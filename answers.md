Components of a DBMS (Database Management System)
Database Engine:

Handles the storage, retrieval, and updating of data in the database. It executes queries and ensures data consistency.
Database Schema:

Defines the logical structure of the database, including tables, columns, relationships, constraints, and indexes.
Query Processor:

Interprets and executes database queries, optimizing them for performance.
Transaction Manager:

Ensures that transactions are processed reliably and adhere to ACID properties (Atomicity, Consistency, Isolation, Durability).
Data Dictionary:

A metadata repository that stores information about the structure of the database, such as schemas, tables, and users.
Storage Manager:

Manages physical data storage and retrieval on disk, including file organization and data compression.
User Interface:

Provides interfaces like command-line tools, APIs, and GUIs for users to interact with the database.
Relational Database
A relational database is a type of database that organizes data into tables (relations) with rows (records) and columns (fields). Relationships between tables are defined using keys.

Examples:

MySQL
PostgreSQL
Microsoft SQL Server
Oracle Database
Classifications of SQL
DDL (Data Definition Language):

Used to define or modify the structure of database objects like tables, indexes, and schemas.
Examples: CREATE, ALTER, DROP
DML (Data Manipulation Language):

Used to manipulate data within tables.
Examples: SELECT, INSERT, UPDATE, DELETE
DCL (Data Control Language):

Used to control access to the database by managing user permissions.
Examples: GRANT, REVOKE
TCL (Transaction Control Language):

Used to manage transactions.
Examples: COMMIT, ROLLBACK, SAVEPOINT
Primary Key vs. Foreign Key
Primary Key:

A unique identifier for a record in a table.
Must contain unique values and cannot be NULL.
Example: student_id in a "Students" table.
Foreign Key:

A field in one table that references the primary key in another table to establish a relationship.
Allows for enforcing referential integrity.
Example: course_id in an "Enrollments" table referencing course_id in a "Courses" table.
Entity-Relationship Diagram (ERD)
An Entity-Relationship Diagram is a visual representation of entities (tables), their attributes (fields), and the relationships between them. It helps design and understand the structure of a database.

Advantages of Relational Databases
Data Integrity: Ensures accuracy and consistency through constraints like primary keys and foreign keys.
Flexibility: Data can be easily queried and updated.
Scalability: Can handle large volumes of data efficiently.
Security: Supports access controls and user permissions.
Standardized Language: SQL provides a common interface for interacting with the database.
Four Types of Data Types Used in Tables
Integer (INT): Stores whole numbers.
String (VARCHAR/CHAR): Stores text data.
Date/Time (DATE, TIMESTAMP): Stores dates and times.
Floating-Point Numbers (FLOAT, DECIMAL): Stores numbers with decimals.
Purpose of a DBMS
The purpose of a Database Management System (DBMS) is to:

Store and Manage Data: Efficiently handle large amounts of data.
Ensure Data Security: Protect against unauthorized access.
Facilitate Data Access: Enable users to retrieve and modify data easily.
Enforce Data Integrity: Maintain consistency and accuracy of data.
Support Concurrent Access: Allow multiple users to interact with the database simultaneously.