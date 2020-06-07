# Node.js

## An Introduction to Node.js
* Node is a JavaScript runtime
* Node supports the latest versions of JavaScript, which means you will not have to worry as much about compatibility issues
* `npm` is the JavaScript packeage manager
* Node is used to develop apps with modern JavaScript frameworks, such as React and Angular
* Node is event driven, and it uses the libuv library to implement asynchronous behavior
* Set up your server.js file like this:
  * Start by requiring the module and assigning it to a variable. We used express in our project
  (`const express = require('express');)
  * Use `.createServer((request, response =>{}))` to create a new web server object
  * To listen on port 3000, add `.listen(3000)` to the end
* Node.js is especially useful for appications that require real time interaction or collaboration
* Working with JavaScript in the backend makes the apps fast and scalable, and it is easier for developers, because they can think in one language
* Node reads JSON 