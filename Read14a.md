# DATABASE NORMALIZATION

## What is a Database Table?
**The database table is where all the data in a database is stored, and without tables, there would not be much use for relational databases.**
## Overall Structure of a Database Table
**A database consists of one or more tables.  Each table is made up of rows and columns.  If you think of a table as a grid, the column go from left to right across the grid and each entry of data is listed down as a row.**

**Each row in a relational is uniquely  identified by a primary key.  This can be by one or more sets of column values.  In most scenarios it is a single column, such as employeeID.**

**Every relational table has one primary key.  Its purpose is to uniquely identify each row in the database.  No two rows can have the same primary key value.  The practical result of this is that you can select every single row by just knowing its primary key.**
**Database normalization is a process used to organize a database into tables and columns.  The main idea with this is that a table should be about a specific topic and only supporting topics included.**

**By limiting a table to one purpose you reduce the number of duplicate data contained within your database. This eliminates some issues stemming from database modifications.**

## Reasons for Database Normalization
**There are three main reasons to normalize a database.  The first is to minimize duplicate data, the second is to minimize or avoid data modification issues, and the third is to simplify queries.**

![image](https://www.sqlrelease.com/wp-content/uploads/2015/06/Database-normalization.png)
