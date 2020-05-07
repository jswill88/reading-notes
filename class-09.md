# More CSS Layout

## Layout
* Use `clear` with floating elements to make sure te right or left or both sides of a floating box won't appear next to other boxes, so it's more even. `clear: left`
* If a containing element only has floating elements, the container may appear 0px tall. Fix this with `overflow: auto`
* Mobile devices have higher resolutions than computer screens
* A browser window is about 1000px by 570px
* Fixed width layouts do not change as the user increases or decreases the size of the screen, whereas liquid layouts do
* Fixed width uses px and liquid uses %
* You can use min-width and max-width properties to help control a liquid layout
* A layout grid gives continuity between different pages, makes a site more predictable, makes it easy to add new content, and makes it easier for people to collaborate
* With a 12 column grid, there are many options for cleanly formatting the page
* Use a CSS Framework to create a grid based page
* You specify in the classes of the HTML the size of your box with classes such as `"css/960_12 clearfix"`
