# SQL-Commands

SQL (Structured Query Language) includes various types of commands for managing databases. Here are some common SQL commands categorized by their purposes:

## Data Definition Language (DDL)

### Create a Database
```sql
CREATE DATABASE your_database_name;
```
### Create a Table
```sql
CREATE TABLE your_table_name (
   column1 datatype,
   column2 datatype,
   ...
);
```
### DROP TABLE
```sql
DROP TABLE your_table_name;
```
## Data Manipulation Language (DML)

### Insert Data into the Table
```sql
INSERT INTO your_table_name (column1, column2, ...) VALUES (value1, value2, ...);
```
## Transaction Control Language (TCL)

### Commit the Transaction
```sql
COMMIT;
```
### Rollback the Transaction
```sql
ROLLBACK;
```
## Control Database Access (DCL - Data Control Language):

### Grant privileges to a user or role:
```sql
GRANT privilege_name ON table_name TO user_or_role;
```
### Revoke privileges from a user or role:
```sql
REVOKE privilege_name ON table_name FROM user_or_role;
```
