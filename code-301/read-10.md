# The Call Stack

## MDN Call Stack
* The call stack is how the JavaScript interpreter keeps track of where it is when it has to call multiple functions
* If a stack takes up more space than it had assigned to it, it results in a stack overflow error
* We start with an empty stack, and add to it it whenever a function is called

## Understanding the JavaScript Call Stack
* The JavaScript engine is comprised of a heap and a single call stack
* The call stack uses the Last In, First Out priciple (LIFO)
* When a function is called, it is temporarily in the stack
* When a function calls another function, the function it calls goes to the top of the stack
* Stack overflow happens when a function calls itself without an exit point
* JavaScript can only do one thing at a time, the code is synchronous, and a function invocation creates a stack frame

## JavaScript Error Messages
* __Reference errors__ happen when you use a variable that has not been declared yet
* __Syntax errors__ occur when you use syntax that cannot be read by the interpreter
* __Range errors__ occur when you try to manipulate an object with an invalid length
* __Type errors__ occur when you use the wrong value type for a variable
* The easiest way to debug is with console.log
* You can add a conditional breakpoint by right clicking on a breakpoint line in the chrome dev tools
* "quokka" is a tool that can help catch errors as you type in JavaScript



