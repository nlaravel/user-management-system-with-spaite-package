# User Management System with Spaite Package

  Laravel project to apply CRUD functionalities on users & role & product.<br>

# Getting Started

1-	Clone or download the repository .
<br>
2-	move into the project directory .
<br>
3-	Install laravel dependencies using composer install .
<br>
4-	Install npm dependencies using npm install .
<br>
5-	Fill all the database information in the ".env" file .
<br>
6-	Generate app encryption key using php artisan key:generate .
<br>
7-	Generate the database tables using php artisan migrate .
<br>
8-	Run php storage:link to connect public folder to storage folder.
<br>
 # Important to access project : 

Generate Admin by run php artisan db:seed
<br>
email: "admin@admin.com"
<br>
password: "123456"
<br>

 Run php artisan serve to show  the project.
 
# Note : 

you can find a demo database in project files called: user-management-system.sql<br>

# Features About The Project

1-	Has Multiple Authentication, Admin Authentication and User Authentication.<br>
2-	There is no registration form for admins, only for users<br>
3-	To generate admin you must run php artisan db:seed<br>
4-	login form is mutual between users and admin but it will direct users to their home page and admins to their admin panel.<br>
5-	Forms has validation.<br>

