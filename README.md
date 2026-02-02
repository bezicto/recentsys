# recentsys

Small to Medium Size Library Management System - with selective MARC fields and DDC support.

Requirement: PHP 8.4 / MariaDB 11.8 / Apache 2.4.58
Current Version: 7.0 Internal Beta

1. Open phpMyAdmin and create a database named `recentsys_db`.
2. Create a user and password to access this database. These credentials will be used later during the configuration process.
3. Import `recentsys_db.sql.zip` into the newly created database.
4. Next, extract `recentsys_files.zip` into your Apache working directory.
5. Ensure the path is as follows:  
   - `/var/www/html/recentsys` (if using CentOS/Rocky/Alma)  
   - `C:/xampp/htdocs/recentsys` (if using XAMPP)
6. Make sure the directory structure inside `recentsys` is as follows:
```
recentsys/
├─ site/*
├─ rsc/*
└─ index.php
```
7. Edit `$dbname`, `$dbuser`, and `$dbpass` in `recentsys/site/config.php` according to the settings you created in steps 1 and 2.
8. In this `config.php` file, you may also modify other settings if necessary.
9. Once completed, navigate to:  
`http://localhost/recentsys/index.php`
10. Log in to the Admin Login using the following credentials:  
 - **Username:** admin  
 - **Password:** 1  
 *(Please change this password immediately.)*
