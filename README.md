# InternPortal

InternPortal is a web application where mentors assign projects and interns submit their work. It’s simple, fast, and easy to set up locally.

---

## Features
- Mentors can create and assign projects.
- Interns can register, log in, and submit projects.
- User-friendly interface for smooth project management.

---

## Tech Stack
- Frontend: HTML, CSS, JavaScript  
- Backend: PHP  
- Database: MySQL (via XAMPP)  

---

## Setup Instructions

1. **Move the project to XAMPP `htdocs`**:  
   - Locate your XAMPP installation folder (e.g., `C:\xampp\htdocs`)  
   - Copy or move your `internportal` project folder into `htdocs`  
   - Resulting path: `C:\xampp\htdocs\internportal`

2. **Start XAMPP** and turn on **Apache** and **MySQL**.

3. **Create the database**:  
   - Open [phpMyAdmin](http://localhost/phpmyadmin)  
   - Create a new database (e.g., `internportal_db`)  
   - Import the `database.sql` file from the project folder

4. **Update database connection** in your PHP files if needed (`config.php` or similar).

5. **Open the project in a browser**:  
    - http://localhost/internportal




## Usage
1. **Register** as a new user (intern or mentor).  
2. **Log in** to access your dashboard:  
- Mentors: assign and manage projects  
- Interns: view projects and submit work  

---

## Screenshots

![Login Page](Screenshots/login.png)  
![Dashboard](Screenshots/mentor_dashboard.png)(Screenshots/intern_dashboard.png)  
![Project Submission](Screenshots/project_Submission.png)  
