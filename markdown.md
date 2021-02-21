**In this page i will talk to  you about Markdown**

Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

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
  3. To order your list, precede each line with a number.
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
  @octocat :+1: This PR looks great - it's ready to merge! :shipit:
