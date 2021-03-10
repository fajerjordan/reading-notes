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


## Form struCturE

- <form>
Form controls live inside a 
<form> element. This element should always carry the action attribute and will usually have a method and id attribute too.

- action
Every <form> element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

- method
Forms can be sent using one of two methods: get or post.
With the get method, the values from the form are added to 
the end of the URL specified in the action attribute. 


# THE EVENT OBJECT

Every event handling function receives an event object.
It has methods and properties related to the event that occurred.

Just like the JavaScript event object, the jQuery event object has properties and methods that tell you more about the event that took place.
If you look at the function that is called when the event occurs,the event object is named in the parentheses. Like any other
parameter, this name is then used within the function to refer
 o the event object.