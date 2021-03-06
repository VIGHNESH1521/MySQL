# MySQL

![image](https://user-images.githubusercontent.com/90493668/153834562-fba49b13-0500-4a75-b1a3-385fe09f946a.png) ![image](https://user-images.githubusercontent.com/90493668/153834640-5cbc3200-d630-4791-a89c-1ecede70a348.png)


MySQL is a widely used relational database management system (RDBMS).
MySQL is free and open-source.
MySQL is ideal for both small and large applications.

## What is MySQL?

- MySQL is a relational database management system
- MySQL is open-source
- MySQL is free
- MySQL is ideal for both small and large applications
- MySQL is very fast, reliable, scalable, and easy to use
- MySQL is cross-platform
- MySQL is compliant with the ANSI SQL standard
- MySQL was first released in 1995
- MySQL is developed, distributed, and supported by Oracle Corporation.

## Who Uses MySQL?

- Huge websites like Facebook, Twitter, Airbnb, Booking.com, Uber, GitHub, YouTube, etc.
- Content Management Systems like WordPress, Drupal, Joomla!, Contao, etc.
- A very large number of web developers around the world

## What is RDBMS?

- RDBMS stands for Relational Database Management System.
- RDBMS is a program used to maintain a relational database.
-RDBMS is the basis for all modern database systems such as MySQL, Microsoft SQL Server, Oracle, and Microsoft Access.
-RDBMS uses SQL queries to access the data in the database.

## What is a Database Table?

- A table is a collection of related data entries, and it consists of columns and rows.
- A column holds specific information about every record in the table.
- A record (or row) is each individual entry that exists in a table.

## What is a Relational Database?

A relational database defines database relationships in the form of tables. The tables are related to each other - based on data common to each.

## Some of The Most Important SQL Commands

- SELECT - extracts data from a database
- UPDATE - updates data in a database
- DELETE - deletes data from a database
- INSERT INTO - inserts new data into a database
- CREATE DATABASE - creates a new database
- ALTER DATABASE - modifies a database
- CREATE TABLE - creates a new table
- ALTER TABLE - modifies a table
- DROP TABLE - deletes a table
- CREATE INDEX - creates an index (search key)
- DROP INDEX - deletes an index


# Start Using MySQL

    use mysql;
    
# Create database

    CREATE DATABASE testDB;
    
# Create Table
 
      CREATE TABLE Persons (
    ->     PersonID int,
    ->     LastName varchar(255),
    ->     FirstName varchar(255),
    ->     Address varchar(255),
    ->     City varchar(255)
    -> );
    
# Viewing Table Details
    
        describe Persons;
        
# Inserting Values to the table created
 
      insert into Persons(PersonID, LastName, FirstName, Address, City)
    -> VALUES(124, 'K U', 'SUDEEP', 'PEENYA', 'BANGALORE'),
    -> (125, 'C', 'YASHAS', 'MALLESHWARAM', 'BANGALORE'),
    -> (126, 'K R', 'SUMAN', 'YELAHANKA', 'BANGALORE'),
    -> (127, 'K', 'KISHORE', 'KURUBARAHALLI', 'BANGALORE'),
    -> (128, 'B N', 'SAGAR', 'KURUBARAHALLI', 'BANGALORE');
 
# Viewing the table
     
     select * from Persons;
  
# Drop the table
  
      DROP TABLE Persons;
 
# MySQL SHOW WARNINGS statement 

When you execute a statement, if errors, warnings, or notes occur, you can use the SHOW WARNINGS diagnostic statement to display detailed information.

      SHOW WARNINGS;

# How to load the sample database

The required database has been uploaded

      source C:\Users\VIGHNESH SUDHAKAR\Desktop\MySQL\mysqlsampledatabase.sql
      

# Use the SHOW DATABASES command to list all databases in the current server

    show databases;
