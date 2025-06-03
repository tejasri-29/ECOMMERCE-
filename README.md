🛒 E-Commerce Website
A beginner-friendly e-commerce web application developed using PHP and MySQL. This project serves as a foundational platform for understanding the core functionalities of online shopping systems.

📌 Features
User Registration and Authentication

Product Catalog Browsing

Shopping Cart Functionality

Order Placement and Management

Admin Panel for Product Management

🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Server: Apache (via XAMPP)

🚀 Getting Started
Prerequisites
XAMPP installed on your local machine.

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/tejasri-29/ECOMMERCE-.git
Move the project to XAMPP's htdocs directory:

bash
Copy
Edit
mv ECOMMERCE- /path-to-xampp/htdocs/
Start Apache and MySQL via XAMPP Control Panel.

Create the database:

Access phpMyAdmin.

Create a new database named ecommerce.

Import the provided SQL file:

Click on the ecommerce database.

Navigate to the Import tab.

Choose the ecommerce.sql file from the project directory.

Click Go.

Configure Database Connection:

Open includes/db.php.

Ensure the database credentials match your local setup:

php
Copy
Edit
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "ecommerce";
Access the application:

Navigate to http://localhost/ecommerce/ in your web browser.

📂 Project Structure
perl
Copy
Edit
ECOMMERCE-/
├── admin/              # Admin panel for product management
├── cart/               # Shopping cart functionalities
├── includes/           # Database connection and common functions
├── products/           # Product listings and details
├── user/               # User registration and login
├── index.php           # Homepage
└── README.md           # Project documentation


🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
