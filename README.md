# Kidicode LMS

##  Project Overview
Kidicode LMS (Learning Management System) is a web-based platform designed to help students learn programming and digital skills through interactive courses. It provides user authentication, course management, and an admin panel for managing users and courses.  
The system is built using **PHP, MySQL, Bootstrap, and Font Awesome** to ensure simplicity, responsiveness, and scalability.

---

##  Setup Instructions
1. **Clone the project** or download the files to your server (e.g., XAMPP `htdocs` folder).
2. **Create a MySQL Database** (e.g., `kidicode_lms`).
3. Import the provided SQL schema (if available) into your database.
4. Update `db.php` with your database credentials:
   ```php
   $host = "localhost";
   $user = "root";
   $pass = "";
   $dbname = "kidicode_lms";
   $conn = new mysqli($host, $user, $pass, $dbname);


Implemented Features

User Authentication

Registration and Login system with session handling.

Logout functionality.

Admin Dashboard

Sidebar navigation with options for user and course management.

Analytics section with stats on users, courses, and students.

User management table with delete option.

Courses Page

Course cards with details (title, description, difficulty level).

Enroll button for each course (future DB integration planned).

Responsive layout using Bootstrap.

Navigation

Consistent navbar with Logout option.

Footer with branding.

Reflection on Learning

Through this project, I learned:

How to structure a PHP + MySQL web application with sessions and role-based access.

The importance of separating pages for admin, user, and public functionalities.

Bootstrap utilities for creating responsive and professional UI quickly.

Implementing a secure login/logout mechanism and user session handling.

Practical experience in integrating frontend (Bootstrap + FontAwesome) with backend (PHP + MySQL).

Planned Future Work

Course Enrollment System

Save enrolled courses into a database.

Student dashboard for viewing enrolled courses.

Role Management

Separate dashboards for Admin, Instructor, and Student.

Advanced Analytics

Visual charts for course popularity, user activity, and completion rates.

Content Management

Add lessons, quizzes, and progress tracking to each course.

Enhanced Security

Use prepared statements everywhere and password hashing for strong protection.