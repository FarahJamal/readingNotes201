# HTML
## 1- Lists Pages(62-73)
  * **Numbered lists**
    
    - Also known as Ordered List.
    - The HTML <ol> tag defines an ordered list. 
    - An ordered list can be numerical or alphabetical.
  * **Bullet lists**
    - Also known as unordered lists.
    - The HTML <ul> tag defines an unordered list.
    - begin with a bullet point (rather than characters that indicate order).
  * **Definition lists** 
    - The <dl> tag defines a description list.

    - The <dl> tag is used in conjunction with <dt> (defines terms/names) and <dd> (describes each term/name). 

#### you can also use nested lists 
##### example:
```
<ul>
<li>Mousses</li>
<li>Pastries
 <ul>
 <li>Croissant</li>
 <li>Mille-feuille</li>
 <li>Palmier</li>
 <li>Profiterole</li>
 </ul>
</li>
<li>Tarts</li>
</ul>
```

## 2- Boxes Pages(300-329)
* Controlling size of boxes
  * Dimensions
    - width.
    - height.
  * Limiting width
    - min-width.
    - max-width.
  * Limiting height
    - min-height.
    - max-height.
* Box model for borders, margin and padding
  - **Border** : The border separates the edge of one box from another.
  - **Margin** :Margins sit outside the edge of the border
  - **Padding** :Padding is the space between the border of a box and any content contained within it.

  ![](https://i0.wp.com/css-tricks.com/wp-content/uploads/2016/01/AT-box-model.png) 
  ### `you can style them by CSS `
* Displaying and hiding boxes
  - visibility.
    * hidden.
    * visible.
* images Border.
  - border-image 
* box shadows
  - Horizontal offset.
  - vertical offset.
  - blur distance
  - spread of shadow.

* rounded corners
  - border-radius


# JavaScript.
## 1- Basic JavaScript Instructions (pp.70-73).
#### in this chapter I'll show some instruction for Arrays create.
  - An array is a special type of variable. It doesn't just store one value; it stores a list of values. 

  ```
var colors; 
colors ['white', 'black', ' custom']; 
var el document.getElementByld('col ors'); 
el . textContent = col ors[O]; 
 ```
 - arrays starts from index [0].

  - you can change the array element by replace the value by mention it's index.
  ```
  
  var colors = ['white', 'black' , 'custom']; 
colors[2] = 'beige ' ; 
var el = document .getElementByid(' colors') ; 
el .textContent = colors[2]; 

## 2- Decisions and Loops from switch statements on (pp.162-182)

  * SWITCH STATEMENTS 
    - A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value. 

* LOOPS 
   - Loops can execute a block of code a number of times.
   - Loops are handy, if you want to run the same code over and over again, each time with a different value.
  - Often this is the case when working with arrays:

```
 text += cars[0] + "<br>";
text += cars[1] + "<br>";
text += cars[2] + "<br>";
text += cars[3] + "<br>";
text += cars[4] + "<br>";
text += cars[5] + "<br>";
```

## insted you can write:
```
var i;
for (i = 0; i < cars.length; i++) {
  text += cars[i] + "<br>";
}
```

#### Different Kinds of Loops

* JavaScript supports different kinds of loops:

  - for - loops through a block of code a number of times
  - for/in - loops through the properties of an object
  - for/of - loops through the values of an iterable object
  - while - loops through a block of code while a specified condition is true
  - do/while - also loops through a block of code while a specified condition is true

##### 2-Truthy and falsy values.

 * A falsy value is something which evaluates to FALSE, for instance when checking a variable. 
    - There are only six falsey values in JavaScript:
      
      1-  undefined
      2- null
      
       3- NaN
      
        4- 0
      
         5- "" (empty string)
      
      6- false.

  - everything else is consider as truthy.








