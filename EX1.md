
# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE:

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
create table Studentsdetails(rollno numeric(12),name varchar(20),age numeric(2),address varchar(100),phoneno numeri
c(10));

```



### OUTPUT:
![Screenshot 2023-10-05 092952](https://github.com/svarsha220/F2_DBMS/assets/127709117/14a75313-294a-412c-b3ad-b110011f4b31)




### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table Studentsdetails add dept char(20);

```
### OUTPUT:
![image](https://github.com/svarsha220/F2_DBMS/assets/127709117/1f3b72df-689b-4d78-bca3-282249b7a6e7)

### 3) Drop the student table


### SQL QUERY: 
 ```
 drop table Studentsdetails;

```


### OUTPUT:

![image](https://github.com/svarsha220/F2_DBMS/assets/127709117/e9564909-6a5b-44c2-a962-ba56c8543a06)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 

```

truncate table Studentsdetails;

```
### OUTPUT:
![image](https://github.com/svarsha220/F2_DBMS/assets/127709117/ba542667-115c-4bac-bbd7-df8d67a105a1)





### 5) Rename the student table to mystudent

### SQL QUERY: 
```

alter table Studentsdetails rename to my_student;

```

### OUTPUT:
![image](https://github.com/svarsha220/F2_DBMS/assets/127709117/e1601106-6f71-42e3-abff-5865050abb55)

