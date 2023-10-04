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
![image](https://github.com/jeevansurya30/F2_DBMS/assets/129417865/03a2e25f-be1c-4e53-9c5f-23bbe4ab548c)



### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:
![image](https://github.com/jeevansurya30/F2_DBMS/assets/129417865/44f298e0-2c71-4733-a5c0-5e2888ac4dc1)

### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```
### OUTPUT:
![image](https://github.com/jeevansurya30/F2_DBMS/assets/129417865/6b7fc69f-5c2d-4c00-8491-597ede5b0a7a)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```
### OUTPUT:
![image](https://github.com/jeevansurya30/F2_DBMS/assets/129417865/0bbabe5a-9afc-4648-bf47-4bc4918679cc)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student rename to mystudent;
```

### OUTPUT:
![image](https://github.com/jeevansurya30/F2_DBMS/assets/129417865/233024aa-21a8-434d-b50d-c96fdac08c7f)

