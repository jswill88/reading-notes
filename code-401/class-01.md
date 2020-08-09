# Node Ecosystem, TDD, CI/CD
1. Why would you want to run JavaScript code outside of a browser?  
This allows you to uild your own server so you can move information around just using JavaScript and build a more complex application. I believe that using your own server also helps with browser compatibility issues because you are not relying on the browser to run your code.
2. What is the difference between a module and a package?  
A module is not required to have a `package.json` file. A module with this file is also a package. A package can consist of multiple modules
3. What does the node package manager do?  
 - Brings packages of code into your app
 - Allows you to download standalone tools
 - Allows you to share code with other npm users
 - Allows you to restrict code to specific developers
 - Can create Orgs
 - Can manage multiple versions of code
 - Can update applications easily
 - Can help you find other developers doing similar work
4. Provide code snippets showing 3 different ways to export a function from a node module.  
    - ```javascript
      module.exports = thisIsTheFunction;
      ```
    - ```javascript
      exports = function(x) {
        return x + 1;
      }
      ```
      (`exports` is shorthand for `module.exports`)
    - ```javascript
      module.exports = {
        addFive: function(x) { return x + 5 },
        getAvg: function(x,y) { return (x + y)/2 }
      }
      ```

## Vocabulary Terms
|Term | Definition |  
|------|------:|  
|ecosystem| Refers to all tools and aspects of a type of code. For example, JavaScript and Node.js are part of the same ecosystem because they use the same language |  
|Node.js| A JavaScript runtime that allows JavaScript to run on any platform outside of a browser. JavaScript can run in any system that has Node.js|  
|V8 Engine| The JavaScript engine that powers Chrome. It provides the runtime environment that runs JavaScript |  
|module | A file or directory that is loaded by the `require()` function. It is what is loaded from the file. The name of the module goes in the parens. Code can be separated into modules to make it more readable|  
|package | A directory with one or more files in it, that also has a package.json with information about the package|  
| node package manager (`npm`)| A software registry to use, share, and borrow packages|  
|server| A server is a program that provides functionality to other programs, known as clients|  
|environment| A place where you can develop, test, and debug an application or program. It generally has three tiers: development, staging, and production|  
|interpreter| This is what reads and understands the code you write. With Node.js, you can use the command prompt on your computer as a JavaScript interpreter|  
|compiler| A program that translates code in one language to another language. It can translate high level languages to low level languages |  

### Sources
- https://dev.to/somedood/nodejs-breaking-javascript-out-of-the-browser-since-2009-53cn
- https://nodesource.com/blog/ABC-of-JavaScript-and-Nodejs
- https://en.wikipedia.org/wiki/Server_(computing)
- https://medium.com/@osiolabs/use-module-exports-to-keep-node-js-code-organized-9379526ebac8



