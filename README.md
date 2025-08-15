# 🗂️ Task 7 - Employee Database Management System

## 📌 Task Objective

Develop a **Java CLI application** to manage employee records with **database integration** using JDBC.

## 🛠 Features Implemented
- ➕ **Add Employee** (Name, Department, Salary)
- 📋 **View All Employees** (Fetch from database)
- 🖊️ **Update Employee** details by ID
- 🗑️ **Delete Employee** by ID
- ✅ **Input Validation** for proper data entry

## 🔧 Technologies Used
- **Language:** Java  
- **Database:** MySQL  
- **Libraries:** JDBC (Java Database Connectivity)  
- **Tools:** VS Code / IntelliJ IDEA / Eclipse  

## 🗄 Database Setup
(Run the following SQL commands in MySQL before running the project:)

CREATE DATABASE IF NOT EXISTS employee_db;
USE employee_db;
CREATE TABLE IF NOT EXISTS employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    department VARCHAR(50),
    salary DOUBLE
);

## 🚀 How to Run
1) Compile the projet : javac -cp ".;mysql-connector-java-8.0.xx.jar" *.java
2) Run the projet     : java -cp ".;mysql-connector-java-8.0.xx.jar" MainApp

## 📷 Sample Output
--- Employee Database App ---
1. Add Employee
2. View All Employees
3. Update Employee
4. Delete Employee
5. Exit
Enter choice: 1
Enter Name: Rutuja
Enter Department: IT
Enter Salary: 50000
✅ Employee added successfully!

1) Adding data : <img width="1920" height="1080" alt="Screenshot (369)" src="https://github.com/user-attachments/assets/1b8ada20-211d-4e8d-892c-468bb4aa961f" />
2) Database : <img width="1920" height="1080" alt="Screenshot (370)" src="https://github.com/user-attachments/assets/9deffd4a-87de-4f5b-90b5-b1b1ebe2141f" />

