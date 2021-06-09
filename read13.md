# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS
web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

* Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.
* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).
* Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful
What we really want is:
a lot of storage space, on the client, that persists beyond a page refresh and isn’t transmitted to the server.

# HTML5 STORAGE
it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you.
Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually), Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

# USING HTML5 STORAGE
HTML5 Storage is based on named key/value pairs, You store data based on a named key, then you can retrieve that data with the same key, The named key is a string, The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.
However, the data is actually stored as a string, If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

# TRACKING CHANGES TO THE HTML5 STORAGE AREA
track programmatically of when the storage area changes, you can trap the storage event.
 The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire, because nothing actually changed in the storage area.
The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener (although that will finally be added in IE 9). Therefore, to hook the storage event, you’ll need to check which event mechanism the browser supports. (If you’ve done this before with other events, you can skip to the end of this section. Trapping the storage event works the same as every other event you’ve ever trapped. If you prefer to use jQuery or some other JavaScript library to register your event handlers, you can do that with the storage event, too.)

# LIMITATIONS IN CURRENT BROWSERS
In talking about the history of local storage hacks using third-party plugins, I made a point of mentioning the limitations of each technique, such as storage limits. I just realized that I haven’t mentioned anything about the limitations of the now-standardized HTML5 Storage. I’ll give you the answers first, then explain them. The answers, in order of importance, are “5 megabytes,” “QUOTA_EXCEEDED_ERR,” and “no.”

“5 megabytes” is how much storage space each origin gets by default, This is surprisingly consistent across browsers, although it is phrased as no more than a suggestion in the HTML5 Storage specification. One thing to keep in mind is that you’re storing strings, not data in its original format. If you’re storing a lot of integers or floats, the difference in representation can really add up. Each digit in that float is being stored as a character, not in the usual representation of a floating point number.
![](https://pbs.twimg.com/media/EYvP6meWsAIvhNq.jpg)