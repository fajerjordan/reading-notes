
# HTML Layout Elements
### HTML has several semantic elements that define the different parts of a web page:
  - <header> - Defines a header for a document or a section
  - <nav> - Defines a set of navigation links
  - <section> - Defines a section in a document
  - <article> - Defines an independent, self-contained content
  - <aside> - Defines content aside from the content (like a sidebar)
  - <footer> - Defines a footer for a document or a section
  - <details> - Defines additional details that the user can open and close on demand
  - <summary> - Defines a heading for the <details> element

  
  ## What are Semantic Elements?
### A semantic element clearly describes its meaning to both the browser and the developer.

### Examples of non-semantic elements: <div> and <span> - Tells nothing about its content.

### Examples of semantic elements: <form>, <table>, and <article> - Clearly defines its content.

## Semantic Elements in HTML

### Many web sites contain HTML code like: <div id="nav"> <div class="header"> <div id="footer"> to indicate navigation, header, and footer.

### In HTML there are some semantic elements that can be used to define different parts of a web page:  
  <article>
  <aside>
  <details>
  <figcaption>
  <figure>
  <footer>
  <header>
  <main>
  <mark>
  <nav>
  <section>
  <summary>
  <time>  

# HTML Layout Techniques
### There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:

  - CSS framework
  - CSS float property
  - CSS flexbox
  - CSS grid
  
## HTML Layout Techniques

***There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:***


- CSS framework
- CSS float property
- CSS flexbox
- CSS grid

## CSS Frameworks
If you want to create your layout fast, you can use a CSS framework, like W3.CSS or Bootstrap:

## CSS Float Layout
It is common to do entire web layouts using the CSS float property. Float is easy to learn - you just need to remember how the float and clear properties work. Disadvantages: Floating elements are tied to the document flow, which may harm the flexibility. Learn more about float in our CSS Float and Clear chapter.

## CSS Flexbox Layout
Use of flexbox ensures that elements behave predictably when the page layout must accommodate different screen sizes and different display devices.

## CSS Grid Layout
The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

## What CSS does
### CSS Associates Style rules with HTML elements

## How CSS works
### CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.

## Rules, properties, and values
### This rule indicates that all <p> elements should be shown in the Arial typeface.

### Selectors indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names
with commas.

### Declarations indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon.

**Markdown** is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

_And here's an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files:_

1. To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the size of the heading:
  # This is an h1 tag
  ## This is an h2 tag
  ###### This is an h6 tag

2. You can indicate emphasis with bold, italic, or strikethrough text:
  * Bold , by using	** ** or __ __	, ex: **This is bold text**	
  * Italic, by using	* * or _ _	, ex: 	*This text is italicized*
  * Strikethrough, by using	~~ ~~	, ex: 	~~This was mistaken text~~	
  * Bold and nested italic, by using	** ** and _ _	, ex:	**This text is _extremely_ important**
  * All bold and italic , by using	*** ***	, ex:	***All this text is important***	
  
3. You can quote text with a >.
  In the words of Abraham Lincoln:
  > Pardon my French
  
4. You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted.
  Use `git status` to list all new or modified files that haven't yet been committed.
  
5. To format code or text into its own distinct block, use triple backticks.
    Some basic Git commands are:
    ```
    git status
    git add
    git commit
    ```
6. You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ). You can also use the keyboard shortcut command + k to create a link.
  This site was built using [GitHub Pages](https://pages.github.com/).
  
7. You can make an unordered list by preceding one or more lines of text with - or *.
  - George Washington
  - John Adams
  - Thomas Jefferson


8. To order your list, precede each line with a number.

  1. James Madison
  2. John Quincy Adams
  3. James Monroe

  
9. You can create a nested list by indenting one or more list items below another item.
  1. First list item
   - First nested list item
     - Second nested list item
  
10. To create a task list, preface list items with a regular space character followed by [ ]. To mark a task as complete, use [x].
  - [x] Finish my changes
  - [ ] Push my commits to GitHub
  - [ ] Open a pull request 

11. You can mention a person or team on GitHub by typing @ plus their username or team name. 
  @github/support What do you think about these updates?
  
12. You can create a new paragraph by leaving a blank line between lines of text.

13. You can tell GitHub to ignore (or escape) Markdown formatting by using \ before the Markdown character.
 
 Let's rename \*our-new-project\* to \*our-old-project\*.
  
14. You can add emoji to your writing by typing :EMOJICODE:.
  @octocat :+1: This PR looks great - it's ready to merge! 
  
  
  # JavaScript layers

## Web developers usually talk about three languages that are used to create web pages: HTML, CSS, and JavaScript.
Where possible, aim to keep the three languages in separate files, with the HTML page linking to CSS and JavaScript files.
Each language forms a separate layer with a different purpose. Each layer, from left to right. builds on the previous one.
HTML layer. This is where the content of the page lives. The HTML gives the page structure and adds semantics.

#CSS layer
The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.).

#Javascript layer
## This is where we can change how the page behaves, adding interact ivity. We will aim to keep as much of our JavaScript as possible in separate files.

## Keeping it separate means that the page still works if the user cannot load or run the JavaScript. You can also reuse the code on severa l pages (making the site faster to load and easier to maintain).

# What is JavaScript?
JavaScript was initially created to “make web pages alive”.

The programs in this language are called scripts. They can be written right in a web page’s HTML and run automatically as the page loads.

Scripts are provided and executed as plain text. They don’t need special preparation or compilation to run.

In this aspect, JavaScript is very different from another language called Java.

