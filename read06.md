# Read:06 \| JS Object Literals & The DOM
[Textbook](https://files.slack.com/files-pri/TNGRRLUMA-F023F5HG1QQ/javascript_and_jquery_interactive_jon_du__1_.pdf): _Jon Duckett: JavaScript.**(JS book: Chapters 3 + 5)** 

Article: [Understanding the problem domain is the hardest part of programming](http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming)

---
## JS | Object Literals
---
> Objects contain a set of **variables** and **functions** that create a **model** of something    
- **variables** become known as a **property** inside an Object, like the *name* of something
- **functions** become known as a **method** that performs a task like check how many rooms in the hotel object are booked
- The **property** names are called the **key**, each Object has **key** / **value** pairs in their list of **properities**
	- Ex: `name: ‘Jack’,` *name*  is the **key** and *Jack* is the **value** of the **key** and the **key** is the *name* **property** in the **object**
- The textbook referenced above does a great job with visuals for **Creating an Object Literal** and **Accessing an Object Literal w/Dot Notation**, so I’ve added the images below: 

  **Creating an Object Literal**  
  <img src='https://miro.medium.com/max/875/1*gslNlU_BKtZuSyjLMbmp7Q.png' width='300px'>

 

---
## HTML + JS | Document Object Model (DOM)
---
- When you open a browser (like Chrome) the Object you first see is the window (the browser tab) and inside that object, the document object is rendered
- The Document Object Model represents the HTML page and contains properties, methods, and events
- The DOM receives initial HTML code and stores a model of it in memory (often referred to as the DOM tree), which is where JavaScript will interact with the HTML

![](https://www.w3schools.com/js/pic_htmltree.gif)

### With the object model, JavaScript gets all the power it needs to create dynamic HTML:

- JavaScript can change all the HTML elements in the page
- JavaScript can change all the HTML attributes in the page
- JavaScript can change all the CSS styles in the page
- JavaScript can remove existing HTML elements and attributes
- JavaScript can add new HTML elements and attributes
- JavaScript can react to all existing HTML events in the page
- JavaScript can create new HTML events in the page


### types of DOM:
- Core DOM - standard model for all document types.
- XML DOM - standard model for XML documents.
+ HTML DOM - standard model for HTML documents.
  + The HTML DOM is a standard object model and programming interface for HTML. It defines:

      + The HTML elements as objects
      + The properties of all HTML elements
      + The methods to access all HTML elements
      + The events for all HTML elements

### **TL;DR**:
- The HTML DOM is a standard for how to get, change, add, or delete HTML elements.
- The XML DOM defines a standard way for accessing and manipulating XML documents. It presents an XML document as a tree-structure. Understanding the DOM is a must for anyone working with HTML or XML.
- DOM Core defines the event and document model the Web platform uses. 




#### Nodes
> DOM trees have 4 types of Nodes that are used as reference for navigating, accessing and updating various aspects of the website. If a query has more than one node, it will return a NodeList  
- **Document Nodes**: `document` node which encompasses ALL nodes on the page
- **Element Nodes**: These are the element tags like `<h1>` or `<p>` etc.
- Can select them by `id` or `class`, tag name or CSS selector syntax
- Access and Update content using properties like `textContent` and `innerHTML`
- Can contain multiple **text** nodes, child elements that are siblings of each other
- **Attribute Nodes**: The attr’s in the opening tag, like `src=` or `alt=` etc.
- **Text Nodes**: The text between tags

- You access the DOM in various ways referencing Element or Attribute nodes.

---
## Article | [Understanding the problem domain is the hardest part of programming](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)
---
- Often times the Problem Domain isn't clear which will lead to bad code
- Be sure to have a clear understanding of the Problem Domain before starting the code
- You can simply the Problem Domain but cutting it into smaller chunks


[here you'll find DOM cheat sheet for JS and HTML](http://patatatech.me/readingNotes201/DOMcheatsheet)
