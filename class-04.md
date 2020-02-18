
# Read:04-Summary 
## From the Duckett HTML book:
### Chapter 4: Ch.4 “Links” ( for more understanding see pp.74-93)
* Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing.

* Types of links :

   * Links from one website to another : Links are created using the `<a>` element which has an attribute called `href`. The value of the href attribute is the page that you want people to go to when they click on the link.
   
   * Linking to A sPeciFic PArt oF Another PAge : if you want to link to a specific part of a different page (whether on your own site or a different website) you can use a similar technique

   * Links from one page to another on the same website : When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL
  
   * Links from one part of a web page to another part of the same page : you need to identify the points in the page that the link will go to. You do this using the id attribute (which can be used on every HTML element). You can see that the `<h1>` and `<h2>` elements in this example have been given `id` attributes that identify those sections of the page
  
   * Links that open in a new browser : you can use the target attribute on the opening  `<a>` tag. The value of this attribute should be` _blank.`

   * Links that start up your email program and address a new email to someone : you will use the `<a>` element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.

 
* Links are created using the `<a>` element. Users can click on anything between the opening `<a>` tag and the closing `</a>` tag. You specify which page you want to link to using the href attribute 


* Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.
----------------------------------------------------------------------------------------------------------------------------------------

### Chapter 15: “Layout” (for more understanding see pp.358-404)

*  we are going to look at how to control where each element sits on a page and how to create attractive page layouts.
* position elements using normal `flow, relative positioning, absolute positioning and floats `
* CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
   * Block-level elements start on a new line Examples include: `<h1> <p> <ul> <li>`
   * inline elements flow in Between surrounding text Examples include: `<img> <b> <i>`
* It is common to group a number of elements together inside a `<div>` (or other block-level) element
* positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property
* box offset properties to tell the browser how far from the top or bottom and left or right it should be placed.
* Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens
* Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their 
* web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens
* Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels
* Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.
* Grids set consistent proportions and spaces between items which helps to create a professional looking design
* CSS frameworks aim to make your life easier by providing the code for common tasks
* There are two ways to add multiple style sheets to a page:
   * Your HTML page can link to one style sheet and that stylesheet can use the @import rule to import other style sheets.
   * In the `HTML` you can use a separate `<link>` element for each style sheet.
   
* Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning
---------------------------------------------------------------------------------------------------------------------------------------
## From the Duckett JS book :
### Chapter 3 (first part): “Functions, Methods, and Objects” (for more understanding see pp.86-99 ONLY)

* Programmers use functions, methods, and objects to organize their code. 
  * Functions  : Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements). 
* Expressions produce a value. They can be used where values are 
* The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's scope
* Functions can take parameters (information) required to do their job and may return a value
 --------------------------------------------------------------------------------------------------------------------------------------
 
 ### Article: “6 Reasons for Pair Programming” :
 
 * pair programming : is the practice of two developers sharing a single workstation to interactively tackle a coding task together.
 * pair programming commonly involves two roles: the Driver and the Navigator
   * The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding
   * the Driver manages the text editor, switching files, version control, and—of course writing—code
 * Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.
 * Reasons for Pair Programming :
    * Greater efficiency
    * Engaged collaboration
    * Learning from fellow students
    * Social skills
    * Job interview readiness
    * Work environment readiness
  
  












