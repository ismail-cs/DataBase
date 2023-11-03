fild = column,   record = row,   keyfild = header

- [x] show database list
```
SHOW DATABASES;    
```
---

- [x] Create Database
```
CREATE DATABASE DB_name;
```
--- 

- [x] Delete Database
```
DROP DATABASE DB_name;
```

---

- [x] Create table
```
CREATE TABLE table_name
(

	Roll int, 
    	Name varchar(20),
	Gender varchar(10),
	Age int(5),
	GPA double(3,2),
	City varchar(15),
	PRIMARY KEY (Roll) 

);
```
---

- [x] Delete Table
```
DROP TABLE table_name;     
```
---

- [x] Rename Table
```
RENAME TABLE old_name TO new_name;     
```
---

- [x] Insert one row on a Table
```
INSERT INTO student_details 
( Roll, Name, Gender, Age, GPA, City)
VALUES (101, 'Rahim', 'Male', 18, 3.44, Khulna);
```
---

- [x] Insert multiple row on a Table
```
INSERT INTO student_details 
VALUES 
(103, 'sakib', 'Male', 18, 3.44, 'khulna'),
(104, 'rakib', 'Male', 18, 3.44, 'jashore'),
(105, 'sazzad', 'Male', 18, 3.44, 'barisal');
```
