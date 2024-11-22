## State and Explain the components of a DBMS(Database Management System)
- Database:
  The collection of organized data stored in tables, rows, and columns.

- DBMS Software:
  The software that manages database operations like querying, storing, and updating data (e.g., SQLite, MySQL).

- Data:
The actual information stored in the database, such as records about users, products, or transactions.

- Query Processor:
The part of the DBMS that interprets and executes user queries (e.g., SQL commands).

- Data Dictionary:
A repository of metadata describing the structure and rules of the database, such as table names and data types.
## What is a relational database? Give 4 examples.
- A relational database organizes data into tables (called relations) consisting of rows (records) and columns (fields). The tables are connected by relationships, and the structure follows a schema. Data is managed using a relational model and is manipulated through SQL (Structured Query Language).

#### Examples of Relational Databases:
- MySQL
A popular open-source relational database widely used in web applications.

- PostgreSQL
An advanced open-source relational database with features like extensibility and compliance with SQL standards.

- Microsoft SQL Server
A relational database developed by Microsoft, often used in enterprise applications.

- Oracle Database
A powerful and scalable relational database system used in large-scale applications.
## What is the difference between a Primary Key and a Foreign Key?
- Primary Key: A unique identifier for each record in a table. It ensures that no two rows have the same value and cannot contain NULL values.
- Foreign Key: A field in one table that refers to the Primary Key in another table. It establishes a relationship between the two tables.
## What is an Entity-Relationship Diagram (ERD)?
- An Entity-Relationship Diagram is a visual representation of the data and their relationships in a database. It uses symbols like entities (tables), attributes (columns), and relationships (connections between tables) to design the database structure.
## What are the advantages of relational databases?
- Data Integrity: Maintains accurate and consistent data across tables.
- Scalability: Suitable for small to large applications.
- Flexibility: Allows complex queries using SQL.
- Normalization: Reduces data redundancy by organizing it into related tables.
- Security: Access control features protect sensitive data.
## State four types of data types used to store data in tables:
- Integer: For whole numbers (e.g., INT in SQL).
- Text: For strings or characters (e.g., VARCHAR or TEXT).
- Date/Time: For storing dates and times (e.g., DATE, TIMESTAMP).
- Boolean: For true/false values (e.g., BOOLEAN).
## What is the purpose of a Database Management System (DBMS)?
The purpose of a DBMS is to efficiently manage and interact with databases by:

- Storing and retrieving data in a structured way.
- Ensuring data security and access control.
- Enabling multi-user access without conflicts.
- Supporting data consistency and integrity.
- Providing tools for querying, updating, and analyzing data.
