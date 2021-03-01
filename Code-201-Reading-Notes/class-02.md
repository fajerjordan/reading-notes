# Include JavaScript Code in HTML
Attribute Details
src Specifies the path to a JavaScript file. Either a relative or absolute URL.
type Specifies the MIME type. This attribute is required in HTML4, but optional in HTML5.
async
Specifies that the script shall be executed asynchronously (only for external scripts). This attribute
does not require any value (except of XHTML).
defer Specifies that the script shall be executed when the page has finished parsing (only for external
scripts). This attribute does not require any value (except of XHTML).
charset Specifies the character encoding used in an external script file, e.g. UTF-8
crossorigin How the element handles crossorigin requests
nonce Cryptographic nonce used in Content Security Policy checks CSP3
Section 13.1: Handling disabled Javascript
It is possible that the client browser does not support Javascript or have Javascript execution disabled, perhaps due
to security reasons. To be able to tell users that a script is supposed to execute in the page, the <noscript> tag can
be used. The content of <noscript> is displayed whenever Javascript is disabled for the current page.
<script>
 document.write("Hello, world!");
</script>
<noscript>This browser does not support Javascript.</noscript>

## Linking to an external JavaScript file
<script src="example.js"></script>
The src attribute works like the href attribute on anchors: you can either specify an absolute or relative URL. The
example above links to a file inside the same directory of the HTML document. This is typically added inside the
<head> tags at the top of the html document
Section 13.3: Directly including JavaScript code
Instead of linking to an external file, you can also include the JS code as-is in your HTML:
<script>
// JavaScript code
</script>
## Including a JavaScript file executing
asynchronously
<script type="text/javascript" src="URL" async></script>
  
  
## Using HTML with CSS
CSS provides styles to HTML elements on the page. Inline styling involves usage of the style attribute in tags, and is
highly discouraged. Internal stylesheets use the <style> tag and are used to declare rules for directed portions of
the page. External stylesheets may be used through a <link> tag which takes an external file of CSS and applies the
rules to the document. This topic covers usage of all three methods of attachment.
Section 14.1: External Stylesheet Use
Use the link attribute in the document's head:
<head>
 <link rel="stylesheet" type="text/css" href="stylesheet.css">
</head>
You can also use stylesheets provided from websites via a content delivery network, or CDN for short. (for example,
Bootstrap):
<head>
 <link rel="stylesheet"
href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-
BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
</head>
Generally, you can find CDN support for a framework on its website.
Section 14.2: Internal Stylesheet
You can also include CSS elements internally by using the <style> tag:
<head>
 <style type="text/css">
 body {
 background-color: gray;
 }
 </style>
</head>
Multiple internal stylesheets can be included in a program as well.
<head>
 <style type="text/css">
 body {
 background-color: gray;
 }
 </style>
 <style type="text/css">
 p {
 background-color: blue;
 }
 </style>
</head>
  
  
##   Inline Style
You can style a specific element by using the style attribute:
<span style="color: red">This text will appear in red.</span>
Note: Try to avoid this -- the point of CSS is to separate content from presentation.


## Multiple Stylesheets
It's possible to load multiple stylesheets:
<head>
 <link rel="stylesheet" type="text/css" href="general.css">
 <link rel="stylesheet" type="text/css" href="specific.css">
</head>
Note that later files and declarations will override earlier ones. So if general.css contains:
body {
 background-color: red;
}
and specific.css contains:
body {
 background-color: blue;
}
if both are used, the background of the document will be blue

##  Images
Parameters Details
src Specifies the URL of the image
srcset Images to use in different situations (e.g., high-resolution displays, small monitors, etc)
sizes Image sizes between breakpoints
crossorigin How the element handles crossorigin requests
usemap Name of image map to use
ismap Whether the image is a server-side image map
alt Alternative text that should be displayed if for some reason the image could not be displayed
width Specifies the width of the image (optional)
height Specifies the height of the image (optional)
 
 
 ## : Choosing alt text
Alt-text is used by screen readers for visually impaired users and by search engines. It's therefore important to
write good alt-text for your images.
The text should look correct even if you replace the image with its alt attribute. For example:
<!-- Incorrect -->
<img src="anonymous.png" alt="Anonymous user avatar"/> An anonymous user wrote:
<blockquote>Lorem ipsum dolor sed.</blockquote>
<a href="https://google.com/"><img src="edit.png" alt="Edit icon"/></a> /
<a href="https://google.com/"><img src="delete.png" alt="Delete icon"/></a>



