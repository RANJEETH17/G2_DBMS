# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```
### OUTPUT:
![image](https://github.com/ARUNKUMART9968/G2_DBMS/assets/121215794/490a6bfd-05f1-4789-8526-274d786999c9)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);

```
### OUTPUT:
![image](https://github.com/ARUNKUMART9968/G2_DBMS/assets/121215794/9ee913f2-a82f-4b3d-a2bb-d5f2254184d1)

### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;

```
### OUTPUT:
![image](https://github.com/ARUNKUMART9968/G2_DBMS/assets/121215794/fbbd4d76-7f7f-4a96-876d-ea3f7688a81f)


### 4) Delete the student table using truncate keyword
### SQL QUERY: 
```
truncate table student;

```
### OUTPUT:
![image](https://github.com/ARUNKUMART9968/G2_DBMS/assets/121215794/a588479f-0b33-4e5a-88cd-e8b2e2069a77)

### 5) Rename the student table to mystudent
### SQL QUERY: 
```
alter table student rename to mystudent;

```
### OUTPUT:
![image](https://github.com/ARUNKUMART9968/G2_DBMS/assets/121215794/0c723764-5e0e-49ce-927b-b1fdd0a03f66)

### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
