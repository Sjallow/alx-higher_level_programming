SQL - Introduction

SQL (Structured Query Language) is a programming language used to manage and manipulate data in a relational database. It is a standard language used by most modern relational database management systems (RDBMS) such as MySQL, Oracle, PostgreSQL, and Microsoft SQL Server.

SQL is used for a wide range of tasks such as creating, modifying, and deleting database tables, inserting, updating and retrieving data from tables, and creating complex queries to extract specific data from databases.

Examples:

Here is an example of how MySQL can be used to create a simple database and perform some basic operations:

Create a database:

CREATE DATABASE mydatabase;


Create a table:

To create a new table in the mydatabase database, use the following command:

CREATE TABLE users (

 id INT NOT NULL AUTO_INCREMENT,

 name VARCHAR(25 NOT NULL,

 email VARCHAR(50) NOT NULL,

 PRIMARY KEY (id)

);
