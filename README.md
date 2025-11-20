 
AmbuFinder — Emergency Ambulance Finder App

Overview
AmbuFinder is a web-based application that helps users quickly find and book ambulances in emergencies.
Users can register, log in, search ambulances by type (Normal, Oxygen, ICU), book rides, and provide feedback.
Drivers have their own dashboard to manage bookings. The app ensures safety, real-time updates, and easy access to emergency services.

System Requirements
•	XAMPP (Apache + MySQL)
•	Code Editor: Visual Studio Code (VS Code)
•	Web Browser: Google Chrome or Microsoft Edge

Installation & Setup
Step 1: Extract Project Files
1.	Download the zipped project folder.
2.	Extract it into: C:\xampp\htdocs\
3.	Make sure the folder name is: ambufinder
Step 2: Start Local Server
1.	Open XAMPP Control Panel.
2.	Start Apache and MySQL.
3.	Test database connection:
http://localhost/ambufinder/includes/db_connect.php
Step 3: Run the Application
1.	Open the app in your browser:
http://localhost/ambufinder/home.php
2.	The home page will open.
User Registration & Login
1.	Click Login on the top-right.
2.	For new users, click Sign Up.
3.	Registration page URLs:
o	Login: http://localhost/ambufinder/login.php
o	Sign Up: http://localhost/ambufinder/register.php
4.	Register as a Passenger or Driver.
5.	After successful login, access the dashboard:
http://localhost/ambufinder/index.php

Features
•	Search ambulances by location
•	Filter by ambulance type (Normal, Oxygen, ICU)
•	Directly call an ambulance
•	Language toggle (English/Bangla)
•	Feedback and rating system
•	Responsive and user-friendly interface

Notes
•	Make sure the database is imported if an SQL file is provided.
•	Keep the folder name exactly as ambufinder to prevent broken links.
•	The app is for local use via localhost.
•	VS Code is recommended for editing, debugging, and running PHP files.

