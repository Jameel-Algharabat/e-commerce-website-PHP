# Overview

This project is a pure PHP/MySQL e-commerce platform that features a user-friendly interface and a variety of functionalities for both users and administrators. The user side allows users to view product categories, add products to the cart, and proceed to checkout. On the admin side, the admin can view sales, users, add products and categories, edit, update, and delete previously mentioned items. The user can also leave comments on each product if desired. The landing page includes:

- Header and navigation bar with login and registration buttons
- A slider containing images
- A special section for discounts
- Login and registration pages (implemented using OOP)
- Users can:
  - Register to make payments
  - Login to the website
  - Search for any specific product
  - Filter by category and price
  - Edit their profile
  - Add products to the shopping cart
  - Delete or update products in the shopping cart
  - Make a complete payment
- Administrators can:
  - Access an administrative control panel
  - Add, edit, remove, and view products
  - Add, edit, remove, and view categories
  - Add, edit, remove, and view users
  
  
# Setup Guide

- Clone the repository to your local machine
```
git clone https://github.com/YOUR_USERNAME/e-commerce-website-php.git
```
- Import the provided SQL file (e-commerce-website-php.sql) to your MySQL database
- Update the database configuration in dbcon.php file with your MySQL credentials
- Start the PHP server by running the following command in the project directory
```
php -S localhost:8000
```
- Open http://localhost:8000 in your browser to view the website

# Technologies Used
- PHP
- MySQL
- Note

You can run the web on any port you want instead of 8000. Also, you can use xampp or any other software that use PHP and MySQL instead of the embedded server.


# Disclaimer

Please note that this project is not production ready and has been built for educational purposes only. It may contain bugs or lack certain features and security measures that are required for a production environment. Use it at your own risk.



