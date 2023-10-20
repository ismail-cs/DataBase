fild = column, record = row, keyfild = header


SHOW DATABASES;    (show database list)

CREATE DATABASE [DB_name];    (create database)
CREATE DATABASE college;

DROP DATABASE [DB_name];   (delete database)
DROP DATABASE college;

CREATE TABLE [table_name] (create table)
(



);


CREATE TABLE student 
(
	Roll int, 
    Name varchar(20),
	Gender varchar(10),
	Age int(5),
	GPA double(3,2),
	City varchar(15),
	PRIMARY KEY (Roll) 
);

DROP TABLE [table_name];     (delete table)

RENAME TABLE old_name TO new_name;     (rename table)

