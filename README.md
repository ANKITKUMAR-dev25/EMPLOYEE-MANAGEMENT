👥 Employee Management System
This Java-based desktop application allows you to manage employee data with features like adding, editing, deleting, and viewing records. It connects to a MySQL database and uses external libraries for enhanced functionality like calendars and XML export.

✅ Features
Add, edit, and delete employee records

Search functionality

Date selection via calendar widget

Export results to XML format

Persistent data storage using MySQL

🚀 How to Set Up and Run
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/employee-management-system.git
cd employee-management-system
2. Import into IntelliJ IDEA / Eclipse
Open as a Java project.

If using IntelliJ: File → Open → select the .iml file.

3. Add External Libraries
Place the following JAR files in a lib/ folder and add them to your project's classpath:

jcalendar-tz-1.3.3-4.jar

mysql-connector-j-9.3.0.jar

ResultSet2xml.jar (provide source if it's a custom or public lib)

4. Set Up MySQL Database
Create a new database (e.g., employee_db)

Import any .sql schema files if provided in /db

Update DB connection details in your source code:

java
Copy
Edit
String url = "jdbc:mysql://localhost:3306/employee_db";
String user = "your-username";
String password = "your-password";
5. Run the Project
Run the Main class from your IDE. The GUI should open, allowing you to interact with the employee records.

⚙️ Dependencies
Java 8 or later

MySQL Server

External Libraries:

jcalendar-tz-1.3.3-4

mysql-connector-j-9.3.0

ResultSet2xml

📸 Screenshots
Place images in a screenshots/ folder and reference them here:

Login Page	Dashboard

📁 Project Structure
pgsql
Copy
Edit
Employee management system/
│
├── src/                         # Java source code
├── out/production/              # Compiled output
├── lib/                         # External JARs (not committed — see .gitignore)
├── screenshots/                 # Demo images (optional)
├── README.md
├── .gitignore
├── Employee management system.iml
└── misc.xml, modules.xml, etc. # IDE config files
