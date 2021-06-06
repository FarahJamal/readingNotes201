# CSS Layout Cheat sheet.

#####  The CSS Grid Layout Module was developed by the CSS Working Group to provide a better way to create website layouts in CSS. It became a Candidate Recommendation in February 2017, and major browsers started to support grid layout in March 2017.

#### CSS Grid Layout will soon be an essential part of any frontend developer's toolbox. If you're a frontend developer, you will need to learn grid — it will almost certainly become a non-negotiable skill in any frontend development position.

#### With its powerful features and intuitive syntax, grid layout will undoubtedly change the way layouts are done on the web.

![](https://www.quackit.com/pix/stock/css_grid_introduction.png).

#### How Grid Works
Grid layout works on a grid system. The grid is an intersecting set of horizontal and vertical lines which create a sizing and positioning coordinate system for the grid container's contents.

To create a grid, you simply set an element to display: grid. This automatically makes all of that element's direct descendents grid items. You can now use the various grid properties to adjust their size and positioning as required. Usually the first step is to define how many rows and columns the grid has

- A grid with 4 rows and 3 columns.

![](https://www.quackit.com/pix/stock/css_grid_4_rows_3_columns.gif)




## Display

- Controls how an element is represented within the flow.

 

`display: inline`
Allows other elements beside; margin, padding & width don’t work.

 

`display: block`
Takes up an entire line; margin, padding & width work.

 

`display: inline-block`
Allows other elements beside; margin, padding & width work. Can create columns, but will force a space between boxes.

## Float

- Controls whether text is wrapped around the element.

 

`float: left|right|none`
Allows other elements to wrap around the element.

 - Multiple floats: Can create columns with boxes touching sides.

 

`clear: left|right|both`
Force the element below floated elements.

 

`overflow: hidden`
Use on a parent element to force it to wrap around the floated children—a clearfix.

## Position

- Gives strict, coordinate-based control over layout.

 

`position: absolute`
Move an element around based on coordinates.

 

`position: relative`
Added to a parent element to reset absolute child’s coordinates.

 

`position: fixed`
Forces an element to not move when the page is scrolled.

 

`z-index`
Control the stacking order of elements—higher number is closer.

## Centering elements
`text-align: center`

- Works only on display: inline & inline-block elements.

- Must be applied to the parent element.
```
<figure class="img-box">
  <img src="images/argentinosaurus.jpg" alt="">
  <figcaption>The mighty Argentinosaurus</figcaption>
</figure>
.img-box {
  text-align: center;
}
```
`margin: 0 auto`

- Works only on display: block elements.

- The element must have a width
```
<div class="box">Stegosaurus</div>
.box {
  width: 24em; /* Without a width `auto` won’t work */
  margin-left: auto;
  margin-right: auto;
}
```
* You can also specify just `margin-left: auto` and `margin-right: auto` if you want margins on the top or bottom.

`vertical-align: middle`

* Works only on display: inline & inline-block elements.
```
<ul>
  <li>Pteranodon</li>
  <li>Quetzalcoatlus</li>
</ul>
ul li {
  display: inline-block;
  vertical-align: middle;
}
```

## Centering absolute

* Use transform & 50% coordinates to center an absolutely positioned element.
```
<div class="banner">
  <div class="content">
    <h1>Micropachycephalosaurus</h1>
    <p>Longest dinosaur name ever!</p>
  </div>
</div>
.banner {
  position: relative;
}
.content {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
}
```

Or vertical centering too…
```
.content {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
```
## Centering with float

# There’s no float: center

# You cannot center floated elements.

#### Centering with flexbox

- Flex box has a bunch of different alignment classes—that are always applied to the parent.
```
<div class="card">
  <h2>Edmontosaurus</h2>
  <a href="#">See the bones!</a>
</div>
.card {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-content: center;
  align-items: center;
}
```
- This will be completely centered within the box.

- See the flexbox cheat sheet for more details.

### Common code
### Border box

- Used to change layout math for width & padding.

* Put at the top of every CSS file.
```
html {
  box-sizing: border-box;
}

*, *::before, *::after {
  box-sizing: inherit;
}
```
### Clearfix for float

- Add to the parent elements of floats to force the parent to surround the floated element.

### Can be used instead of `overflow: hidden`
```
.clearfix::after {
  content: " ";
  display: block;
  clear: both;
}
```
### Flexible images

- Use width & display to make images flex to their parent’s size.
```
img {
  display: block;
  width: 100%;
}
```




