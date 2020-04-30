# HTML Links, CSS Layout, JS Functions
## Links
* Links have an `<a>` tag with an `href=""` attribute
* When linking to other sites, use the full URL
* When linking to other parts of the page, you can use the relative URL, such as `fun.html`. Follow the file path from the folder you are in
* The top level folder is known as the **root** folder
* The homepage is `index.html`
* When linking to something in a **child** folder, use `"child-folder.filename.html"`
* Add one more parent for linking to grandchildren folders
* To go back home from a child use `"../index.html"`, and use `..` twice when going home from a granchild folder
* For email, use `mailto:` folloed by the email address
* To open a link in a new window, add a second attribute to `a`: `target=_blank`
* To link to a different part of the same page `href="#id"`
* Add that to the end of a URL to link to a specific part of another page: `href="http://www.site.com/#id`

## Layout
* **Block level** elements start on new lines
* **Inline elements** flow between text.
* **Normal flow** - boxes sit on top of one another
  * `position: static`
* **Containing** elements have block level elements in them
* **Relative position** moves an element from its  normal flow
  * Use `left`, `right`, `top`, `bottom` to offset the box
* **Absolute** position is positioned in relation to it's containing element, and is taken out of the regular flow
* **Fixed position** is like absolute, but in relation to the browser window
  * If a user scrolls, the `fixed` bow will stay in the same place
* **floating elements** are pushed to the right or left of their container and text can flow around them
  * Can put boxes next to each other using `float`
* `clear: left` makes sure the sides of boxes don't touch, so new rows are created (see page 372)
* Parents of only `float` objects need `overflow: auto`  and `width: 100%` so the container is not treated as 0px tall
* Make multi-column layouts with `float`, `width`, and `margin`
* web designers usually design for 960-1000px wide
* **Fixed width** layouts does not change size based on the size of the browser window
*  **Liquid** layouts stretch and contract based on the size of the browser window
* Layout Grids are used to cleanly organize elements
* The **960 Grid System** `www.960.gs` provides a style sheet you can add to a document to create column layouts
* You can put multiple stylesheets into one by linking them in your CSS: `@import url("tables.css");`
* Or you can link multiple stylesheets in your HTML `<head>`

## Functions, Methods, and Objects  
* Make a function with `function theName() {}`, then call it with `theName()`
* `function` is a keyword, and in the above example, `theName()` is the function name
* If you need to send variables into the function, you put them in the `()` separated by commas. When you declare the function, these are called parameters
* The values you put through the function are called arguments
* You can get multiple values out of a function using an array
* If you put a function where an expression is expected, then the function will be treated as an expression, and the variable it is assigned to will take on the properties of the function

## Pair Programming
* There are two roles in pair programming: the **Driver** who codes and the **Navigator** who helps and thinks more about the big picture
* Pair programming is useful for learning, because it involves listening, speaking, reading, and writing
* Pair programming takes a little longer, but produces more polished code, so it requires less debugging
* It is a more engaging experience and helps programmers focus
* At Code Fellows this helps students develop interpersonal skills, and makse students more job-ready

