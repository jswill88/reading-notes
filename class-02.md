# HTML Text, CSS Introduction, and Basic JavaScript Instructions

## Text
* There are six levels of headings `<h1>`(biggest) - `<h6>`(smallest)
* `<p>` for paragraphs
* Inline tags:
  * `<b>` for bold  
  * `<i>` for italic  
  * `<sup>` for superscript 
  * `<sub>` for subscript 
* **white space collapsing** - the browser will reduce more than one space or line breaks into one space
* `<br />` is line break
* `<hr />` is a horizontal rule, a break between topics. You can put it between paragraphs, and it puts a line across the screen
    * An example of an **empty element**
* **Semantic Markup** doesn't affect the structure of the page, but adds extra information to the pages
* `<strong>` is used to show important elements, defaults to bold
* `<em>` is used to emphasize certain elements, defaults to italics
* `<blockquote>` is for quotes that take up more than one line
* `<q>` is for quotes within a paragraph
* `<abbr>` can be used for an acronym
  * `<abbr title="Professor">Prof</abbr>`
* `<cite>` is used to reference a source, and is rendered in italics
* `<dfn>` is used to indicate the first time you define a word
* `<address>` contains the contact details for the page's author
* `<ins>` shows that content has been inserted and is underlined, and `<del>` shows that content has been removed and as a line through it.
* `<s>` - strikethrough

## Introducing CSS
* A CSS rule has a **selector**(element, such as `p`) and a **declaration** (eg `color: blue`)
* The first part of the declaration is the **property** and the second part is the **value**
* Use external CSS with `<link href="css/styles.css" type="text/css" rel="stylesheet" />` in the `<head>`
* Use internal CSS with the tag `<style type="text/css">`
* CSS Selectors:
  * `*` - Universal selector affects everything on the page
  * You can pick elements such as `h1` to modify. Select muliple by separating with a comma, like `h1, p, h3 {}`
  * class selectors start with a `.` followed by the class name. You can select only classes of certan types of elements with `p.class`
  * select ids with `#` followed by id name
  * `>` is a child selector. Use like this: `li>a` to change `a` elements that are direct children of `li`
  *  `p a {}` targets all descendants, not just direct children
  * `h1+p {}` only targets adjacent siblings. Just the first `p` after an `h1`
  * `h1~p {}` affects all `p`s in the `h1`
  * The last rule and the most specific rule take precedence in CSS, or you can use `!important` to overrule. `color: red !important;`

## Basic Javascript Instructions
* JS steps are known as a `statement` and end with a `;`
* JS comments are `/* comment */` for mulitple lines or `// comment` for one line
* A **variable keyword** is `var` so the interpreter knows that what's coming will be a variable `var name = 'hank';`
* after the keyword is the **variable name**
* `=` is the assignment operator
* `hank` is the variable value
* Data types include numbers, strings, and boolean(true/false)
* If you want single quotes in a string, you can surround the whole string with double quotes
* Alternately, you can use a `/` before each quote occurence. This technique is called **escaping**
* You can declare multiple variables on the same line, separated by commas `var dog, cat;` or `var big = 10, small = 1;`
* Variable names can have letters, numbers,  dollar signs, and underscores, but can't start with a number
* You can't use a keyword as a variable
* Varibale names are case sensitive
* An array stores a list of values `var bears = ['grizzly', 'polar', 'teddy'];`
* Access parts of the array by choosing the number of the value, starting at 0. To get `'polar'` is found with `bears[1]`. You can use this to change a value in the array, or assign that value to a different variable
* Find the length of an array with `bears.length`
* `%` **modulus** divides two numbers and provides the remainder
* Use this format to change something in HTML: `var change = document.getElementById('id'); change.textContent = newHtmlContent;`

## Decisions and Loops
* Use flowcharts to see how different scenarios will pan out
* `==` is equal to, `===` is strictly equal to where strings and numbers will be seen as not equal
* `!=` means not equal, and `!==` means strictly not equal. `3 != '3'` is false, `3 !== '3'` is true
* **operands** and **comparison operators** are in parentheses to create a **condition**
* An operand can be an expression if you put it in parentheses. `(dog + cat) >= 11;`
* `&&` is AND, `||` is OR, `!` is NOT. These are **logical operators** and can be used to compare multiple **comparison operators**
* An if statement runs if the conditions are met: `if (dog > 300) {doThis();}`
* Use `else` after an `if` to do something if the `if` condition is `false`
`if (dog > 300) {doThis();} else {doThat();}`

## How to Write a Git Commit Message
* Use consistent concise commit messages
* Commit messages should have consistent style, content, and metadata
> Seven rules of Git Commit:
> 1. Separate subject from body with a blank line
> 1. Limit the subject line to 50 characters
> 1. Capitalize the subject line
> 1. Do not end the subject line with a period
> 1. Use the imperative mood in the subject line
> 1. Wrap the body at 72 characters
> 1. Use the body to explain what and why vs. how
* Not all commits need a subject and a body
* If you can't summarize the changes in 50 characters, you may be doing too many changes for one commit
* **imperative mood** means the subject is written like a command, so if someone goes to that commit, they know what it will do
* Git does not auto wrap, so it needs to be done manually at 72 characters
* You don't need to write how you acheived something, because that can be seen in the code


