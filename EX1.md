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
``create table student(rollno int,name varchar(10),age int,address varchar(16),phoneno int);``


### OUTPUT:
![image](https://github.com/Vijisdurai/G2_DBMS/assets/118343184/ea814585-0563-4de9-b673-eb042e6626d8)

![image](https://github.com/Vijisdurai/G2_DBMS/assets/118343184/b8c005b7-3c04-4a5e-9b34-af8dfd72279c)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
``alter table student add department varchar(10);``

### OUTPUT:
![image](https://github.com/Vijisdurai/G2_DBMS/assets/118343184/c4d910c5-19f3-4108-9f06-23accd1dc006)

## PREVIOUS TABLE:
![image](https://github.com/Vijisdurai/G2_DBMS/assets/118343184/b8c005b7-3c04-4a5e-9b34-af8dfd72279c)

## ALTERED TABLE:
![image](https://github.com/Vijisdurai/G2_DBMS/assets/118343184/366de4e4-119e-4f5f-a0ad-28ca3c7ccbd7)


### 3) Drop the student table
 
### SQL QUERY: 
`` drop table student;``

### OUTPUT:
![image](https://github.com/Vijisdurai/G2_DBMS/assets/118343184/78efa1b2-e539-4fb7-bd7f-ee14f54f7808)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
``TRUNCATE TABLE student;``

### OUTPUT:
![image](https://github.com/Vijisdurai/G2_DBMS/assets/118343184/5d44392b-8e64-4110-89e8-deef85651523)

### 5) Rename the student table to mystudent

### SQL QUERY: 
``alter table student_details rename to mystudent;``

### OUTPUT:
![image](https://github.com/Vijisdurai/G2_DBMS/assets/118343184/13071f0e-7a0a-4bc4-b2f1-72764f221184)
