# NewsPortal

## Project Overview
**NewsPortal** is a web-based news portal developed using PHP and MySQL. This project is divided into two main modules: the User Module and the Admin Module.

### Technologies Used
- **Programming Language:** PHP
- **Database:** MySQL
- **User Interface Design:** HTML, AJAX, jQuery, JavaScript
- **Web Browsers Supported:** Mozilla Firefox, Google Chrome, Internet Explorer 8, Opera
- **Development Environment:** XAMPP / WAMP / MAMP / LAMP (any one)

## Modules

### User Module
- Anyone can read the news
- Users can search for specific news

### Admin Module
- Secure admin login system
- Admin dashboard

#### Category Management
- Add, update, delete categories
- Restore deleted categories

#### Sub-Category Management
- Add, update, delete sub-categories
- Restore deleted sub-categories

#### Post Management
- Add, update, delete news posts
- View and restore deleted news posts in the trash section

#### Page Management
- Manage content of 'About Us' and 'Contact Us' pages

## How to Run NewsPortal Project

1. Download the zip file
2. Extract the file and copy the `newsportal` folder
3. Paste the `newsportal` folder inside the root directory:
   - For XAMPP: `xamp/htdocs`
4. Open phpMyAdmin [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
5. Create a database with the name `newsportal`
6. Import the `newsportal.sql` file (located inside the zip package in the `sql` file folder)
7. Run the script:
   - Frontend: [http://localhost/newsportal](http://localhost/newsportal)
   - Admin panel: [http://localhost/newsportal/admin](http://localhost/newsportal/admin)

