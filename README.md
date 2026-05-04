# php-clothing-cart-system

 Pastimes Online Clothing System

 Project Overview
Pastimes is a web-based clothing system that allows users to register, log in, browse clothing items, and add them to a shopping cart. The system also includes an admin approval feature to control user access.



 Objectives
- Allow users to register and log in securely
- Enable admin approval before login access
- Display clothing items dynamically
- Allow users to add items to cart
- Provide a simple shopping experience

 Technologies Used
- PHP
- MySQL
- HTML
- XAMPP (Apache & MySQL)
- phpMyAdmin



System Features

 User Features
- User Registration
- Login Authentication
- View Products (Shop Page)
- Add to Cart
- View Cart
- Logout

Admin Features
- View Pending Users
- Approve Users



 System Flow
1. User registers an account
2. Account is set to pending
3. Admin approves the account
4. User logs in
5. User is redirected to shop page
6. User adds items to cart
7. User views cart and total price



Database Structure

 Users Table
- user_id (Primary Key)
- name
- email
- username
- password
- role
- status

Clothes Table
- item_id (Primary Key)
- name
- description
- price
- image
- seller_id
- status

Cart Table
- cart_id (Primary Key)
- user_id
- item_id
- quantity

Orders Table
- order_id (Primary Key)
- user_id
- total
- order_date



How to Run the Project

1. Install XAMPP
2. Start Apache and MySQL
3. Place project folder in:
   C:\xampp\htdocs
4. Open browser and go to:
   http://localhost/pastimes/
5. Create database in phpMyAdmin:
   pastimes_db
6. Import or create tables
7. Run the system



 Test Login Details
- Register a new account
- Approve user via admin panel or phpMyAdmin
- Login with registered credentials



 Notes
- Users must be approved before logging in
- Passwords are encrypted using MD5
- System uses sessions for authentication



 Future Improvements
- Remove items from cart
- Checkout system
- Product image uploads
- Admin product management
- Better UI design (CSS/Bootstrap)


 Author
Murendeni Junior
