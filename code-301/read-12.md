# EJS Partials

* Partials are useful for when you need to use the same HTML across multiple views
* You can easily use the same header and footer on mulitple pages
* Make a new ejs file for everything you want to use accross multiple pages
* Once you do this, use `<%- include(PARTIAL_FILE)%>` where you want that code snippet to go
* You can make a new directory called 'partials' to organize your partials files, just make sure you reference it correctly on the page you want to use the snippet on
