# Read: 09 - Forms and Events

# Forms

## There are several types of form controls that you can use to collect information from visitors to your site:

* ADDInG tEXt:
Text input (single-line) Used for a single line of text such as email addresses and names.

* Password input
Like a single line text box but it masks the characters entered.

* Text area (multi-line) For longer areas of text, such as messages and comments.

* mAkInG ChoICEs:
Radio buttons
For use when a user must select one of a number of options.

* Checkboxes
When a user can select and unselect one or more options.

* Drop-down boxes 
When a user must pick one of a number of options from a list.

* submIttInG Forms:
Submit buttons
To submit data from your form to another web page.

* Image buttons
Similar to submit buttons but they allow you to use an image.

* uploADInG FIlEs:
File upload
Allows users to upload files (e.g. images) to a website.

## hoW Forms Work:

1- A user fills in a form and then presses a button to submit the information to the server.

2- The name of each form control is sent to the server along with the value the user enters or selects.

3- The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.

4- The server creates a new page to send back to the browser based on the information received.

## A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.


# THE EVENT OBJECT

## Events are actions or occurrences that happen in the system you are programming, which the system tells you about so you can respond to them in some way if desired. For example, if the user selects a button on a webpage, you might want to respond to that action by displaying an information box. In this article, we discuss some important concepts surrounding events, and look at how they work in browsers. This won't be an exhaustive study; just what you need to know at this stage.

* Prerequisites:	Basic computer literacy, a basic understanding of HTML and CSS, JavaScript first steps.
* Objective:	To understand the fundamental theory of events, how they work in browsers, and how events may differ in different programming environments.

## In the case of the Web, events are fired inside the browser window, and tend to be attached to a specific item that resides in it — this might be a single element, set of elements, the HTML document loaded in the current tab, or the entire browser window. There are many different types of events that can occur. For example:

## The user selects a certain element or hovers the cursor over a certain element.
The user chooses a key on the keyboard.
The user resizes or closes the browser window.
A web page finishes loading.
A form is submitted.
A video is played, paused, or finishes.
An error occurs.
You can gather from this (and from glancing at the MDN Event reference) that there are a lot of events that can be responded to.

## Each available event has an event handler, which is a block of code (usually a JavaScript function that you as a programmer create) that runs when the event fires. When such a block of code is defined to run in response to an event, we say we are registering an event handler. Note: Event handlers are sometimes called event listeners — they are pretty much interchangeable for our purposes, although strictly speaking, they work together. The listener listens out for the event happening, and the handler is the code that is run in response to it happening.

***Note: Web events are not part of the core JavaScript language — they are defined as part of the APIs built into the browser***





 
 
 
