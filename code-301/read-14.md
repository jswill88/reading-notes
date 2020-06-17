# Database Normalization

* Data normalization is a process to organize a database into tables and columns
* It is important to normalize the data to minimize duplicate data, to avoid modification issues, and to simplify queries
* Duplication can be a big problem, because if one item changes in a large table, you may have to change many others if it is not organized well
* There are some things you cannot insert unless you have values for the entire row
* If you update a row, you may have to make the same update in many rows
* If one pice of data gets deleted, you might lose other data unintentionally
* There are three common data normalization forms, known as 1NF, 2NF, and 3NF
  * First Normal Form (1NF) - The info is stored in a relational table and there are no repeating groups of columns
  * Second Normal Form (2NF) - All the columns depend on the table's first primary key
  * Third Normal Form (3NF) - The columns are not dependent on the primary key
* Third Normal Form relies on Second Normal Form, and Second Normal Form relies on First Normal Form
