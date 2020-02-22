# Read:06 Summary

> The hardest thing about writing code are :

   * earning a new technology
   * Naming things
   * Testing your code
   * Debugging
   * Fixing bugs
   * Making software maintainable
***To make programming easier :***
   * Make the problem domain easier
   * Get better at understanding the problem domain
* You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.
* It is easy to fall into the trap of thinking you understand enough of the problem to get started coding it

------------------------------------------------------------------------------------------------------------------------------------

## From the Duckett JS book :
### Chapter 3: “Object Literals” (for more understanding see pp.100-105)

> Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

* Properties tell us about the object
* Methods represent tasks that are associated with the object
* properties and methods have a name and a value. In an object, that name is called a key.
* An object cannot have two keys with the same name
***Programmers use a lot of name/value pairs :***
   * HTML uses attribute names and values.
   * CSS uses property names and values.
* Variables have a name and you can assign them a value of a string, number, or Boolean in Java Script
* Arrays have a name and a group of values. (Each item in an array is a name/value pair because it has an index number and a value.
* Objects consist of a set of name/value pairs (but the names are referred to as keys). 
* Named functions have a name and value that is a set of statements to run if the function is called.

-----------------------------------------------------------------------------------------------------------------------------------

### Chapter 5: “Document Object Model” (for more understanding see pp.183-242)

> The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window

***The DOM specifies the way in which the browser should structure this model using a DOM tree**
***The DOM is called an object model because the model (the DOM tree) is made of objects.*** 
***The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas :***
   * MAKING A MODEL OF THE HTML PAGE 
   * Accessing and changing the html page
***The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser***
* Each node is an object with methods and properties. Scripts access and update this DOM tree (not the source HTML file). Any changes made to the DOM tree are reflected in the browser.
***Accessing and updating the DOM tree involves two steps :***
   * Locate the node that represents the element you want to work with
   * Use its text content, child elements, and attributes
* The terms elements and element nodes are used interchangeably but when people say the DOM is working with an element, it is actually working with a node that represents that element
* DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes
* When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element). 
* When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM
* Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements
* When you select a text node, you can retrieve or amend the content of it using the node Va 1 ue property
* The textContent property allows you to collect or update just the text that is in the containing element (and its children
* Using the i nnerHTML property, you can access and amend the contents of an element, including any child elements
* DOM manipulation can be used to remove elements from the DOM tree. 
* Modern browsers come with tools that help you inspect the page loaded in the browser and understand the structure of the DOM tree
