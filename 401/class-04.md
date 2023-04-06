# Class 4 notes

## nosql vs sql

-What type of database is the best fit for the complex query intensive environment?

SQL databases 

What type of database is the best fit for hierarchical data storage?

SQL databases are not best fit for hierarchical data storage. But, NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data. NoSQL database are highly preferred for large data set

Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

In most typical situations, SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server. On the other hand, NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.

## sql modeling techniques

Among data tables, what is a one-to-many relationship and how do we “relate” them?

In some cases an entry in one table can be related to more than one entry in another.  This is called a one-to-many relationship.  In our example there are many employees in on department; therefore, we show a many-to-one relationship.

Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.

When working with SQL databases it is often useful to create diagrams of the database tables and their relationships.  These may be done during the design process, as  your data modeling, or once the database is created, in order to document the tables’ dependencies. 

Explain the difference between a primary and foreign key.
Videos

Foreign Key – This is a column or set of columns which match a primary key in another table.
The Primary Keys.  Remember the primary keys uniquely identify each row in a table.  A table typically has one primary key, but can have more.  When the key has more than one column, it is called a compound key.


## sql vs nosql

How do we treat keywords and parameters differently in SQL syntax?
Define normalization within the context of schemas and data.
Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

## Sources
[SQL VS NoSql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)
[sequelize API](https://sequelize.org/docs/v6/)
[EssentialSQL](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)
