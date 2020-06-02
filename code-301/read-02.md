# jQuery, Events, and The Dom

## JQuery
* jQuery can select elements, perform tasks, and handle elements
* You find the element with CSS style selectors, ie `$(li.cold')`
* After that, you add the method to be done with what you select, `$('li.cold).addClass('water');`
* You need to start by adding the jQuery script to the page, like `<script src="js/jquery-1.11.0.js"></script>`
* jQuery is preferred because it uses simple selectors, can acheive common tasks with less code, and has cross-browser compatibility
* Use a comma to separate selectors when selecting multiple elements
* `previous + next` only selects elements immediately followed by the preceding element
* `previous ~ sibling` will select elements that are siblings of the previous element
* There are a lot of kinds of selectors, similar to CSS, but a lot more options (pg 302-3)
* Use `$('p').html()` to get an element, fill in the parens to set it
* You can add classes and such to many alements at once with `.addClass('class-here')` in a process known as __implicit iteration__
* When you have multiple methods on one element, you can put each new method on a new line for better readability
* Wrap your jQuert in `$(document).ready(function() {
  // script here
})`
* `.html()` returns everything in the html, and `.text()` just returns the text on the page
* `.text()` will only get the text, even if it is from mulitple elements 
* `.replaceWith` and `.remove()` are  options
* `.before()` and `.after()` insert around the element, and `.prepend` and `.append()` insert inside the element, at the beginning and end
* `.attr()` can get or set an attribute
* `.css()` can add css rules, including adding a new code block
* use `.each()` to run a function on every element that is selected, like a loop. The function goes in the parens
* You can refer to the current node with `this`
* You can add events with `.on('click', function)`
* There are a variety of jQuery effects you can use, such as `.toggle()` and `.fadeIn(0)`
* You should place your scripts right before `</body>`

## Pair Programming
* Pair programming helps students learn the language of coding
* Pair programming produces higher quality code tht requires less debugging
* Programmers are more focused when they work together
* Students learn from one another when they work together
* It improves social skills and helps students prepare for interviews
* This is a common industry practice, so it makes sense to work o n it at Code Fellows