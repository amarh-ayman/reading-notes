# Database Normalization

is a process used to organize a database into tables and columns.

- The main idea with this is that a table should be about a specific topic and only supporting topics included.

# Reasons for Database Normalization

There are three main reasons to normalize a database:

- The first is to minimize duplicate data,
- the second is to minimize or avoid data modification issues,
- and the third is to simplify queries.

# Duplicated information presents two problems:

1- It increases storage and decrease performance.

2- It becomes more difficult to maintain data changes.

# There are three common forms of database normalization:

1. First Normal Form – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.

1. Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.

1. Third Normal Form – the table is in second normal form and all of its columns are not transitively dependent on the primary key.

![img](https://i.stack.imgur.com/O2smv.png)

![img](https://i0.wp.com/www.complexsql.com/wp-content/uploads/2017/04/Normalization-300x169.jpg?resize=289%2C163)
