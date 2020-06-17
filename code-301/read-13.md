# Update/Delete

## Sending Form Data
* An HTML form is basically a way to send data to a server
* The `action` attribute defines where the data from the form will be sent, and needs to be a url or valid pathway
* The `action` should be a file on the server that can handle the incoming data
* The `method` says how the data is sent. Either `get` or `post`
* `GET` asks the server to send back a specified resource, and it will send the data back in the url
* If `POST` is used, the input data will be sent to the server, and it will not have the data in the url
* You can use PHP to get the data from the form
* Express is what you use to handle forms in Node.js
* If you want to send a file in a form, you need to use `enctype="multipart/form-data" as another attribute in the form
* Look out for characters that look like code in forms

## HTML5 Forms Reference
*   `name=` defines how the input will be referenced. It can also be used on the name of the form
* `fieldset` defines a group of controls within a form
* `method="post"` sends form information to the server as part of the request body
* `method="get"` sends form information as part of the url
* You can use `<legend>` tags to and a caption to the content of a filedset

