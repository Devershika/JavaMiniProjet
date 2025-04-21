# JavaMiniProjet
Menu-Driven CRUD System using Java & MySQL
A simple yet powerful Java-based CRUD (Create, Read, Update, Delete) system with a role-based login menu for Admin, Faculty, and Students. It uses JDBC (Java Database Connectivity) to interact with a MySQL database. The application demonstrates practical concepts of authentication, database operations, and modular menu-driven programming.

✨ Features
🔐 Login System
Secure login using PreparedStatement to prevent SQL injection.

Role-based access: Admin, Faculty, and Student.

👤 Admin Functionalities
Insert new students

Update student details

View all students

Update faculty usernames

👨‍🏫 Faculty Functionalities
Update marks for students

👨‍🎓 Student Functionalities
View personal academic details (Roll no, Name, Age, Marks)


🛠️ Technologies Used

Tool/Technology	Description
Java	Core language for logic
JDBC	Java-MySQL connectivity
MySQL	Backend relational database
IntelliJ / VS Code / Eclipse	IDE Support


🧩 Database Schema
1. users Table (Login Management)
2. students Table (Student Details)

🚀 How to Run
Setup MySQL Database

Create a database named khushi

Run the SQL queries provided above to create necessary tables.

Insert test data for users to enable login.

Configure JDBC in your IDE

Add MySQL JDBC Driver (mysql-connector-java.jar) to your project libraries.

Run the Java Program

Compile and execute MenuDrivenCRUD.java.

Login using sample credentials


💡 Best Practices Followed
✅ Use of PreparedStatement to prevent SQL injection.

✅ Modular functions for role-based operations.

✅ Readable and maintainable code.

✅ Error handling with try-catch.

📌 Future Enhancements (Suggestions)
Password encryption using SHA-256 or BCrypt.

GUI version using JavaFX or Swing.

Logging system for activity tracking.

Input validation and constraint handling.
