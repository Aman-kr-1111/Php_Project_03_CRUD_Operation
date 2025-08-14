📝 PHP CRUD Application

This project is a simple CRUD (Create, Read, Update, Delete) system built using PHP and MySQL.
It allows users to Add, View, Update, and Delete records through a clean Bootstrap UI.

---

📂 Project Files
File Name	Description
connect.php ⚡	Connects the project to the MySQL database.
user.php ➕	Handles user registration (Add new user form + insert into DB).
display.php 📋	Displays all user data in a table with Update and Delete options.
update.php ✏️	Updates existing user information in the database.
delete.php ❌	Deletes a user record from the database.

---
⚙️ How It Works

Database Connection 🗄

connect.php connects PHP with MySQL using mysqli.

Add User ➕

user.php provides a form to add Name, Email, Mobile, and Password.
On submit, data is stored in the crud table.

---

Display Users 📋

display.php fetches all users and displays them in a Bootstrap table.
Each row has Update and Delete buttons.

Update User ✏️
update.php loads the selected user’s details into a form.
On submit, it updates the record in the database.

Delete User ❌
delete.php removes a selected record from the database.

--- 

📊 Database Structure

Database Name: crudoperation
Table Name: crud
Column Name	Type	Description
id	INT (Primary Key, Auto Increment)	Unique user ID
name	VARCHAR(100)	User’s name
email	VARCHAR(100)	User’s email
mobile	VARCHAR(20)	User’s mobile number
password	VARCHAR(100)	User’s password

```sql
CREATE TABLE `crud` (
  `id` INT NOT NULL AUTO_INCREMENT PRIMARY KEY,
  `name` VARCHAR(100) NOT NULL,
  `email` VARCHAR(100) NOT NULL,
  `mobile` VARCHAR(20) NOT NULL,
  `password` VARCHAR(100) NOT NULL
);

```
---

🛠 Technologies Used

PHP 🐘 – Backend logic
MySQL 🗄 – Database
Bootstrap 5 🎨 – Styling and responsive design
HTML + CSS 🌐 – Structure and design

---

📚 What You Learn from This Project

✔ How to connect PHP with MySQL using mysqli
✔ How to Insert, Fetch, Update, Delete records
✔ How to pass data between pages using GET and POST
✔ How to create a clean UI using Bootstrap
✔ How CRUD is the foundation for larger web applications

---

🚀 How to Run This Project

Install XAMPP or WAMP.
Start Apache and MySQL.
Create a database named crudoperation.
Run the above CREATE TABLE SQL query.
Place all project files inside the htdocs folder.
Open browser → http://localhost/your-project/display.php.


---

## 📧 Contact
- **LinkedIn**: [Aman Kumar](https://www.linkedin.com/in/aman-kumar-64b22b270/)
- **Portfolio**: [Visit Here](https://aman-first-portfolio.netlify.app/)

---
t by giving this repository a ⭐!
