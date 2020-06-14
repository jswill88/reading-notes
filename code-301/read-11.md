# EJS

## Getting Started
* Install express, body-parser, cors, EJS, and require them
* app.use(bodyParser())
* `var path = require('path')` (do not need to install path)
```
app.set('views', path.join(__dirname, 'views'));
app.set('view engine','ejs');
```
* create a file called index.ejs
* listen on the server you want to listen on

## Injecting Values into the views
* Add an index.ejs file where you can put content for the EJS viewer
* put object in `response.render` in server file, and make key value pairs for what you want to render in your EJS viewer
* Use `<%= content %>` to add things to your ESJ viewer from your server file, a lot liike mustache

## For loops and arrays
* Make an array in your server.js file
```
<% for(var person of people) { %>
<li><%= person.name %></li>
<% } %>
```
* This will loop through all the names in your people object and make list items

## If/else statment
* equal sign only used to evaluate values
```
<% for(var person of people) { %>
<% if (person.name === 'dave') { %>
<li>This is definitely<%= person.name %>!</li>
<% } else { %>
<li>Other stuff</li>
<% } %>
<% } %>
```

## Google Books API, Volumes
* You do not need to provide the authorization HTTP header with the GET request
* the 'kind' returned is 'books#volumes'
* The array 'items' has all the books that are returned
* the title and authors are in the 'volumeInfo' object
* The authors are in an array, even if it is only one author
* Useful queries include 'intitle', 'inauthor', inpublisher', and 'subject'
* You can paginate with 'startIndex' and 'maxResults'
