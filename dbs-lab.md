
# **DBS Lab (sem-5)**


## 1. BASIC-1 :

| Use   | Command |
| ------------- | ------------- |
|  Show dB | `SHOW DATABASES` |
| Create dB  | `CREATE DATABASE name;`  |
|  Delete dB | `DROP DATABASE name;` |
| Select dB  | `USE name;` |

#### CREATE TABLE :
~~~~sql
CREATE TABLE users(
id INT AUTO_INCREMENT,
   first_name VARCHAR(100),
   last_name VARCHAR(100),
   email VARCHAR(50),
   password VARCHAR(30),
   location VARCHAR(100),
   dept VARCHAR(100),
   PRIMARY KEY(id)
);
~~~~
## 2. BASIC-2 :

| Use   | Command |
| ------------- | ------------- |
|  Delete/Drop Table | `DROP TABLE tablename;` |
| Show tables  | `SHOW TABLES;`  |
|  Insert Row / Record | `INSERT INTO users (first_name, last_name, email, password, location, dept) values ('Harsh', 'Mehta', 'harsh.mehta2001@gmail.com', 'password','Manipal', 'IT');` |
| Insert Multiple Rows / Records | `INSERT INTO users (first_name, last_name, email, password, location, dept) values ('Harsh', 'Mehta', 'harsh.mehta2001@gmail.com', 'password','Manipal', 'IT'),('John', 'Doe', 'john.doe@gmail.com', 'password','London', 'Placeholder');` |
| Select | SELECT * FROM users; |
|  | SELECT first_name, last_name FROM users; | 
| Where Clause | SELECT * FROM users WHERE location='Manipal'; |
| Delete Row | DELETE FROM users WHERE location = 'London'; |
| Update Row |  |
