# From the Duckett HTML book:

## Chapter 2: “Text” (pp.40-61)

* there is two types of markup that we can add to the text :

1. Structural markup:  the elements that you can use to describe both headings and paragraphs

2. Semantic markup: which provides extra information; such as where emphasis is placed in a sentence, that
something you have written is a quotation (and who said it), the meaning of acronyms, and so on

* HTML has six "levels" of headings: h1 to h6

* By default, a browser will show each paragraph on a new line with 
some space between it and any subsequent paragraphs.

* By enclosing words in the tags `<b>` and `</b>` we can make characters appear bold.

* By enclosing words in the tags `<i>` and `</i>` we can make characters appear italic(such as technical terms,
names of ships, foreign words, thoughts, or other terms that would usually be italicized

* The `<sup>`  element is used to contain characters that should be superscript such as the suffixes of dates or 
mathematical concepts like raising a number to a power such as 2^2.such as `(4<sup>th</sup> )`
  
* The `<sub>` element is used to contain characters that should be subscript. It is commonly 
used with foot notes or chemical formulas such as co2.such as`( CO<sub>2</sub> )`
  
* white space collapsing : When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too.(so if there is two or more spaces between the words in the `<p></p>` tag so the browser will display just one space)

* `<br />` : if you wanted to add a line break inside the middle of a paragraph you can use the line break tag `<br />`so to move to a new line we use this.

* `<hr />` : To create a break between themes — such as a change of topic in a book or a new scene in a play — you 
can add a horizontal rule between sections using the `<hr />` tag.(it makes a new empty line then aline like ------ then a new empty line)

* empty elements : elements that do not have any words between an opening and closing tag and has only one tag. (such as the `<hr />` tag)

* Visual ediTors : such as Dreamweaver usually have two views of the page you are creating: a visual editor and a code view.

* Visual editors often resemble word processors. Although each editor will differ slightly, there are
 some features that are common to most editors that allow you to control the presentation of text.
 
* Code views show you the code created by the visual editor so you can manually edit it, or so you can just enter new code yourself. It is often activated using a button with an icon that says HTML or has angled brackets. White space may be added to the
 code by the editor to make the code easier to read
 
* semanTic markup:text elements that are not intended to affect the structure of your web pages, but they do add extra 
information to the pages — they are known as semantic markupThe reason for using these elements is that other programs, such as 
screen readers or search engines, can use this extra information.such as :

1. (emphasis) : `<em>` element that allows you to indicate where emphasis should be placed on selected words. the content of the 
`<em>` element is shown in italics .By default browsers will show the contents of an `<em>` element in italic.`(ex <em>first</em> so first will be in italic)`.

2. `<blockquote>` element which indicates that a block of text is a quotation. `<blockquote>` is usually indented. 
  
* The use of the `<strong>` element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis.By default, browsers will show the contents of a `<strong>` element in bold.`(ex <p><strong>Beware:</strong> so beware will be in bold )` 
  
* Quotations : There are two elements commonly used for marking up quotations:

1. The `<blockquote>` element is used for longer quotes that take up an entire paragraph.`( ex <blockquote> <p>text to quote</p></blockquote>)`
  
2. `<q>` : The `<q>` element is used for shorter quotes that sit within a paragraph. Browsers are supposed to put
 quotes around the `<q>` element.`( ex <p> any text <q>something to quote to be in ""</q></p>  )`
  
* the `<abbr>` element can be used. A title attribute on the opening tag is used to specify the full term.`(ex <p><abbr title="Professor">Prof</abbr>....</p> so the result will be prof but we specify prof more using </abbr> .)`

* `<acronym>` : element In HTML 4  To spell out the full form of the acronym, the title attribute was 
used (as with the `<abbr>` element above). HTML5 just uses the `<abbr>` element for both abbreviations and acronyms.( so its the same as `</abbr>` but in html 4 )
  
* `<cite>` : When you are referencing a piece of work such as a book, film or research paper, the  `<cite>` element can
 be used to indicate where the citation is from.`( ex <p><cite>A Brief History of Time</cite><p> so words between <cite> will be in italics .`
  
* `<dfn>` : The `<dfn>` element is used to indicate the defining instance of a new term.The first time 
you explain some new terminology (perhaps an academic concept or some jargon) in a document, it is known as
 the defining instance of it.`( ex <p>A <dfn>black hole</dfn> and the content between the <dfn> will resulted the same)`
  
* `<address>`: The `<address>` element has quite a specific use: to contain contact details for the author of the page.It can contain
 a physical address, but it does not have to. For example, it may also contain a phone number or email address.Browsers 
often display the content of the `<address>` element in italics.`(ex <address><p><a href="mailto:homer@example.org">   homer@example.org</a></p> ; <p>742 Evergreen Terrace, Springfield.</p> </address> so the result will be that "homer@example.org" will be italic and linkable and "742 Evergreen Terrace, Springfield " will be just in italic.)`
  
* `<del>` : the `<del>` element can show text that has been deleted from it.`(ex <p><del>test..</del></p> so the text will shown as removed text )`
  
* `<ins>` : The `<ins>` element can be used to show content that has been inserted into a document.The content of
 a `<ins>` element is usually underlined.`( ex <p><ins> text..</ins><p> so the text will be underlined.)`
  
* `<s>` : The `<s>` element indicates something that is no longer accurate or relevant (but that should not 
be deleted).`( ex <p><s>Was $995</s></p>  so Was $995 will shows as deleted )`

----------------------------------------------------------------------------------------------------------------------
## Chapter 10: Ch.10 “Introducing CSS” (pp.226-245)

* In this section, we will look at how to make your web pages more attractive, controlling the
 design of them using CSS.CSS allows you to create rules that specify how the content of an element should appear.
 
* CSS treats each HTML element as if it appears inside  its own box and uses rules to indicate 
how that element should look.

* Rules are made up of selectors (that specify the  elements the rule applies to) and 
declarations (that indicate what these elements should look like).

* Different types of selectors allow you to target your  rules at different elements.

* Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.

* CSS rules usually appear in a separate document,  although they may appear within an HTML page.

---------------------------------------------------------------------------------------------------------------------------
# From the Duckett JS book:

## Chapter 2: “Basic JavaScript Instructions” (pp.53-84)

* In this chapter, you will start learning to read and write JavaScript. You will also learn
 how to give a web browser instructions you want it to follow. 
 
* JAVASCRIPT IS CASE SENSITIVE 

* A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or 
step is known as a statement. Statements should end with a semicolon. 

* comments :we use it  to explain what your code does. They help make your code easier to read and understand. 

* A variable is a good name for this concept because the data stored in a variable can
 change (or vary) each time a script runs.
 
* DATA TYPES : numbers, strings, and true or false values known as Booleans.

* `ARRAYS` :  is a special type of variable. It doesn't just store one value; it stores a list of values. 

* You should consider using an array whenever you are working with a list or a set of values that are 
related to each other. 

* Arrays are especially helpful when you do not know how many items a list will contain because, when you create the array, you do not 
need to specify how many values it will hold. 

* values in an array are separated by commas. 

* example : `( var colors;    colors ['white', 'black', 'custom']; )` called array literal (it is the preffered technique).The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array

* another technique is called array constructor .such as `( var colors =  new Array('white' , 'black', 'custom');    )`

* Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this 
list starts at zero (not one). 

1. NUMBERING ITEMS IN AN ARRAY : Each item in an array is automatically given a number called an index. This can be used 
to access specific items in the array. `(ex var colors; colors= ['white' , 'black ' , ' custom']; ) so INDEX VALUE = 0 for
array value = 'white ' and INDEX VALUE = 1 for array value = 'black ' et..)`

2. ACCESSING ITEMS IN AN ARRAY : To retrieve the third item for example in the above code so we
 write `(var itemThree; itemThree = colors[2] ; )`
 
3. NUMBER OF ITEMS IN AN ARRAY : Each array has a property called length, which holds the number of items
 in the array.`( ex var numColors; numColors =colors.length; )`
 
4. CHANGING VALUES IN AN ARRAY (updating) : `( ex  the third item on the list is changed from 'custom' to 'beige' like this colors[2] = 'beige' ; )`
------------------------------------------------------------------------------------------------------------------------------
## Chapter 4: “Decisions and Loops” only up to the section on switch statements (pp.145-162)

* the code can take more than one path, which means the browser runs different code in different situations. In this chapter, you will learn how to create and control the flow of data in your scripts to handle different situations.

* Decision making : there is two components for a decision :

1. expression is evaluated which returns a value 

2. conditional statement says what to do in the given situation 

* `( score >= pass )` this condition have : operator(>=) and two operands ( score and pass) and the operand 
usually is a variable or value or expression.

* Comparison operators `(===, ! ==, ==, ! =, <, >, <=, =>)` are used to compare two operands. 

* Logical operators allow you to combine more than one set of comparison operators. 



 





















