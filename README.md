# Electricity Bill Management System

## Overview

The Electricity Bill Management System is a web-based application designed to streamline the process of paying electricity bills. It automates the calculation of electricity bills, including past due amounts and penalties, offering a more efficient and paperless alternative to manual billing systems. This project is built using PHP, CSS, and JavaScript.

## Features

- User-friendly interface for managing electricity bill payments.
- Automated calculation of current bills, past due bills, and penalties.
- Admin panel for managing user accounts and overseeing billing operations.

## Technologies Used

- PHP
- CSS
- JavaScript
- MySQL

## Prerequisites

- XAMPP (Apache and MySQL)
- Web browser

## How to Run the Project

### Step 1: Start Apache and MySQL
1. Launch XAMPP.
2. Start the Apache and MySQL services.

### Step 2: Set Up the Project Files
1. Extract the project archive.
2. Copy the extracted project folder (`ebill`).
3. Paste the `ebill` folder into the `xampp/htdocs/` directory.

### Step 3: Set Up the Database
1. Open a web browser and navigate to `http://localhost/phpmyadmin/`.
2. Click on the **Databases** tab.
3. Create a new database named `ebillsystem`.
4. Go to the **Import** tab.
5. Click on **Browse file** and select the `ebillsystem.sql` file located in the `DATABASE FILE` folder within the project directory.
6. Click **Go** to import the database.

### Step 4: Access the Application
1. Open a web browser and go to `http://localhost/ebill/index.php`.
2. To access the admin panel, navigate to `http://localhost/ebill/login.php`.

### Admin Login Credentials
- **Email**: admin@gmail.com
- **Password**: Password@123

## Acknowledgments

- Thank you to the open-source community for providing the tools and resources that made this project possible.
