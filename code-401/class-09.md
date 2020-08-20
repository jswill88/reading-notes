# API Server

#### Router Parameters
* When you get params on a route (`:paramName`) you can access it with `req.params.paramName`
* You can call middleware like this `app.get('/places/:city', middleWareCall, (req,res) => {})`, or `app.use`
* `router.param` lets you run middleware only when certain params are present
#### Sub Documents in Mongoose
* Mongoose gives structure to Mongo documents. NoSQL databases are not structured by default
* You can define sub documents in a Mongoose schema to help do more with your data
* This may be difficult to keep track of, but it has some benefits when organizing data
#### Joining Data/Documents in Mongo
* `populate()` is a method for joining 2 collenctions
* You can also make a virtual field in a document that points to another.
* With `pre('find')` you can do a collection on the fly rather than storing the relation
* You can also create a reference column that has all the `_id`s of the document to make quicker `finds()`
