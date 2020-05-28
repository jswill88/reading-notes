# Introductory HTML and Javascript

## Strucure
* HTML pages are text documents
* Characters inside `<>` are called **elements**  
  * They are made up of opening and closing **tags**
* Important tags:
  * `<html>` - tells you that everything in between is HTML code
  * `<body>` - contains what appears in the screen of the browser
  * `<h1>,<h2>,<p>` - heading, sub-heading, paragraph
* Attributes tell you more about the element, and they appear in the opening tag
  * For example `<p lang="en-us">`
  * `lang` is the attribute name, `en-us` is the attribute value
* `<head>` contains info about the page that isn't shown, such as the `title`
* `<title>` is shown in the top of the browser
* Use **View Source** in your browser to study how other sites are built

## Extra Markup
* Each webpage should begin `<!DOCTYPE html>` to show you that you are using HTML5
* Comment by surrounding text with `<!-- comments here -->`
* An **id** attribute must start with a letter or underscore, and is used to uniquely identify an element
  * eg. `<p id="pullquote">`
* A **class** identifies several elements
  * eg. `<p class="important">`
* Block elements always appear on a new line
  * `<p>, <h1>, <ul>, <li>` are block elements
* Inline elements stay on the same line
  * `<a>, <b>, <em>, <img>` are inline elements
* `<div>` allows you to group a set of elements together in one block level box
> "You can create CSS style rules
> to indicate how much space the
> `<div>` element should occupy 
>  on the screen and change the
> appearance of all the elements
> contained within it." - Duckett
* `<span>` is the inline equivalent of `<div>`
* `<iframe>` is a window to another site
  * You can add the attributes, width, height, src, and seamless(applied where no scrollbars are desired, no value needed)
* `<meta>` is in the `<head>` and contains info for searching for the page and other info that is hidden such as the page author
* **Escape characters** are used for characters that won't normally show up in HTML. Look up on pg. 193-4 when needed

## HTML5 Layout
* The `<header>` and `<footer>` are at the top and bottom of the page, respectively
  * The `<header>` can have the page's name, and the `<footer>` can have copyright info, for example
* `<nav>` is for the navigation bar
* `<article>` is for sections that could stand alone
* `<aside>` contains info related to the article, but not essential to its overall meaning
* `<section>` groups related content together
* `<hgroup>` stands for "heading group" and groups a heading and its sub-headings together
* `<figure>` contains content referenced in the main flow of the article, such as images, videos, graphs, diagrams, etc.
  * `<figcaption>` can be added in the `<fig>` element to add a caption to the figure
* `<div>` used for other sections that don't fit into any of the above
* You can use `<a>` around block level elements
* Extra JS is needed to make HTML5 elements work with IE8 and older

## Process and Design
* Consider the site's target demographic
* Think of visitor's **motivation** and **goals**, and how often they will visit
* Use grouping and similarity to share information clearly
#### Vocabulary
* Site map - shows how pages are grouped
* Card sorting - place info on separate papers and orgnize into groups
* Wireframe - a sketch of key info on each page of a site
* Visual hierarchy - draws atttention to key messages then guides to subsequent messages using size, color, and style
* Design Navigation Principles - Concise, clear, selective, context, interactive, consistent

## The ABC of Programming

* Writing a script
  1. Define the goal
  1. Design the script
  1. Code each step
* Use a flow chart to show how tasks will fit together.
* Flowchart key:
  * *Rectangle* - Generic Step
  * *Hexagpn* - Event
  * *Rhombus* - Input or Output
  * *Diamond* - Decision
* An **instance** is an occurence of an **object**. 
* **Properties** are characteristics of an object, and they consist of a **name** and a **value**
* An **event** is when something happens, such as a user clicks on something. The programmer can choose what events will cause something else to happen
* A **method** is what is done with an object.
  * It can change a value in an object, or tell you something about the object
* How the browser sees a web page   
  1. Receives the page as HTML code
  1. Stores a model of the page in memory
  1. Uses a rendering engine to show the page on the screen using default HTML style, or what is specified in the CSS
  1. They translate the JS instructions into something the computer understands with an **interpreter**
* Each language forms a different layer
  * `HTML` is the content layer
  * `CSS` is the
  * `JS` is the behavior layer
  * They build upon one another with **progressive enhancement**
* You can use `document.write()` to add something into HTMl
* Link to JS file from HTML with `<script src="name-of-js-file"></script>`
* You can also put JS straight into the HTML page by putting JS code betwween `<script>` tags
* In the example `document.write('Good afternoon!');`
  * `document` is the **object**
  * `.` is the member **operator**
  * `write()` is the **method**
  * `'Good afternoon!'` is the **parameter** 
