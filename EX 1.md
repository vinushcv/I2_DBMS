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
```python
create table students(rollno int,name varchar(30),age int,address varchar(50),phoneno int);
```


### OUTPUT:
![image](https://github.com/vinushcv/I2_DBMS/assets/113975318/4565e0bd-59ff-4430-8ffb-0b2b1985a367)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```python
alter table students add dept varchar(30);
```
### OUTPUT:
![image](https://github.com/vinushcv/I2_DBMS/assets/113975318/3cdc4a52-9d57-4ffe-8716-61bd794b154e)



### 3) Drop the student table
 
### SQL QUERY: 
```python
drop table mystudents;

```
### OUTPUT:
![image](https://github.com/vinushcv/I2_DBMS/assets/113975318/ae2994a0-f70d-448f-8dc4-c906be535cde)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```python
truncate table mystudents;
```

### OUTPUT:
![image](https://github.com/vinushcv/I2_DBMS/assets/113975318/d75cca6e-a583-4c1e-aa26-f2f0dd8611ef)




### 5) Rename the student table to mystudent

### SQL QUERY: 
```python
alter table students rename to mystudents;
```


### OUTPUT:
![image](https://github.com/vinushcv/I2_DBMS/assets/113975318/7ea3b9ed-978a-4b30-b614-438b4eb2c5c1)

