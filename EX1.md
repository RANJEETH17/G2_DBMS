# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE:4/8/23
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
![image](https://github.com/RANJEETH17/G2_DBMS/assets/120718823/941c2146-63d8-424c-b812-1bda3f4d4907)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);

```
### OUTPUT:
![image](https://github.com/RANJEETH17/G2_DBMS/assets/120718823/4ca7581c-15ac-43e3-8643-363c7d3c8964)


### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;

```
### OUTPUT:
![image](https://github.com/RANJEETH17/G2_DBMS/assets/120718823/473dd9c4-268c-4350-b79f-fe336f55682f)



### 4) Delete the student table using truncate keyword
### SQL QUERY: 
```
truncate table student;

```
### OUTPUT:
![image](https://github.com/RANJEETH17/G2_DBMS/assets/120718823/314619b3-0cfe-4c36-b4ab-6a723b8e8549)


### 5) Rename the student table to mystudent
### SQL QUERY: 
```
alter table student rename to mystudent;

```
### OUTPUT:
![image](https://github.com/RANJEETH17/G2_DBMS/assets/120718823/f757ad99-29cf-41ee-ad23-b580b214985c)


### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
