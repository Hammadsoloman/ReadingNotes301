# SQL

## What is SQL?
**SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate,
and transform data from a relational database. And due to its simplicity, SQL databases provide safe and scalable storage for
millions of websites and mobile applications.**

* relational database represents a collection of related (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet,
with a fixed number of named columns (the attributes or properties of the table) and any number of rows of data.

* To retrieve data from a SQL database, we need to write SELECT statements, which are often colloquially refered to as queries. 

* In order to filter certain results from being returned, we need to use a WHERE clause in the query. The clause is applied to each row of
data by checking specific column values to determine whether it should be included in the results or not.

* All strings must be quoted so that the query parser can distinguish words in the string from SQL keywords.

**SQL provides a convenient way to discard rows that have a duplicate column value by using the DISTINCT keyword.Since the DISTINCT
keyword will blindly remove duplicate rows, we will learn in a future lesson how to discard duplicates based on specific columns
using grouping and the GROUP BY clause.**

**In SQL, the database schema is what describes the structure of each table, and the datatypes that each column of the table can contain.
When inserting data into a database, we need to use an INSERT statement, which declares which table to write into, the columns of data 
that we are filling, and one or more rows of data to insert.**

**you can use a DELETE statement, which describes the table to act on, and the rows of the table to delete through the WHERE clause
ou can create a new database table using the CREATE TABLE statement.**

**SQL provides a way for you to update your corresponding tables and database schemas by using the ALTER TABLE statement to add, remove,
or modify columns and table constraints.**

**In some rare cases, you may want to remove an entire table including all of its data and metadata, and to do so, you can use the DROP
TABLE statement, which differs from the DELETE statement in that it also removes the table schema from the database entirely.**

![image](https://static.arageek.com/wp-content/uploads/2018/12/85005953-sql-icon.jpg)

