
#University Management System with Online Quiz & E-Library
Description
This project is a comprehensive University Management System designed to streamline various administrative tasks within a college or educational institution. In addition to core management functionalities, it includes an integrated online test-taking platform, a digital e-library to enhance the learning experience for students and faculty members & fees & salary management for administrator & attendance section for both faculty & student.

Features
College Management System
Student Management: Manage student records, including admission details, personal information like marks, attendance, online-quiz, fee payment academic history, and many more.
Faculty Management: Keep track of faculty members, their teaching assignments, qualifications, and schedules.
Course Management: Define and manage courses offered by the college, including course materials, syllabi, and schedules.
Attendance Management: Record and monitor student attendance for various classes and sessions.
Examination Management: Schedule exams, manage exam timetables, and record grades and results.
Fees & Salary Management: Handle financial aspects such as fee collection, expense tracking, and total salary report.
result management Allows to manage student's marks of each sem & calculate total CGPA.
Online Test Taking Platform
Test Creation: Create and manage online tests with various question types including multiple choice, true/false, and short answer questions.
Test Scheduling: Schedule tests for specific courses or classes and set time limits for completion.
Student Performance Tracking: Track student performance in online tests, view results, and generate performance reports.
Question Bank: Maintain a repository of questions categorized by subject or topic for easy test creation.
E-Library
Digital Book Repository: Provide access to a wide range of digital books and educational materials.
Search and Browse: Allow users to search for books by title, author, subject, or keyword and browse through available categories.
Reading and Downloading: Enable users to read books online and download them for offline access.
Books for Each sem & Course allows every user to access their preferred reference book which is suggested in syllabus can be accessed for each sem.
Administator mangement
Manage Accounts Manage all the accounts of Student & Faculty & provide access to each one.
Check Attendance: Enable admin to check attendance of user & faculty & also filter them by class/course.
Manage Salary Allow to add,calculate & manage salary & allowance of each & every faculty members in university.
Assign Courses: Enables admin to assign single/multiple subjects to any faculty.
Payment Confirmation: allows admin to send Payment Confirmation or request for their fees.
Manage Timetable:allows to manage all the classes & their schedules for every week
Display result: Displays all the student information for particular class/course & check pass & fail status.
Technologies Used
Frontend: HTML, CSS, Bootstrap Backend: PHP,MySQL
Here's a step-by-step guide on how to set up and run your project using XAMPP:

Step 1: Install XAMPP
Download XAMPP:

Go to the XAMPP website and download the latest version of XAMPP for your operating system (Windows, macOS, Linux).
Install XAMPP:

Run the installer you just downloaded.
Follow the installation steps, and choose the components you want to install (by default, Apache, MySQL, PHP, and phpMyAdmin are selected).
Complete the installation.
Step 2: Start Apache and MySQL Server
Open XAMPP Control Panel:

After installation, launch the XAMPP Control Panel.
You’ll see a list of services. Look for Apache and MySQL.
Start Apache and MySQL:

Click on the "Start" button next to Apache.
Click on the "Start" button next to MySQL.
Make sure both services are running (green indicators).
Step 3: Import the SQL File
Open phpMyAdmin:

Open your web browser and go to http://localhost/phpmyadmin.
This will take you to the phpMyAdmin interface.
Create a New Database:

Click on the "Databases" tab at the top.
Enter a name for your database (e.g., my_database) and click "Create."
Import the .sql File:

After creating the database, select the newly created database from the left sidebar.
Click on the "Import" tab.
Click on "Choose File" and select the .sql file from the database folder of your project.
Click "Go" to import the database. You should see a success message once the import is complete.
Step 4: Load index.php
Move Your Project Files:

Copy your project files (including the index.php file and other project folders) into the htdocs folder inside your XAMPP installation directory (usually located at C:\xampp\htdocs on Windows or /Applications/XAMPP/htdocs on macOS).
Access the Project in Your Browser:

Open your web browser and type http://localhost/your_project_folder_name.
This will load the index.php file, and your project should be up and running.
Step 5: Enjoy!
Explore the functionality of your project as per the instructions. Ensure everything works as expected, and make any necessary adjustments.
Let me know if you need help with any specific part of the process!
