# University-site

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
