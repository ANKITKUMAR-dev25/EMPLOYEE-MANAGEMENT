 👥 EMPLOYEE MANAGEMENT SYSTEM

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
       git clone :- https://github.com/ANKITKUMAR-dev25/EMPLOYEE-MANAGEMENT.git

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
    String user = "techcoder";
    String password = "123456789";
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

    🖥️ Front Page

![Screenshot (957)](https://github.com/user-attachments/assets/7cf24f53-16ce-4c41-aac3-079df12d8724)


   🔐 Login Page

![Screenshot (958)](https://github.com/user-attachments/assets/1a079a04-7b30-452c-a99b-669093b08808)

   📊 Dashboard

![Screenshot (959)](https://github.com/user-attachments/assets/002ba560-0183-4047-9607-b04ed4ab9246)

    🧑‍💼 Add Employee

![Screenshot (960)](https://github.com/user-attachments/assets/5c693442-55e2-4e8f-b37a-7d113fa621f5)

   ✏️ Update Employee

![Screenshot (961)](https://github.com/user-attachments/assets/e3083c4a-66b5-48c6-a286-30344d7e0060)

   🗑️ Remove Employee

![Screenshot (963)](https://github.com/user-attachments/assets/56abfef1-fafc-4027-b75d-7abd9451e96b)

🛠️ SQL

![Screenshot (964)](https://github.com/user-attachments/assets/05b11c6d-a4e8-4b99-81ed-576bc6dca97b)





📁 Project Structure

  Employee management system/

  │


  ├── src/                            # Java source code

  ├── out/production/                # Compiled output

  ├── lib/                           # External JARs (not committed — see .gitignore)

  ├── screenshots/                   # Demo images (optional)

  ├── README.md

  ├── .gitignore

  ├── Employee management system.iml

  └── misc.xml, modules.xml, etc. # IDE config files






