# Classes, Inheritance, Functional Programming

__Name 3 advantages to Test Driven Development__  
1. The methodical approach leads to fewer bugs. 
1. In the long run, you will write better code, and it will save you time
1. It makes it easier to refactor, because you have tests that will show you if the new code is still working.  
https://medium.com/javascript-scene/tdd-changed-my-life-5af0ce099f80

__In what case would you need to use `beforeEach()` or `afterEach()` in a test suite?__  
Use these when you need to run many tests, and they can handle testing asynchronous code.
https://jestjs.io/docs/en/setup-teardown

__What is one downside of Test Driven Development__  
This approach can be slower, so it may not be best for short and fast projects that do not need a lot of upkeep.  
http://www.letscodejavascript.com/

__What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?__  
Classes can contain methods within the declaration, and classes can have children that inhererit certain properties. These make classes easier to organize.  
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes


__Name a use case for a static method__  
They are used to create utility functions.  
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes  

__Write an example of a Higher Order function and describe the use case it solves__
```javascript
function equateNums(x, y, equate) {
  return equate(x, y);
}
```
This could be used to run different operations on two numbers, depending on what function you pass through the `equate` parameter.


## Vocabulary Terms  
  
|Term | Definition |  
|---|---| 
|functional programming | Functional programming uses pure functions and higher order functions. The functions will be used as data. It maintains an immutable state.  https://www.freecodecamp.org/news/functional-programming-principles-in-javascript-1b8fc6c3563f/ |
|pure function | A pure function will always give the same result if it is given the same arguments. It will not have any side-effects. It will not change over time. https://www.freecodecamp.org/news/functional-programming-principles-in-javascript-1b8fc6c3563f/|
|higher-order function | Takes at least one function as an argument or returns a function as a result. https://www.freecodecamp.org/news/functional-programming-principles-in-javascript-1b8fc6c3563f/ |
|immutable state | Data with an immutable state cannot be changed after it is created. https://www.freecodecamp.org/news/functional-programming-principles-in-javascript-1b8fc6c3563f/|
|object | A type of data that stores key value pairs. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object|
|object-oriented programming (OOP) | The four principles of OOP are encapsulation, abstraction, inheritance, and polymorphism. Objects should keep their state private. Objects should have a high level mechanism for using them. Use inheritance to give similar classes shared properties. https://www.freecodecamp.org/news/object-oriented-programming-concepts-21bb035f7260/ |
|class | Templates for creating objects. They organize data and functions, and they are built on prototypes. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes|
|prototype| A prototype is a property of an object. When you write a prototype for an object, it is adding a new property to the prototype object. There is a chain of prototypes linking objects together until it reaches `null`. `new` is an example of something that extends the prototype chain. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain|
|`super`| This is used to call parent classes, and use the same data and prototypes. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes |
|inheritance | A way to describe how properties can be shared between objects or classes. Children inherit from parents. https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Inheritance|
|constructor | A method to create and initialize an object in a class. There can only be one constructor in a class. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes |
|instance | Instances are the objects that are created with a constructor or from a class. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Details_of_the_Object_Model |
|context| What the value of `this` is in your code. This changes based on where you are in your code and what the scope is. You can change the context with `call`. https://www.youtube.com/watch?v=fjJoX9F_F5g |
|`this` | Refers to the scope in which `this` appears. Outside of a in the global scope it refers to the window object, and in a function or object, it refers to that object. With jQuery, this becomes the element that was clicked. You can use `bind` to use `this` to reference a higher scope if needed. https://www.youtube.com/watch?v=fjJoX9F_F5g  |
|Test Driven Development (TDD)| Used to ensure that code is consistent and does what it is expected to do. You accomplish this by running tests on your code, and by running the production code. The results should match. http://www.letscodejavascript.com/ |
|Jest | A library that can be used to write and run tests on your code. You can run the tests from the command line. https://jestjs.io/docs/en/getting-started|
|Continuous Integration | With this, developers will often make updates to the code which are then tested. The goal is to find bugs quicker and to produce software faster. https://aws.amazon.com/devops/continuous-integration/|
|unit test | The part of testing where individaul components are tested, to make sure each unit of the software works as expected. http://softwaretestingfundamentals.com/unit-testing/#:~:text=UNIT%20TESTING%20is%20a%20level,and%20usually%20a%20single%20output. |
