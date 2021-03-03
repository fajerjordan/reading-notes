# HTML Links, JS Functions, and Intro to CSS Layout

## HTML Links - Hyperlinks

HTML links are hyperlinks. You can click on a link and jump to another document. when you move the mouse over a link, the mouse arrow will turn into a little hand. Note: A link does not have to be text. A link can be an image or any other HTML element!

By default, links will appear as follows in all browsers:

An unvisited link is underlined and blue A visited link is underlined and purple An active link is underlined and red Tip: Links can of course be styled with CSS, to get another look!

HTML Links - The target Attribute By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

_self - Default. Opens the document in the same window/tab as it was clicked _blank - Opens the document in a new window or tab _parent - Opens the document in the parent frame _top - Opens the document in the full body of the window Example Use target=”_blank” to open the linked document in a new browser window or tab:

HTML links are hyperlinks. You can click on a link and jump to another document. when you move the mouse over a link, the mouse arrow will turn into a little hand. Note: A link does not have to be text. A link can be an image or any other HTML element!

A local link (a link to a page within the same website) is specified with a relative URL (without the “https://www” part):


## JavaScript Functions

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when “something” invokes it (calls it).

Example function myFunction(p1, p2) { return p1 * p2; // The function returns the product of p1 and p2 }

- Function parameters are listed inside the parentheses () in the function definition.
- Function arguments are the values received by the function when it is invoked.
- Inside the function, the arguments (the parameters) behave as local variables.
- A Function is much the same as a Procedure or a Subroutine, in other programming languages.
- Function Invocation The code inside the function will execute when “something” invokes (calls) the function
- When an event occurs (when a user clicks a button) When it is invoked (called) from JavaScript code Automatically (self invoked) Y
- Function Return When JavaScript reaches a return statement, the function will stop executing.
- If the function was invoked from a statement, JavaScript will “return” to execute the code after the invoking statement.
- Functions often compute a return value. The return value is “returned” back to the “caller”:


Example Calculate the product of two numbers, and return the result:

var x = myFunction(4, 3); // Function is called, return value will end up in x

function myFunction(a, b) { return a * b; // Function returns the product of a and b } The result in x will be:

12 Why Functions? You can reuse code: Define the code once, and use it many times.

You can use the same code many times with different arguments, to produce different results.


## Introduction to CSS layout

CSS page layout techniques allow us to take elements contained in a web page and control where they are positioned relative to their default position in normal layout flow, the other elements around them, their parent container, or the main viewport/window. 

Normal flow is how the browser lays out HTML pages by default when you do nothing to control page layout.

By default, the browser will display this code as follows: Note here how the HTML is displayed in the exact order in which it appears in the source code, with elements stacked up on top of one another — the first paragraph, followed by the unordered list, followed by the second paragraph.

The elements that appear one below the other are described as block elements, in contrast to inline elements, which appear one beside the other, like the individual words in a paragraph.

Note: The direction in which block element contents are laid out is described as the Block Direction. The Block Direction runs vertically in a language such as English, which has a horizontal writing mode. It would run horizontally in any language with a Vertical Writing Mode, such as Japanese. The corresponding Inline Direction is the direction in which inline contents (such as a sentence) would run.

For many of the elements on your page, the normal flow will create exactly the layout you need, however for more complex layouts you will need to alter this default behavior using some of the tools available to you in CSS. Starting with a well-structured HTML document is very important, as you can then work with the way things are laid out by default rather than fighting against it.

The methods that can change how elements are laid out in CSS are as follows:

The display property — Standard values such as block, inline or inline-block can change how elements behave in normal flow, for example making a block-level element behave like an inline element (see Types of CSS boxes for more information). We also have entire layout methods that are switched on via specific display values, for example CSS Grid and Flexbox, which alter how elements inside the element they are set on are laid out. Floats — Applying a float value such as left can cause block level elements to wrap alongside one side of an element, like the way images sometimes have text floating around them in magazine layouts. The position property — Allows you to precisely control the placement of boxes inside other boxes. static positioning is the default in normal flow, but you can cause elements to be laid out differently using other values, for example always fixed to the top of the browser viewport. Table layout — features designed for styling the parts of an HTML table can be used on non-table elements using display: table and associated properties. Multi-column layout — The Multi-column layout properties can cause the content of a block to layout in columns, as you might see in a newspaper.






