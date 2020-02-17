# Read:03 Summary

## From the Duckett HTML book:

***Chapter 3: “Lists” (pp.62-73)***
> There are different types of lists : .

1. Ordered lists : are lists where each item in the list is numbered.
  * We use `<ol> element ` for this
  * Each item in the list is placed between an opening `<li>` tag and a closing `</li>` tag. (The `li` stands for list item.)
  * It is better to use the CSS `liststyle-type` property covered on pages 333-335 to specify the type of numbering (numbers, letters, roman numerals and so on). 

2. Unordered lists : are lists that begin with a (bullet) point (rather than characters that indicate order).
  * The unordered list is created with the `<ul>` element
  * Each item in the list is placed between an opening `<li>` tag and a closing `</li>` tag. (The `li` stands for list item.)
  * It is better to use the CSS `list-styletype ` property covered on pages 333-335 to specify the type of bullet point (circles, squares, diamonds and so on). 


3. Definition lists : are made up of a set of terms along with the definitions for each of those terms.
  * `<dl>` : The definition list is created with the `<dl> ` element and usually consists of a series of terms and their definitions.Inside the `<dl>` element you will usually see pairs of `<dt>` and `<dd>` elements.
  * `<dt>` This is used to contain the term being defined (the definition term). 
  * `<dd>` This is used to contain the definition.
  * ex : `( <dl><dt><dd></dd></dt></dl> `
4. Nested list : 
  * You can put a second list inside an `<li>` element to create a sublist or nested list.
  * ex :` (<ul><li><ul><li></li></ul></li></ul> )`
  
  -----------------------------------------------------------------------------------------------------------------------------------
  
  ***Chapter 13: “Boxes” ( for more understandig see pp.300-329)***
  
  > CSS treats each HTML element as if it lives in its own box .
  
  
  *  `width, height`  To set your own dimensions for a box using units of pixels( most popular method ) , percentage(the size of the box      is relative to the size of the browser window ) , ems (the size of the box is based on the size of text within it)
  * `min-width, max-width` : `min-width ` property specifies the smallest size a box can be displayed at when the browser window is         narrow and to make sure that they do not appear too narrow , and the `max-width` property indicates the maximum width a box can         stretch to when the browser window is wide and to ensure that lines of text do not appear too wide within a big browser window.
  * You can limiting the height too using : ( `min-height, max-height`)
  * The (overflow) property tells the browser what to do if the content contained within a box is larger than the box itself. It can         have one of two values: hidden and scroll
  * Every box has three available properties that can be adjusted to control its appearance :border,margin and padding
  * The padding and margin properties are very helpful in adding space between various items on the page
  * The `border-width` property is used to control the width of a border. The value of this property can either be given in pixels or       using one of the following values:thin medium thick
  * You can control the style of a border using the border-style property. 
  * You can specify the color of a border using either RGB values, hex codes or CSS color names 
  * The border property allows you to specify the width, style and color of a border in one property 
  * The padding property allows you to specify how much space should appear between the content of an element and its border. 
  * The margin property controls the gap between boxes. Its value is commonly given in pixels, although you may also use .
  * The display property allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an     element from the page. 
  
  -----------------------------------------------------------------------------------------------------------------------------------
  
 ## From the Duckett JS book :
  
  ***Chapter 4: “Decisions and Loops” from switch statements on (for more understanding see pp.162-182)***
  
  > A switch statement starts with a variable called the switch value. Each case indicates a possible value for
  > this variable and the code that should run if the variable matches that value . 
  
  * Logical operators are processed left to right. They short-circuit (stop) as soon as they have a result - but they return the value       that stopped the processing (not necessarily true or fa 1 se). 
  * There are the common types of loops : for , while and do while
     1. for loop : used to loop through the items in an array. 
     2. while : run for as long as the condition in the parentheses is true
     3. do while : difference between a whi 1 e loop and a do whi 1e  loop is that the statements in the code block come before the             condition. This means that those statements are run once whether or not the condition is met.
  




  
  
  
  
  
  
  
  
  
  
  
