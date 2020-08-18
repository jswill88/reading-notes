# Express

### Express Routing
* The request object is found in the `request.params`
* The query strings are elements in the params object
* The response sends headers, cookies, and status codes, and Express uses this to format for the browser
* Middleware is a series of functions that a request goes through, and each function reiceives a `request`, `response`, and `next` parameter
* The types of middleware are application and route
* You should modularize your code such that each module does one thing very well
* Export your server as a module in a library to test rather than starting the actual server
* Use `supertest` to run the tests
* You can also wrap `superagent` in a module to test. Also, create a folder called `__mocks__` and put an `agent.js` file in in it. `jest.mock()` will use this during the tests
* Test Units, Integration, and Acceptance with server testing

### [Middleware Explained](https://www.youtube.com/watch?v=9HOem0amlyg)
*  __Middleware__ are functions invoked by Express before the final request handler is made
* An example of using authentication middleware
* Middleware functions carry an optional `next` parameter
* The last function does not need the `next` parameter
* `app.use` will run middleware on all requests
*  Put `next` as the third parameter after request and reqponse and call `next()` at the end of the middleware function to link to the next function in the chain until the final request
