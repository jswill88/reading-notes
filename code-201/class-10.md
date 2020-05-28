# JS Debugging

## Error Handling and Debugging - Chapter 10
* Think about the execution context when debugging, and the variable scope
* When you call a function in JS, it works on that code befre returning to the code that called the function
* Eveything in the same context can seemingly work simultaneously. A function or variable can be assigned before it is declared
* Functions can take in vairiables from parents, but can not send them back
* An error object has a `name`, a `message`, a `fileNumber`, and a `lineNuumber`
* a `SyntaxError` is usually a result of a small typo
* A `ReferenceError` is caused when a variable does not exist, or is in the wrong scope
* An `EvalError` comes from an improper use of the `eval()` function
* A `URI Error` is cause when a character is not escaped
* A `TypeError` is when the value is an unexpected data type
* A `RangeError` is when something is out of range, such as a negative array number
* An `Error` is a generic error
* Use breakpoints where things are going wrong to pause execution to inspect data in the variables
* Call functions in the console to check if they are returning the values you expect them to
* Check the number of parameters in a function, or items in an array
* If an error stops the JS in Chrome, it will only show one error, but there may be more
* The no entry sign in Chrome is used to clear the console
* Remove consloe logs from your code before you put in on a live site
* Tere are some other console methods:
  * `console.info()` can be used for general information
  * `console.warn` will tell you what was entered
  *  `console.error` can be used to hold errors
* You can check a group of info in the console log with `console.group()` and `console.groupend()` 
* On some browsers, `console.table()` can give you a table of objects or an array that contains other arrays or objects
* With `console.assert()` you can test to see if a condition has been met
* To set up a breakpoint in Chrome, go to the **Sources** option, and click on the line number you want to stop on
* Then you are allowed to go through the code step by step to see where there is a problem
* You can add a conditional breakpoint using existing variables
* You can just add the word `debugger;` to your code to set up a breakpoint. This can be in a conditional statement
* If you think your code might fail, you can use `try` `catch` `finally` 
```
try {
  // Try to execute this code
} catch (exception) {
  // if there is an exception, run this code
} finally {
  // This always gets executed
}
```
* This will allow the code to still be executed in case there is an  error
* Create your own error with `throw new Error('message');
* `www.jslint.com` is a validation tool you can use