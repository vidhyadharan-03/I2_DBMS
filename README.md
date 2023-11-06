# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE : 
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
~~~
        create table studentt(rollno int,Name varchar(20),
        age int,address varchar(40),phoneno int);
~~~
### OUTPUT:
![create table 2;](https://github.com/vidhyadharan-03/I2_DBMS/assets/114286357/21a274bd-60da-4bd8-aebb-08bcb6291816)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
~~~   
 ALTER TABLE studentt
 ADD Department varchar(30);
~~~
### OUTPUT:
![Add alter](https://github.com/vidhyadharan-03/I2_DBMS/assets/114286357/0e62d5c9-1f4a-4bab-9965-e3a4d9f3296e)

### 3) Drop the student table
 
### SQL QUERY: 
~~~~
    drop table studentt;
~~~~
### OUTPUT:
![drop table](https://github.com/vidhyadharan-03/I2_DBMS/assets/114286357/70ee9936-af2f-4513-b7fb-0289a6e55bac)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
~~~
 Truncate table vid;
~~~
### OUTPUT:
![Truncate](https://github.com/vidhyadharan-03/I2_DBMS/assets/114286357/5dcebe72-7ec8-4f3b-a1c7-7ef94eadcec5)

### 5) Rename the student table to mystudent

### SQL QUERY: 
~~~
ALTER TABLE studentt RENAME TO mystudent;
~~~~
### OUTPUT:
![Rename](https://github.com/vidhyadharan-03/I2_DBMS/assets/114286357/93d9392d-34b8-4b14-a661-72469fa29db9)
