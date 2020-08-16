# HTTP and REST

* HTTP stands for Hyper Text Transfer Protocol
* HTTP defines how requests and responses should be formatted between clients and servers. It is the foundation of the world wide web
* The first line of an HTTP request contains the __METHOD__, __URL__, and __HTTP VERSION__. These are followed by the __HEADERS__, which are key value pairs. 
* __Safe__ methods are for retrieval, __Idempotent__ methods will always get the same response, and __Cacheable__ means the client should be able to cache the response
* The HTTP response contains the __HTTP VERSION__, __STATUS CODE__, and the __STATUS MESSAGE__ on the first line and the request headers on the second line. 
* __REST__ stands for REpresentational State Transfer.
* RESTful endpoints deliver data in JSON formant
* REST APIs are documented with a a "live" documentation known as Swagger, which show you how to use an API and give you the ability to make live requests from it
* Swagger allows you to create your own documentation for your API.

### [What Is A REST API](https://www.youtube.com/watch?v=Q-BpqyOT3a8)

* API stands for application program interface, consisting of a structeured request and response
* REST is an architecture style for desigining network applications and relies on HTTP
* PUT is used generally in web forms
* PUT updates a resource
* Rarely used requests are __HEAD__, __OPTIONS__, and __PATCH__
* An endpoint is the URI/URL where the api is accessed by a client
* Postman is used to make API requests

