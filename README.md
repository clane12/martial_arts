🥗 Martial_arts - A Health and Fitness Platform
Martial_arts is a PHP-based web platform designed to promote healthy living through nutrition advice, self-defense tutorials, training programs, and an easy-to-use contact system. Users can sign up to explore various resources, reach out through the contact form, and get started on their wellness journey.

🔗 Table of Contents
Features

Pages & Descriptions

Technologies Used

Installation

Database

Contributing

License

✅ Features
User signup functionality

Nutrition guidance

Self-defense techniques

Training plans and resources

Contact form with email and database logging

Modular and easy-to-understand PHP pages

📄 Pages & Descriptions
File	Description
home.php	Landing page of the website with introduction and navigation
signup.php	Allows users to create an account
nutri.php	Displays nutrition-related tips and information
self-def.php	Self-defense resources for personal safety
Training.php	Fitness training plans and physical activities
aboutus.php	Information about the creators or organization behind the platform
contact.php	User-facing contact form
mail.html	Processes contact form submissions and stores them in the MySQL database
f_t.php	Additional content (likely for fitness or tutorials)
debug.log	Debug file capturing system errors or logs

🛠️ Technologies Used
PHP (Backend)

HTML/CSS (Frontend)

MySQL (Database)

XAMPP/WAMP or any local LAMP stack

🧰 Installation
Clone the repository

git clone https://github.com/your-username/fitlife.git
cd fitlife
Set up your local server (e.g., XAMPP)

Place the project folder inside htdocs.

Start Apache and MySQL

Use XAMPP/WAMP control panel.

Import the Database

Create a database named html in phpMyAdmin.

Create a table called contact with columns:

id (INT, AUTO_INCREMENT, PRIMARY KEY)

name (VARCHAR)

email (VARCHAR)

subject (VARCHAR)

message (TEXT)

Navigate to your browser

http://localhost/fitlife/home.php
🗃️ Database
The contact form stores user-submitted details in the contact table.

Example SQL:

CREATE TABLE contact (
  id INT(6) UNSIGNED AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  email VARCHAR(255) NOT NULL,
  subject VARCHAR(255),
  message TEXT
);

🤝 Contributing
Contributions are welcome! If you have suggestions for improvement or new features, feel free to fork the repo and submit a pull request.
