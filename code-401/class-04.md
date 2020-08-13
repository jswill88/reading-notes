# Advanced Mongo/Mongoose

1. __Why would a developer choose to make data models?__  
Data models are useful, because they will help a developer understand how a database will be built, and so that it is done in a way that makes sense.

2. __What purpose do CRUD operations serve?__  
With CRUD(Create, Read, Update, Delete), you make sure that you have everything you need to have a successful database or web application.  
https://www.codecademy.com/articles/what-is-crud

3. __What kind of database is Postgres? What kind of database is MongoDB?__  
Postgres is a SQL database and MongoDB is a NoSQL database.  
https://www.youtube.com/watch?v=ZS_kXvOeQ5Y

4. __What is Mongoose and why do we need it?__  
It translates between Node.js objects and the representation of those objects in MongoDB. It allows developers to more easily work with MongoDB.  
https://www.freecodecamp.org/news/introduction-to-mongoose-for-mongodb-d2a7aa593c57/

5. __Describe how NoSQL Databases scale horizontally__
They use mulitple servers to grow horizontally whereas SQL databases rely on a single server. This can be more efficient than using a single node, but the infrastructure ends up being more complex.   
https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool

6. __Give one strong argument for and against NoSQL Databases__    
No SQL databases are good because the schema is more flexible, and it is easier to change as needed. SQL databases are better when you need to perform more complex queries.  
https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool

7. __Define three related pieces of data in a possible application. An example for a store application might be Product, Category, and Department. Describe the constraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department__  
This could be used for a jazz musician database. The pieces of data would be Musician, Instrument, Sub-Genre. Each musician has an instrument, and they belong in Sub Genres. 

8. __Name 3 cloud based NoSQL Databases__
    1. MongoDB
    2. CouchDB
    3. Redis  
  https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool

## Vocabulary Terms  
  
|Term | Definition |  
|---|---| 
|database | An organized collection of data. Used to store information that can be updated and retrieved. https://www.techopedia.com/definition/1185/database-db|
|data model | Defines the structure of a database. They show how data is connedted and how it is stored in a database. https://www.tutorialspoint.com/dbms/dbms_data_models.htm|
|CRUD | Stands for Create, Read, Update, and Delete. It is used for databases and web applications. They correspond with the HTTP methods POST, GET, PUT, AND DELETE. https://www.codecademy.com/articles/what-is-crud|
|schema| A way to define what goes into a relational database. All records in a table will have to follow the schema. https://www.youtube.com/watch?v=ZS_kXvOeQ5Y |
|sanitize| This means to remove dangerous characters from data before putting it into a database or onto a web application. https://www.quora.com/What-exactly-is-data-sanitization-with-respect-to-SQL-injection#:~:text=Data%20sanitization%20means%20that%20you,SQL%20statements%20but%20string%20%2B%20operations. |
|Structured Query Language (SQL) | A powerful longuage that allows you to write database queries. It consists of tables and rows. It works with relational databases, and it has strict requirements for what can go in the table defined in a schema. https://www.youtube.com/watch?v=ZS_kXvOeQ5Y |
|Non SQL (NoSQL) | It is built to store a large amount of data. This does not use tables, but collections. There are no relations, or they do not rely on relations as much, and all the data is in the same place, so you don't need queries to connect the data. https://www.youtube.com/watch?v=ZS_kXvOeQ5Y|
|MongoDB | The most popular NoSQL database. https://www.youtube.com/watch?v=ZS_kXvOeQ5Y|
|Mongoose | An Object Data Modeling library that allows node.js to use MongoDB easily. It is a schema based solution for modeling data. https://mongoosejs.com/ |
|record| A record is a single entry in a databse. In a NoSQL database, this would be a document, and in a SQL database, this would be a row. https://en.wikipedia.org/wiki/NoSQL|
|document | Essentially the rows in a table. They are written in something like json format. They do not need to use the same schema, and different documents can have different fields. https://www.youtube.com/watch?v=ZS_kXvOeQ5Y|
|Object Relation Mapping (ORM) | The transfer of data from a database table into an object that can be processed by the coding language. https://www.fullstackpython.com/object-relational-mappers-orms.html|
