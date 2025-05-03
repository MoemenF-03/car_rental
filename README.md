# Car Rental Management System

A complete **Car Rental Management System** developed in PHP and MySQL. This web application allows users to rent cars, view available vehicles, and manage bookings. The admin can manage car listings, rental details, and view booking history.
**this project is an academic project for WEB DEV**
## Features

### User Features:
- Register and log in
- Browse available cars
- Book a car for specific dates
- View booking history
- Contact car rental company

### Admin Features:
- Dashboard with statistics
- Manage car listings (Add/Edit/Delete)
- Manage brands
- Manage users and bookings
- View contact queries
- Update site settings

## Technologies Used

- PHP (Core PHP)
- MySQL
- HTML5/CSS3
- Bootstrap
- JavaScript
- Font Awesome

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/MoemenF-03/car_rental.git
   cd car_rental
2. **Setup Database**
   Import the SQL file (car_rental.sql) into your MySQL database.
   You can use tools like phpMyAdmin or MySQL CLI:
   ```sql
   CREATE DATABASE carrental;
   USE carrental;
   -- Import the SQL script here
3. **Configure Database Connection**
   Open /includes/config.php
   Set your database credentials:
   ```php
   $dbh = new PDO("mysql:host=localhost;dbname=carrental", "root", "");
4. **Run Locally**
   Place the project in your local server root (e.g., C:/wamp64/www/ for WAMP).
   Start Apache and MySQL from WAMP/XAMPP.
   Visit: http://localhost/car_rental/
## Screenshots
### User Interface:
![Car-Rental-Portal-939x1536](https://github.com/user-attachments/assets/a23dd9fc-35b1-4a12-abbf-8a39d580033a)
### Admin Dashboard:
![Car-Rental-Portal-Admin-Dashboard](https://github.com/user-attachments/assets/de4b8243-3350-42ab-839b-4fbf3a074ad7)
## Author
Moemen Ferjani
[GitHub Profile](https://github.com/MoemenF-03)

   
