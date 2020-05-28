# Docs for the HTML `<canvas>`, Element, & Chart.js

## Create Animated Charts with Chart.js
* Chart.js is a Javascript plugin that uses HTML to draw a chart onto the page
* Link to the plugin like you would normally link a js page
* Use `<canvas>` in the body of the HTMl page to place a graph
* You can easily make bar, line, and pi charts using HTML and JS with Charts.js 

## Chart.js
* You just need a single `<chart>` node in Chart.js to render the chart
* You put the type, data, color, etc into the Javascript

## Basic Uses
* The `<canvas>` element only has two attributes: width and height
* CSS does not affect the drawing of the chart, though you can add a border and other CSS
* You can provide fallback content within the tags in case the browser doesn't support the chart, such as a description, or an image of a static version of the chart
* The chart must be rendered in JS, and it starts with something like this: 
```
var canvas = document.getElementById('tutorial');
var ctx = canvas.getContent('2d');
```
* Make a function including the above, and have it run when the page loads, or when you want it to be called

## Drawing Shapes
* The canvas grid is known as the **coordinate space**
* Elements are placed in relative to the origin, using (x,y)
* You can draw a rectangle using `fillRect(x,y,width,height)` or `strokeRect()` or `clearRect()`
* `ctx.fillRect(x,y,width,height)`
* You can draw using paths, which are a list of points connected by segments of lines
* You do this by creating the path, drawing the path, and then stroking or filling tht path to render it
* Start with `ctx.beginPath();` then use `ctx.moveTo(x,y)`, then `.lineTo(x.y)` to put dots on the grid to make the shape. Then `.fill()` to finish
* When you finish with `.stoke` you get an unfilled shape. First use `.closePath()` to make sure the whole shape is there with `.stoke`
* use `.arc` or `.arcTo` for curves. Specify radius and degrees in these

## Applying Styles and Colors
* You can apply colors to a shpe with `fillStyle` and `strokeStyle`
* Set those to a color
* Use for loops through `rbg` to make multicolored shapes for your page
* Use the alpha to to change transparency
* Change the endpoints of lines with `lineCap`. Make it `butt`, `round` or `square`
* Overall, there are many options to study to create complex shapes and colors with Chart.js

## Drawing Text
* You can use `fillText()` or `strokeText()`
* The main parameters for each are the text to print, the x, and the y. You can also add the width
* You can style the text with `font`, `textAlign`, `textBaseline`, and `direction`
