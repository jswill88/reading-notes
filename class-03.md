# HTML Lists, CSS Boxes, JS Control Flow

## Lists
* **Definition Lists** are made up of a set of terms, along with their definition
* `<dl>` is for the list, `<dt>` is for the term being defined, and `<dd>`is for the definition of the term
* **Nested lists** are lists inside of lists
* **Ordered lists** are numbered and use the tag `<ol>`
* **Unordered Lists** are not numbered and use the tag `<ul>`
* The list items for each use `<li>` tags

## Boxes
* With CSS you can set the width and height, like this: `width: 40px;`
* You can also use percentages for this. The box will be that percent of the window, or of a containing box
* if you use `ems` it will be based on the size of the text inside the box
* To make sure a box is limited in size when you change the screen size, you can use `min-width` and `max-width`
* You can do the same with `min-height` and `max-height`
* `overflow` tells what to do when content exceeds the size of the box. There are two options:
  * `hidden` will hide what doesn't fit in the box
  * `scroll` will allow the user to scroll to the missing content
* The **margin** is the space between boxes, and the **padding** is the space between the box's border and its content
* You can make `border-width` `thin`, `medium`, or `thick`, or use px.
* There are a variety of `border-styles`
  * `dotted`
  * `dashed`
  * `double`
  * `groove`
  * `ridge`
  * `inset`
  * `outset`
  * `hidden`/`none`
* `border-color` is self explanatory
* Shorthand: `border: 3px`(width) `dotted` (style) `blue` (color);
* If `width` is specified, `padding` and `width` add on to that
* Set `left-margin` and `right-margin` to auto to center a box
* There are many `display` options
  * `inline` makse block elements act line inline elements
  * `block` makes inline elements block elements
  * `inline-block` flows like an inline element, but has other block level features
  * `none` hides the element
* `visibility` can be `hidden` or `visible`
* `border-image` can turn an image into a border
  * The parameters are the URL, where to slice the image (4 numbers), and whether the straight edges are `stretch`, `repeat`, or `round`
* `box-shadow` parameters (needs 1st 2):
  * horizontal offset: negative is left
  * vertical offset: negative is right
  * blur distance: how far the blur goes
  * spread of shadow: spreads the shadow in all directions
  * `inset` keyword can be added to the beginning to make an inward shadow
* `border-radius` can be used to make complex shapes

## Decisins and Loops
* A `switch` statement can provide more options quickly than an if else statement
* Book example:
> switch (level) {
>
>  case 'One':  
>  title = 'Level 1';  
>  break;  
>
> case 'Two';  
> title = 'Level 2';  
> break;  
>
> case 'Three';  
> title = 'Level 3';  
> break;
> 
> default:  
> title = 'Test';  
> break;
> }
* The cases don't need quotes if they are not strings
* If you are not careful, JS will change the type of variable you are using to make sense of it, with **type coersion**
* **Falsy** values include `false`, `0`, an empty string, `NaN`, and a variable with no value, and are treated as `false`. These aren't the same values with `===`
  * `undefined` and `null` are only equal to themselves, `NaN` is not even equal to itself
* **Truthy** values include `true`, numbers other than 0, unempty strings, number calculations, `'true'`, `'0'`, `'false'`
  * You can use this to check if something is in your page
* Logical operators stop as soon as they have a result
* A `for` statement looks like `for (var i = 0; i < 10; i++) {}`
* `for` is the keyword, `var i` is the initialization, `i<10` is the condition, and `i++` is the update
* `break` causes the lopp to end
* `continue` stops the iteration to update and check again
* `while` loops run until the condition is met. `while (i<5){}`
* `do while` always goes through the loop at least once `do {} while ();`


