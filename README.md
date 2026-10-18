## GitHub Repository

Source code: https://github.com/ST10445475/devolt-electricians

## Technologies

- HTML5
- CSS3
- JavaScript
- PHP
- MySQL
A responsive PHP website for Devolt Electricians, with service information, quote requests, contact messages, client registration/login, bookings, and a client dashboard. The interface uses HTML, CSS, and JavaScript; PHP and MySQL handle server-side forms and account data.

## Features

- Home, services, about, and contact pages
- Quote requests with optional job-image upload
- Client registration, login, logout, and password-reset flow
- Appointment booking and client dashboard
- Responsive navigation and scroll-reveal effects

## Requirements

- PHP 8.0 or newer with mysqli and fileinfo enabled
- MySQL 
- A local PHP server such as XAMPP, or a PHP-capable hosting provider

## Run locally with XAMPP

1. Install and start *Apache* and *MySQL* in the XAMPP Control Panel.
2. Copy the devolt project folder into XAMPP's htdocs directory.
3. Open phpMyAdmin at http://localhost/phpmyadmin.
4. Create a database named devolt_db using utf8mb4 if possible.
5. Select the database, choose *Import*, and import database/schema.sql. This file creates empty tables; it deliberately contains no customer records.
6. Check db_connect.php. The included defaults (localhost, user root, blank password) are typical for a fresh local XAMPP installation only. Change these values to match your local database or hosting provider. Do not commit production credentials.
7. Visit http://localhost/devolt/ in your browser.
