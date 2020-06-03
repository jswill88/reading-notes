# Mustache and Flex

## Templating with Mustache
* Mustache is a logic-less template syntax
* Put two braces around something to show it is a placeholder like `{{something}}`
* You need to install mustache, configure it in your JS file, create a views folder with HTML templates, then use `res.render(TEMPLATE_NAME, JSON_DATA)`

## A Guide to Flexbox
* The main axis is the primary axis which flex items are laid out
* Flex items start at the main-start and end at the main-end
* The cross axis is perpendicular to the main axis
* cross size is the width or height
* `display: flex` defines a flex container
* `order` can be applied to items in the flex box
* You can change the direction with `row`, `row-reverse`, `column`, `column-reverse`
* `flex-grow` applies to items in the box. If they are all 1, they will be the same size, but if one is `2` it will be twice as big
* `flex-wrap` will change the default of putting everything on one line
* `justify-content` has a lot of options for changing how each row is aligned
* `align-items` is like justify content, but on the other axis
* Set the parent to `display:flex` and the child to `margin:auto` for perfect centering
