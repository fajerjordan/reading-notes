# HTML Links - Hyperlinks
# HTML links are hyperlinks.

## You can click on a link and jump to another document.

## when you move the mouse over a link, the mouse arrow will turn into a little hand.

## Note: A link does not have to be text. A link can be an image or any other HTML element!

Example
This example shows how to create a link to W3Schools.com:

<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>

By default, links will appear as follows in all browsers:

An unvisited link is underlined and blue
A visited link is underlined and purple
An active link is underlined and red
Tip: Links can of course be styled with CSS, to get another look!

HTML Links - The target Attribute
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

_self - Default. Opens the document in the same window/tab as it was clicked
_blank - Opens the document in a new window or tab
_parent - Opens the document in the parent frame
_top - Opens the document in the full body of the window
Example
Use target="_blank" to open the linked document in a new browser window or tab:

<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
Absolute URLs vs. Relative URLs
Both examples above are using an absolute URL (a full web address) in the href attribute.

A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part):

Example
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>
ADVERTISEMENT


HTML Links - Use an Image as a Link
To use an image as a link, just put the <img> tag inside the <a> tag:

Example
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
Link to an Email Address
Use mailto: inside the href attribute to create a link that opens the user's email program (to let them send a new email):

Example
<a href="mailto:someone@example.com">Send email</a>
Button as a Link
To use an HTML button as a link, you have to add some JavaScript code.

JavaScript allows you to specify what happens at certain events, such as a click of a button:

Example
<button onclick="document.location='default.asp'">HTML Tutorial</button>
Tip: Learn more about JavaScript in our JavaScript Tutorial.

Link Titles
The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.

Example
<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>
More on Absolute URLs and Relative URLs
Example
Use a full URL to link to a web page: 

<a href="https://www.w3schools.com/html/default.asp">HTML tutorial</a>

Example
Link to a page located in the html folder on the current web site: 

<a href="/html/default.asp">HTML tutorial</a>

Example
Link to a page located in the same folder as the current page: 

<a href="default.asp">HTML tutorial</a>


# Introduction to CSS layout

## CSS page layout techniques allow us to take elements contained in a web page and control where they are positioned relative to their default position in normal layout flow, the other elements around them, their parent container, or the main viewport/window.  The page layout techniques we'll be covering in more detail in this module are

Normal flow
The display property
Flexbox
Grid
Floats
Positioning
Table layout
Multiple-column layout
Each technique has its uses, advantages, and disadvantages, and no technique is designed to be used in isolation. By understanding what each method is designed for you will be in a good place to understand which is the best layout tool for each task.

Normal flow
Normal flow is how the browser lays out HTML pages by default when you do nothing to control page layout. Let's look at a quick HTML example:

<p>I love my cat.</p>

<ul>
  <li>Buy cat food</li>
  <li>Exercise</li>
  <li>Cheer up friend</li>
</ul>

<p>The end!</p>
By default, the browser will display this code as follows:



Note here how the HTML is displayed in the exact order in which it appears in the source code, with elements stacked up on top of one another — the first paragraph, followed by the unordered list, followed by the second paragraph.

The elements that appear one below the other are described as block elements, in contrast to inline elements, which appear one beside the other, like the individual words in a paragraph.

Note: The direction in which block element contents are laid out is described as the Block Direction. The Block Direction runs vertically in a language such as English, which has a horizontal writing mode. It would run horizontally in any language with a Vertical Writing Mode, such as Japanese. The corresponding Inline Direction is the direction in which inline contents (such as a sentence) would run.

For many of the elements on your page the normal flow will create exactly the layout you need, however for more complex layouts you will need to alter this default behavior using some of the tools available to you in CSS. Starting with a well-structured HTML document is very important, as you can then work with the way things are laid out by default rather than fighting against it.

The methods that can change how elements are laid out in CSS are as follows:

The display property — Standard values such as block, inline or inline-block can change how elements behave in normal flow, for example making a block-level element behave like an inline element (see Types of CSS boxes for more information). We also have entire layout methods that are switched on via specific display values, for example CSS Grid and Flexbox, which alter how elements inside the element they are set on are laid out.
Floats — Applying a float value such as left can cause block level elements to wrap alongside one side of an element, like the way images sometimes have text floating around them in magazine layouts.
The position property — Allows you to precisely control the placement of boxes inside other boxes. static positioning is the default in normal flow, but you can cause elements to be laid out differently using other values, for example always fixed to the top of the browser viewport.
Table layout — features designed for styling the parts of an HTML table can be used on non-table elements using display: table and associated properties.
Multi-column layout — The Multi-column layout properties can cause the content of a block to layout in columns, as you might see in a newspaper.


# JavaScript Functions

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

Example
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}

Function parameters are listed inside the parentheses () in the function definition.

Function arguments are the values received by the function when it is invoked.

Inside the function, the arguments (the parameters) behave as local variables.

A Function is much the same as a Procedure or a Subroutine, in other programming languages.

Function Invocation
The code inside the function will execute when "something" invokes (calls) the function:

When an event occurs (when a user clicks a button)
When it is invoked (called) from JavaScript code
Automatically (self invoked)
You will learn a lot more about function invocation later in this tutorial.

Function Return
When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The return value is "returned" back to the "caller":

Example
Calculate the product of two numbers, and return the result:

var x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
The result in x will be:

12
Why Functions?
You can reuse code: Define the code once, and use it many times.

You can use the same code many times with different arguments, to produce different results.

Example
Convert Fahrenheit to Celsius:

function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77);
The () Operator Invokes the Function
Using the example above, toCelsius refers to the function object, and toCelsius() refers to the function result.

Accessing a function without () will return the function object instead of the function result.

Example
function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius;
Functions Used as Variable Values
Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.

Example
Instead of using a variable to store the return value of a function:

var x = toCelsius(77);
var text = "The temperature is " + x + " Celsius";
You can use the function directly, as a variable value:

var text = "The temperature is " + toCelsius(77) + " Celsius";

Local Variables
Variables declared within a JavaScript function, become LOCAL to the function.

Local variables can only be accessed from within the function.

Example
// code here can NOT use carName

function myFunction() {
  var carName = "Volvo";
  // code here CAN use carName
}

// code here can NOT use carName


