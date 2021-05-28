# HTML & CSS

### 1- Links (pp.74-93)
- Creating links between pages
- Linking to other sites
- Email links
#### we will talk about :
  
* Links from one website to another
* Links from one page to another on the same website
* Links from one part of a web page to another part of the 
same page
* Links that open in a new browser window
* Links that start up your email program and address a new 
email to someone


### Writing Links:
 - using **<a href="http://www.imdb.com">IMDB</a>**
 you can:
   - Linking to Other Sites.(putting the link of the website).
   - Linking to Other Pages on the Same Site. (by using #id).
   - **Relative URLs**: Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.
   - **Email Links**: mailto: mailto:example@anything.com
   - openeng links in new window: using _blank

    **<a href="http://www.imdb.com" target="_blank">**
   - Linking to a Specific Part of Another Page.

##### Directory Structure : for larger website you must organize your directories.

![](/Capture.PNG)


### 2- Layout (pp.358-404).

- Controlling the position of elements.
- Creating site layouts.
- Designing for different sized screens.


##### Websites often display content in multiple columns (like a magazine or a newspaper).

![](https://www.w3schools.com/html/img_sem_elements.gif)

- <header> - Defines a header for a document or a section
- <nav> - Defines a set of navigation links
- <section> - Defines a section in a document
- <article> - Defines an independent, self-contained content
- <aside> - Defines content aside from the content (like a sidebar)
- <footer> - Defines a footer for a document or a section
- <details> - Defines additional details that the user can open and close on demand
- <summary> - Defines a heading for the <details> element.


### HTML Layout Techniques

* There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:

  - CSS framework
  - CSS float property
  - CSS flexbox
  - CSS grid


# JavaScript.
### 1- Functions, Methods, and Objects (pp.86-99).

#### Programmers use functions, methods, and objects to organize their code. 
* FUNCTIONS & METHODS
* OBJECTS
* BUILT-IN OBJECT

##### Functions let you group a series of statements together to perform a specific task if you have a thing repeated all the time during the code.
### declare a function.
```
var msg = 'Sign up to receive our newsletter for 10% off!'; 
function updateMessage() { 
var el = document.getElementByld('message'}; 
el .textContent = msg; 
} 
```
### calling function :
`updateMessage();`

#### declare function with parameters.
#### declare function with return value so you can assign it to  variables.

#### ANONYMOUS FUNCTIONS & FUNCTION EXPRESSIONS.

  - An anonymous function is a function without a name. An anonymous function is often not accessible after its initial creation

  - A JavaScript function can also be defined using an expression.

  ` var x = function (a, b) {return a * b};`


# Pair Programming.

pair programming is where two developers work using only one machine. Each one has a keyboard and a mouse. One programmer acts as the driver who codes while the other will serve as the observer who will check the code being written, proofread and spell check it, while also figuring out where to go next. 

### Pair Programming Advantages
  - Two heads are better than one
  - More efficient.
  - Fewer coding mistakes.
  - An effective way to share knowledge.
  - Develops your staff’s interpersonal skills.
