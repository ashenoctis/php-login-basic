php-login-basic
===============
A simple, clean and secure PHP Login Script using MySQL for beginners. Below is a brief description of all PHP files you will find in the download archive:

- **config.php** - This script contains the database connection details. Edit this file to specify your own database's connection details.
- **register-form.php** - A simple registration form
- **register-exec.php** - Handler script for the the above form. This script will create member accounts for you.
- **login-form.php** - Login form
- **login-exec.php** - Handler script for the above login form. This script authenticates the login details and then sets up a session for the user.
- **logout.php** - Script used to logout a user from the session.
- **member-index.php** - Sample password protected page.
- **member-profile.php** - Sample password protected page.
- **auth.php** - Include this script at the top of any page you want to password protect. This script checks whether the user is logged in or not.

## Installation
1. We need an Apache server with PHP Compiler & MySQL database (WAMP or LAMP) to run php code. XAMPP is recommended for this example. Download it from [here](https://www.apachefriends.org/index.html).
2. Install the package. Let's assume that you are on Windows to be specific; Then the installation files will be at "C:\XAMPP".
3. Start "xampp-control.exe" from the folder. Start 'Apache' & 'MySQL'. It will start on ports 80 & 3306 repectively.
4. Copy this folder as "C:\xampp\htdocs\login". Open browser and enter "http://localhost/phpmyadmin" in address bar.
5. Select 'test' database from sidebar. Click on 'Import' tab at top. Under section 'File to Import' click 'Choose File'. Select SQL file from "C:\xampp\htdocs\login\mysql.sql" and push 'Go' at the end of the page.
6. If all goes well then you can see 'Import has been successfully' message. Click on 'test > Structure' there you can now see a table named "members". In Action coloumn click 'Browse'. Now you can see the table data.
7. Now enter "http://localhost/login" in address bar of your browser. Try username 'ashenoctis' and password 'password'. Later you can logout and register your own account with it.

## Notes
- Make sure that you edit the config.php file and change the connections details to match your own environment.
- The script is meant to be a teaching tool for Asxena's PHP newbies and is not meant to be used in production environments.