# Car Rental Management System (DBMS Mini Project)

## 📚 Project Overview

This project is a **Car Rental Management Database** built as part of a **DBMS Mini Project**.  
It is designed to simulate a real-world car rental service, managing information related to customers, vehicles, rentals, payments, and more.

The SQL file (`car_rental_db.sql`) contains the necessary table creation scripts, sample data inserts, and relationships to power the database backend of a rental service.

## 🛠️ Features

- Customers Registration and Management
- Car Inventory Management
- Rental Bookings
- Staff Management
- Relationship Management via Primary and Foreign Keys

## 🗃️ Database Structure

Major tables include:
- **Customers**: Stores customer details
- **Cars**: Information about cars available for rent
- **Rentals**: Tracks which customer rented which car and for how long
- **Payments**: Records payments made for rentals
- **Staff**: Staff involved in managing rentals
- **Branches**: Branch offices for car pickup/drop

(For detailed table schemas and relationships, check the SQL file.)

## 🚀 How to Run

1. Install a database server like **MySQL** or **MariaDB**.
2. Open your SQL command line tool or a GUI like **phpMyAdmin**, **MySQL Workbench**, or **DBeaver**.
3. Create a new database:
   ```sql
   CREATE DATABASE car_rental;
4. Select the database:
   ```sql
   USE car_rental;
5. Import the `car_rental_db.sql` file to create tables and insert sample data:
   ```sql
   SOURCE path/to/car_rental_db.sql;

## 📌 Project Purpose
This mini project demonstrates:

- Practical understanding of Relational Databases

- Hands-on experience with ER Modeling, Normalization, and SQL Queries

- Backend planning for full-stack applications
