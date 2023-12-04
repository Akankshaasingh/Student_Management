# Student_Management
Student Management App
-This is a simple Java application for managing student records using a MySQL database.
The application allows users to perform operations such as adding students, deleting students, and displaying all students.

**Project Structure**
1} Start.java: The main class that contains the user interface for interacting with the application. It provides options to add, delete, display students, and exit the application.

2} CP.java: A utility class responsible for creating a database connection. It uses the JDBC driver to connect to a MySQL database.

3} Student.java: A class representing the Student entity with attributes such as studentId, studentName, studentPhone, and studentCity.

4} StudentDao.java: The data access object (DAO) class that contains methods for interacting with the database. It includes methods for inserting, deleting, and displaying student records.

**How to Run the Application**
1} Database Setup:

-> Make sure you have a MySQL database set up.
-> Update the database connection details in the CP.java file.

2} Compile the Java Files:
->Compile all Java files using a Java compiler.
            (javac Start.java CP.java Student.java StudentDao.java)
            
3} Run the Application:
->Run the Start class to launch the application.
             (java Start)
             
4} Interact with the Application:
->Follow the on-screen prompts to add, delete, or display student records.
->Use option 4 to exit the application.

**Important Note:**
->Ensure that the MySQL JDBC driver is in the classpath.
            (MySQL JDBC Driver: https://dev.mysql.com/downloads/connector/j/)
Author
[Akanksha]
