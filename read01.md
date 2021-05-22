# HTML, JS, CSS.

# Introduction

As we have taken on 101 & 102 on this course, The web Pages creates by using (HTML, JavaScript, CSS) together and we know that

* HTML used to describe and define the basic structure of the web page.
* CSS creates the design and how it's will look.

* and JavaScript interacts with the users by its functionality.

# From the Duckett HTML book:

## BUT How the Web Works.➡️ pages (2-11)

##### When you visit a website, the webserver hosting that site could be anywhere in the world. In order for you to find the location of the webserver, your browser will first connect to a Domain Name System (DNS) server

##### People access websites using software called a web browser. 
 
#### Popular examples include
  * Firefox
  * Internet Explorer
  * Chrome
  * Opera. 

##### When you ask your browser for a web page
1- the request is sent across the Internet to a special computer known as a web server that hosts the website.
2- Web servers are special computers that are constantly connected to the Internet and are optimized to send web pages out to people who request them.
3- People are accessing websites on an increasing range of devices including desktop computers, laptops, tablets, and mobile phones. 

```
 It is important to remember that various devices have different screen sizes and some have faster connections to the web than others.
```
## How pages use structure? ➡️ pages(12-39)

#### Think about the stories you read in a newspaper: 

#### for each story, there will be a 
 1- headline
 2- some text
 3- possibly some images.
 
 #####  The structure is very similar when a news story is viewed online (although it may also feature audio or video). 
 
 ##### Now think about a very different type of document — an insurance form.
 1- Insurance firms often have headings for different sections.

 2- each section contains a list of questions with areas for you to fill in details or checkboxes to tick.
 
 - Again, the structure is very similar online.

![](https://3.bp.blogspot.com/-sgm6BBz6KbM/VuarmPKRJ1I/AAAAAAAAG4Q/5GDCRhO09IgiCE2DQXhA0OVaxlylGWvvw/s1600/html-structure.png)

## HTML describes the structure of a page 

#### The HTML code is made up of characters that live inside angled brackets — these are called HTML elements. 

#### Elements are usually made up of two tags:
- an opening tag 
- a closing tag. "The closing tag has an extra forward slash in it." 
```
Each HTML element tells the browser something about the information that sits between its opening and closing tags.
```
#### Looking at how other websites are built

* When the web was first taking off, one of the most common ways to learn about HTML and discover new tips and techniques was to look at the source code that made up web pages.

- These days there are many more books and online tutorials that teach HTML, but you can still look at the code that a web server sends to you.


## The Evolution of HTML ➡️ pages(176-199)

### every new version of HTML was an improvement than the last.

- For example, HTML4 released in 1997, followed by XHTML 1.0 released in the year 2000.
 - It was decided that HTML 4 should be reformulated to follow the rules of XML and it was renamed XHTML. 

This meant that authors had to follow some new, more strict rules about writing markup.


## TRADITIONAL HTML LAYOUTS ➡️ pages(428-451)


As with all HTML5 and CSS3 content, its usage is still subject to change but it is already widely being used by web developers and it is likely that you will want to use them.
HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them. They are still subject to change, but that has not stopped many web page authors from using them already.

For a long time, web page authors used elements to group together related elements on the page (such as the elements that form a header, an article, footer or sidebar). 

Authors used class or id attributes to indicate the role of the element in the structure of the page.

- Headers & Footers, The main header or footer that appears at the top or bottom of every page on the site.
- Navigation, The element is used to contain the major navigational blocks on the site such as the primary site navigation.
- Articles, The element acts as a container for any section of a page that could stand alone and potentially be syndicated.
- Asides. The element has two purposes, depending on whether it is inside an element or not.
- Sections. The element groups related content together, and typically each section would have its own heading.




## WHO IS THE SITE FOR?  pages ➡️ (452-475)

#### Every website should be designed for the target audience—not just for yourself or the site owner.
#### It is therefore very important to understand who your target audience is.

just wait and <span style="color:red">ASK YOURSELF</span>

1- What is the age range of your target audience?

2- Will your site appeal to more women or men? What is the mix?

3- Which country do your visitors live in?

4- Do they live in urban or rural areas?

5- What is the average income of visitors?

6- What level of education do they have?

7- What is their marital or family status?

8- What is their occupation?

9- How many hours do they work per week?

10-How often do they use the web?

11- What kind of device do they use to access the web?

12- Now that you know who your visitors are, you need to consider why  13- they are coming. While some people will simply chance across your 
 14- website, most will visit for a specific reason. And what is the 
 
 15- type of information they need. How often they will visit it.



# From the Duckett JS book:

# JS(JavaScript)

## HOW JAVASCRIPT MAKES WEB PAGES MORE INTERACTIVE! AND FUN! (Introduction) 

#### Javascript allows you to make web pages more interactive by accessing and modifying the content and markup used in a web page while it is being viewed in the browser.
* by using (AMPR)

  - ACCESS CONTENT You can use JavaScript to select any element, attribute, or text from an HTML page.
  -   MODIFY CONTENT You can use JavaScript to add elements, attributes, and text to the page, or remove them.
  -   PROGRAM RULES You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page.
  - REACT TO EVENTS You can specify that a script should run when a specific event has occurred.
Javascript encompasses many of the traditional rules of programming. it can make the web page feel interactive by responding to what the user does.



## A: [WHAT IS A SCRIPT AND HOW DO I CREATE ONE!!] pages ➡️ (11-24).

#### A script is a series of instructions that a computer can follow to achieve a goal.

#### Script are made up of interactions a computer can follow step-by-step. 
#### Acbrowser may use different parts of the script depending on how the user interacts with the web page. 
#### Scripts can run different sections of the code in response to the situation around them.

- To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.

- Start with the big picture of what you want to achieve, and break that down into smaller steps:
  * Define the goal.
  * Design the script.
  * Code each step.


## B: [ How do computers fit in with the world around them? ] pages ➡️ (25-42)

#### Computers creat models of the world using data. 

#### Programmers make these models using data. 

* That is not as strange or as scary as it sounds because the data is all the computer needs in order to follow the instructions you give it to carry out its tasks.

- Objects and properties
  * Objects (things): In computer programming, each physical thing in the world can be represented as an object.

  * Properties (characteristics): Each property has a name and a value, and each of these name/value pairs tells you something about each individual instance of the object.
```
# PUTTING IT ALL TOGETHER!
 Computers use data to create models of things in the real world. The events, methods, and properties of an object all relate to each other: Events can trigger methods, and methods can retrieve or update an object's properties.

```


## C: [How HTML, CSS and Javascript work together?] pages ➡️ (43-52)

1- Content layer: . html files This is where the content of the page lives. The HTML gives the page structure and adds semantics.

2- Presentation layer: . css files The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.).

3- Behavior layer: .js files This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as possible in separate files.

#### Creating a Javascript:
JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script. This example adds a greeting into an HTML page. The greeting changes depending on the time of day.

#### Linking to a Javascript file from an HTML page:
When you want to use JavaScript with a web page, you use the HTML < script > element to tell the browser it is coming across a script. Its s re attribute tells people where the JavaScript file is stored.


# refrences
[Java-Script-Book](https://files.slack.com/files-pri/TNGRRLUMA-F023F5HG1QQ/javascript_and_jquery_interactive_jon_du__1_.pdf)

[HTML-BOOK](https://wtf.tw/ref/duckett.pdf)

![](https://i.gifer.com/EWU7.gif)
