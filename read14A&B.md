14A

As tables satisfy each successive database normalization form, they become less prone to database modification anomalies and more focused toward a sole purpose or topic

There are three main reasons to normalize a database. The first is to minimize duplicate data, the second is to minimize or avoid data modification issues, and the third is to simplify queries.

Duplicated information presents two problems:

It increases storage and decrease performance. It becomes more difficult to maintain data changes.

Definition of Database Normalization There are three common forms of database normalization: 1st, 2nd, and 3rd normal form. They are also abbreviated as 1NF, 2NF, and 3NF respectively.

First Normal Form – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns. Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key. Third Normal Form – the table is in second normal form and all of its columns are not transitively dependent on the primary key