## Why is it called JavaScript?
When JavaScript was created, it initially had another name: “LiveScript”. But Java was very popular at that time, so it was decided that positioning a new language as a “younger brother” of Java would help.

But as it evolved, JavaScript became a fully independent language with its own specification called ECMAScript, and now it has no relation to Java at all.

Today, JavaScript can execute not only in the browser, but also on the server, or actually on any device that has a special program called the JavaScript engine.

The browser has an embedded engine sometimes called a “JavaScript virtual machine”.

Different engines have different “codenames”. For example:

V8 – in Chrome and Opera.
SpiderMonkey – in Firefox.
…There are other codenames like “Chakra” for IE, “ChakraCore” for Microsoft Edge, “Nitro” and “SquirrelFish” for Safari, etc.
The terms above are good to remember because they are used in developer articles on the internet. We’ll use them too. For instance, if “a feature X is supported by V8”, then it probably works in Chrome and Opera.

## How do engines work?
Engines are complicated. But the basics are easy.

The engine (embedded if it’s a browser) reads (“parses”) the script.
Then it converts (“compiles”) the script to the machine language.
And then the machine code runs, pretty fast.
The engine applies optimizations at each step of the process. It even watches the compiled script as it runs, analyzes the data that flows through it, and further optimizes the machine code based on that knowledge.

What can in-browser JavaScript do?
Modern JavaScript is a “safe” programming language. It does not provide low-level access to memory or CPU, because it was initially created for browsers which do not require it.

JavaScript’s capabilities greatly depend on the environment it’s running in. For instance, Node.js supports functions that allow JavaScript to read/write arbitrary files, perform network requests, etc.

In-browser JavaScript can do everything related to webpage manipulation, interaction with the user, and the webserver.

For instance, in-browser JavaScript is able to:

Add new HTML to the page, change the existing content, modify styles.
React to user actions, run on mouse clicks, pointer movements, key presses.
Send requests over the network to remote servers, download and upload files (so-called AJAX and COMET technologies).
Get and set cookies, ask questions to the visitor, show messages.
Remember the data on the client-side (“local storage”).
What CAN’T in-browser JavaScript do?
JavaScript’s abilities in the browser are limited for the sake of the user’s safety. The aim is to prevent an evil webpage from accessing private information or harming the user’s data.

Examples of such restrictions include:

JavaScript on a webpage may not read/write arbitrary files on the hard disk, copy them or execute programs. It has no direct access to OS functions.

Modern browsers allow it to work with files, but the access is limited and only provided if the user does certain actions, like “dropping” a file into a browser window or selecting it via an <input> tag.

There are ways to interact with camera/microphone and other devices, but they require a user’s explicit permission. So a JavaScript-enabled page may not sneakily enable a web-camera, observe the surroundings and send the information to the NSA.

Different tabs/windows generally do not know about each other. Sometimes they do, for example when one window uses JavaScript to open the other one. But even in this case, JavaScript from one page may not access the other if they come from different sites (from a different domain, protocol or port).

This is called the “Same Origin Policy”. To work around that, both pages must agree for data exchange and contain a special JavaScript code that handles it. We’ll cover that in the tutorial.

This limitation is, again, for the user’s safety. A page from http://anysite.com which a user has opened must not be able to access another browser tab with the URL http://gmail.com and steal information from there.

JavaScript can easily communicate over the net to the server where the current page came from. But its ability to receive data from other sites/domains is crippled. Though possible, it requires explicit agreement (expressed in HTTP headers) from the remote side. Once again, that’s a safety limitation.


Such limits do not exist if JavaScript is used outside of the browser, for example on a server. Modern browsers also allow plugin/extensions which may ask for extended permissions.

What makes JavaScript unique?
There are at least three great things about JavaScript:

Full integration with HTML/CSS.
Simple things are done simply.
Support by all major browsers and enabled by default.
JavaScript is the only browser technology that combines these three things.

That’s what makes JavaScript unique. That’s why it’s the most widespread tool for creating browser interfaces.

## That said, JavaScript also allows to create servers, mobile applications, etc.

## Languages “over” JavaScript
The syntax of JavaScript does not suit everyone’s needs. Different people want different features.

## That’s to be expected, because projects and requirements are different for everyone.

## So recently a plethora of new languages appeared, which are transpiled (converted) to JavaScript before they run in the browser.

## Modern tools make the transpilation very fast and transparent, actually allowing developers to code in another language and auto-converting it “under the hood”.

## Examples of such languages:

## CoffeeScript is a “syntactic sugar” for JavaScript. It introduces shorter syntax, allowing us to write clearer and more precise code. Usually, Ruby devs like it.
## TypeScript is concentrated on adding “strict data typing” to simplify the development and support of complex systems. It is developed by Microsoft.
Flow also adds data typing, but in a different way. Developed by Facebook.
Dart is a standalone language that has its own engine that runs in non-browser environments (like mobile apps), but also can be transpiled to JavaScript. Developed by Google.
Brython is a Python transpiler to JavaScript that enables the writing of applications in pure Python without JavaScript.
Kotlin is a modern, concise and safe programming language that can target the browser or Node.
There are more. Of course, even if we use one of transpiled languages, we should also know JavaScript to really understand what we’re doing.

## Summary
JavaScript was initially created as a browser-only language, but it is now used in many other environments as well.
Today, JavaScript has a unique position as the most widely-adopted browser language with full integration in HTML/CSS.
There are many languages that get “transpiled” to JavaScript and provide certain features. It is recommended to take a look at them, at least briefly, after mastering JavaScript.


#################################################################################################################################################################################################################### [Homepage](https://majida-hatamleh.github.io/reading-notes.html)

