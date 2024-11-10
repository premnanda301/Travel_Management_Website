To update the `README.md` with a GitHub repository link instead of a zip file, simply replace the download instructions with a command to clone the repository from GitHub. Here’s the revised `README.md`:

```markdown
# Tourism Management System (TMS)

Tourism Management System (TMS) is a PHP-based project developed by Anuj Kumar. This system allows users to book tours, manage bookings, and manage inquiries. It has three main user roles: Admin, Users, and Guest users.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
  - [Admin](#admin)
  - [Users](#users)
  - [Guest Users](#guest-users)
- [Project Demo](#project-demo)
- [Installation Guide](#installation-guide)
- [Database Configuration](#database-configuration)
- [Login Details](#login-details)

---

## Project Overview
- **Project Name**: Tourism Management System - TMS
- **Language Used**: PHP (compatible with PHP 5.6 and PHP 7.x)
- **Database**: MySQL 5.x
- **User Interface**: HTML, AJAX, jQuery, JavaScript
- **Supported Browsers**: Mozilla Firefox, Google Chrome, Internet Explorer 8+, Opera
- **Software Requirements**: XAMPP, WAMP, MAMP, or LAMP
- **Last Updated**: 04 Feb 2024

## Features

### Admin
- Create and manage packages (add, update)
- Manage users and their inquiries
- Handle user issues and manage bookings
- Control website pages
- Secure account with password change functionality
- Access to an Admin Dashboard

### Users
- Register and log in with a valid email and password
- Reset password if forgotten
- Book and manage tour bookings
- Generate and manage complaints regarding bookings
- Secure account with password change functionality

### Guest Users
- Browse the website and view available packages
- Submit inquiries

## Project Demo
The project includes several key pages:
- **Home Page**: Main landing page for the website.
- **User Signup/Registration**: Register as a new user.
- **Tour History**: View a record of booked tours.
- **Admin Dashboard**: Overview and management dashboard for admins.
- **Create Package**: Page for admins to add a new package.

## Installation Guide
1. **Clone the repository** to your local system:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```
   Replace `https://github.com/username/repository-name.git` with the actual URL of your GitHub repository.
   
2. Move into the project directory:
   ```bash
   cd repository-name
   ```
   
3. Copy the `tms` folder to your server’s root directory:
   - For XAMPP: `xampp/htdocs`
   - For WAMP: `wamp/www`
   - For LAMP: `var/www/html`

### Database Configuration
1. Open **PHPMyAdmin**.
2. Create a new database named `tms`.
3. Import the `tms.sql` file (available inside the project’s `database` folder).

### Running the Project
1. Open your browser and navigate to: `http://localhost/tms`
2. For Admin access: `http://localhost/tms/admin`

## Login Details

### Admin
- **Username**: `admin`
- **Password**: `Test@123`

### User
- **Username**: `test@gmail.com`
- **Password**: `Test@123`

---

## Technologies Used
- PHP
- MySQL
- HTML, CSS, JavaScript (AJAX, jQuery)

## License
This project is licensed under the MIT License.

---

## Author
Developed by Prem Nanda
```
