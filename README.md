# Andalis_Activity-2

## SET UP DATABASE 
1. go to config.php file and change DB_SERVER to you desired server as well as DB_USERNAME, DB_PASSWORD, DB_NAME
2. IF you are using XAMPP as default localhost server just create a database with your desired name
3. create database table named 'users' or...
4. run this SQL command in mysql
   
   CREATE DATABASE IF NOT EXISTS users;
  -- Use the 'users' database
  USE users;
  -- Create a 'users' table with the specified columns
  CREATE TABLE IF NOT EXISTS users (
      id INT AUTO_INCREMENT PRIMARY KEY,
      username VARCHAR(255) NOT NULL,
      password VARCHAR(255) NOT NULL,
      name VARCHAR(255),
      address VARCHAR(255),
      birthday DATE,
      age INT
  );
