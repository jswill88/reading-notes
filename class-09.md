# Forms and Events

## Forms
* Forms have `action` and `method` attributes
* `action` is the URL where the info on the form is submitted
* `method` can be `get` or `post`
* Text input has a self closing tag `<input>` with attributes of `size`, `type=text`, `name`, and `maxlength`
* Type will be `password` for password input
* `<textarea>` is longer, and you specify the `cols`, `rows`, and `name`. It is not self closing, and you can put sample text in the textarea
* With `type="radio"` you choose one out of a few options. You make a new input for each option, all with the same `name` attribute. `value` is the value sent back, and you write the name of the selection after the tag. You can set a `checked` attribute to `"checked"` to start with one option selected
* `<checkbox>` is like radio, but a checkbox
* A drop down list is surrounded by `<select>` tags. Inside you put an `option` tag for each option, with an attribute of the sent back value. To make this a multiselect, set the `mulitple` attribute to `"mulitple"` in the `<select>` tag
* For an image button, set the `input` type to `image` and the `src` of the image
* An optional attribute is `image`
* Surround the input form with `<label>` tags to give a label to the form
* Group form elements with `<fieldset>`
* Set the attribute `required` to `"required"` to make something required
* Some options are  `type="date"`, `type="email"`, `type="url"`, `type="search"`
* Use attribute `placeholder` to put in a placeholder

## Lists, Tables, and Forms
* You can make a list style with an image in css: `list-style-image: url();`
* You can set even or odd rows in css with `tr.even:` (set the class in the `<tr>`s)
* You can hide empty cells with `empty-cells: hide;`
* use `border-spacing` to add separation between elements in the table. Add this to `table`
* `:focus` can change the background color of a part of form you are looking at
* Add `<div>` to forms to make them easier to apply css to
* check out www.chrispederick.com/work/web-developer

## Events
* There are many event types that can trigger a function or script in Javascript
* Select the element that should respond, indicate the event that will trigger, and then specify the code to run when that happens
* Use dom `element.onEvent = functionName; No parentheses on function name
* Event listeners handle more than one function at a time
* set a variable to a node, then `variable.addEventListener(event,functionName,Boolean);`
* To pass an argument, replace `functionName` with `function() { functionName(argument)}`
* The event object tells you info about the event
* Some event triggers are `load`, `unload`, `error`, `resize`, and `scroll`
* There are many **mouse events** and **keyboard** events


