# HTML Tables; JS Constructor Functions

## Domain Modeling
* A model describes attributes and behaviors of different entities and constraints of a problem domain
* **Object Oriented** captures the behavior in methods and stores data
* Define a construtor like a function
```
var constructorEx = function(parameter) {
  this.parameter = parameter;
}
var exOne = new constructorEx(parameter);
```
* This is basic **object oriented programming**
* `new` creates a new object
* A prototype for a constructor function can be added, and is like a stunt double, so you can store the methods outside of the objects

## Tables
* `<table>` starts a table
* `<tr>`, `<td>`, and `<th>` are table row, table data, and table headings
* `<th>` can take the `scope` attribute of `col` or `row`
* You can make them blank if needed
* Use the attribute `colspan = 2` to make something spread across 2 columns ( can be any length)
* `rowspan =` for rows
*  `<thead>` is for the first row of a longer table, then `<tbody>` and `<tfoot>`
* Older code used inline style to set width, spacing, border, and background

## Methods and Objects
* You can create many objects with constructo notation
* It looks like a mix of a function and an object, where properties are passed through like parameters, and then defined with `this.parameter`
* You make a new object by declaring a new variable equal to the function, but fill in the parameters with property values
* Then you can access the values like in an object
* You add new parameters the same way as a regular object after it is declared
* `this` is a keyword to reference other parts of the object
* Arrays are a type of object
* There are built in objects in the browser
* Data Types are objects, and others include `Math`, `Date`, and `Regex`
* The window is an object, and there are a variety of ways to reference this, including `window.innerheight`
* You can use the **Document Object** to change the HTML
* There are methods with the **string object** such as `charAt()`
* An object is a **complex data type**
* There are number object methods, such as `isNaN()`

