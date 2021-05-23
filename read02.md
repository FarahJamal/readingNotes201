# Texts in HTML. Pages (40-61)
### I will summarize:

  * Headings and paragraphs
  * Bold, italic, emphasis
  * Structural and semantic markup

#### When creating a web page, you add tags  (known as markup) to the contents of the page. 
#### These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.

- **Structural markup**: the elements that you can use to 
describe both headings and paragraphs
 
- **Semantic markup**: which provides extra information; such 
as where emphasis is placed in a sentence, that something 
you have written is a quotation (and who said it), the 
meaning of acronyms, and so on.


##### Texts in HTML have many types:
  * headings.
    - <h1-h6> --> bigger then smaller.
  * paragraphs.
    - <p>.
  * **Bold** & *Italic*.
    - <b> --> **bold**.
    - <i> --> *Italic*.
  * Superscript & Subscript.
    - <sup> --> x<sup>2</sup>
    - <sub> --> x<sub>2</sub>
  * White Space.
    - not effected on anything.
  * Line Breaks & Horizantal rules.
    - <br> --> new line.
    - <hr> --> Horizantal Line.
  * Strong & Emphasis.
    - <strong> --> **strong**.
    - <em> --> *emphasis*
  * Quotations.
    - <blockquote>
    - <q>

  * bbreviations & Acronyms.
    - <abbr>

      *  A title attribute on the opening tag is used to specify the full term
  * Citations & Definitions.
    * <cite>

      - the <cite> element can be used to indicate where the citation is from.  
    * <dfn>

      - The <dfn> element is used to  indicate the defining instance of a new term.

  * Author Details. 
    * The <address> element.
  * Changes to Content.
    * <ins> --> underlined Text.
    * <del> -->~~hello~~
    * <s>   --> ~~hello~~

## Introduction to CSS pages(226-245).
#### The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

### CSS Associates Style  rules with HTML elements.

 #### 1- CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.

#### 2- CSS works by associating rules with HTML elements. 

#### 3- These rules govern how the content of specified elements should be displayed. 
A CSS rule contains two parts:
  * selector
  * declaration.

### CSS Properties Affect How Elements Are Displayed.

####  CSS declarations sit inside curly brackets and each is made up of two parts:
- a property
- value, separated by a colon. 
``` 
You can specify several properties in one declaration, each separated by a semi-colon.
```
## types of CSS.

### External CSS.
 ##### by using ` <link href="css/styles.css" type="text/css" `
### Internal CSS.
  ##### by put your css inside <style> tag on the <head> tag.
###  Inline CSS.
  ##### by butting your style as attribute inside the tag.

# JavaScript

#### 1- JavaScript is the world's most popular programming language.
#### 2- JavaScript is the programming language of the Web.
#### 3- JavaScript is easy to learn.

### 1- variables.
 ##### JavaScript variables are containers for storing data values.
  - strings.
  - numbers.
  - booleans.
##### using var and let.

### 2-Arrays.
  ##### JavaScript arrays are used to store multiple values in a single variable.
  ```
  var cars = ["Saab", "Volvo", "BMW"];

  ```
### 3-Expressions.
  ##### An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.

### 4-operators
  ##### xpressions rely on things called operators; they allow programmers to create a single value from one or more values. 

### 5-Arethmatic operators.
##### JavaScript contains the following mathematical operators, which you can use with numbers. You may remember some from math class.
 - +
 - -
 - \* 
 - /
 - %
 - ++
 - --

 ## Switch pages (145-162).
 #### The switch statement is used to perform different actions based on different conditions.


 ##### A switch statement starts with a variable called the switch value.  Each case indicates a possible value for this variable and the code that should run if the variable matches that value. 


## Syntax
``` 
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
```

### This is how it works:

- The switch expression is evaluated once.
* The value of the expression is compared with the values of each case.
* If there is a match, the associated block of code is executed.
* If there is no match, the default code block is executed.





