# Express Routing and Connected API
### [Using Express Routing](https://expressjs.com/en/guide/routing.html)
* __Routing__ is how endpoints respond to client requests
* You can use app.all() to handle all HTTP methods. This can be used to access a secret section before moving on
* Use `next()` to hand off to the next callback function
* A `-` and `.` are interpreted literally by string based paths
* To use a `$`, enclose it in `[]` with an escape like `[\$]`
* `/ab?cd` will match `acd` and `abcd`, like regex
* `/ab+cd` will match `abcd`, `abbcd`, `abbbcd`, ect.
* `/ab*cd` will match `abcd`, `abRANDOMSTUFFcd`, etc.
* `/ab(cd)?e` will match `abe` or `abcde`
* `/a/` will match anything with an `a` in it
* `/.*fly$/` will match regex style
* If the route path is `/users/:id/books/:book`, and you go to `/users/1/books/2` the object will be {users: 1, Books: 2} (`req.params`)
* You can use a dot or hyphen to separate params `/flight/:here-:there`
* You can specify what can be matched in a param with regex `/:id(\d+)`
* You can handle more than one callback function on a route
* `res.end()` to end the response process
* You can also prompt a download, or send files at the end of a route
* You can chain route hanlders with `app.route`, then chaining `.post`, `.get` etc.

### [Express Routing](https://expressjs.com/en/guide/routing.html)
* `Router` is like a mini express app
* Express Router can control all the Express routing, but does not have other parts of Express
* Apply the routes to the application at the bottom of the file with `app.use('/', router)`
* You can make multiple Express routers in an application, to make an app more modular and flexible
* Route middleware can be used to validate parameters
* Use `app.route` as a shortcut to put multiple methods on the same route

