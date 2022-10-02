# SQL_course

## Index:
1. What is a Database?
2. Tables & Keys
3. SQL Basics
4. MySQL Windows Installation
5. MySQL Mac Installation
6. Creating Tables
7. Inserting Data
8. Constraints
9. Update & Delete
10. Basic Queries
11. Company Database Intro
12. Creating Company Database
13. More Basic Queries
14. Functions
15. Wildcards
16. Union
17. Joins
18. Nested Queries
19. On Delete
20. Triggers
21. FR Diagrams Intro
22. Designing an ER Diagram
23. Converting ER Diagrams to Schemas 

## 1. What is a database (DB)?
* A database is any collection of related information

### 1.1 What is a a Database Management Systems (DBMS)
* A DBMS is a special software program that helps users create and maintain a database.
    * Easily manages large amounts of information
    * Handles security (permissions and passwords)
    * Backups
    * Importing / Exporting data
    * Concurrency
    * Interacts with softare applications (w programming languages)
    
### 1.2 CRUD (create, read, update, delete)

### 1.3 Two types of databases

**Relational Databases (SQL):**
* Organize data into one or more tables
  * Each table has columns and rows
  * A unique key identified each row
* Most popular: mySQL, Oracle, postgreSQL...
  
**Non-Relational Databases (noSQL / not just SQL):**
* Organize data in anything but a traditional table
  * Key-valu stores
  * Document (JSON, XML...)
  * Graphs
  * Flexible Tables
* Most popular: mongoDB, dynamoDB, apache cassandra, firebase (no standard language, each their own)...
  
### 1.4 Structured Query Language (SQL)
* Standardized language for interacting wit RDBMS
* Used to perform CRUD operations as well as other admin tasks (user management, security, backup...)
* Used to define tables and structures
* SQL used on a RDBMS is not always portable to another RDBMS

### 1.5 Query
A query is a request made to the DBMS for specific information. 

## Tables and Keys
