# Student Management System using python and MYSQL

## 🚀 Project Overview

A fully functional **Student Management System** built with **Python** and **MySQL**, demonstrating complete CRUD operations and professional backend architecture. This project simulates real-world backend development with clean modular design, secure database integration, and scalable structure.

---

## 🎯 Key Features

- Add new student records
- View all student records (sorted by name)
-  Search student by ID
-  Update student details
-  Delete student records
-  MySQL database integration
-  Fully modular and clean code structure
-  Secure parameterized queries (Prevents SQL Injection)

---

## 🛠 Tech Stack

| Technology | Usage |
|------------|--------|
| **Python 3** | Application logic & backend |
| **MySQL** | Database management system |
| **mysql-connector-python** | Python MySQL integration |

---

##  Project Folder Structure

- database.py  (MySQL connection & table creation)
- models.py  (Student model definition)
- student_manager.py  (CRUD operations)
- main.py  (Console-based user interface)
- requirements.txt  (Python dependencies)
- README.md  (Documentation)
- .gitignore  (Git ignore rules)




##  Setup Instructions

### 1️⃣ Clone the Repository
    git clone https://github.com/Akash3710/Student-Management-System
    cd Student-Management-System

### 2️⃣ Install Python Dependencies
    pip install -r requirements.txt

### 3️⃣ Setup MySQL Database
    Ensure MySQL Server is installed and running on your system.

    Login to MySQL:
        mysql -u root -p

    Create the database:
        CREATE DATABASE student_db;
        (Optional: You can skip this if your database.py creates DB automatically.)

### 4️⃣ Configure MySQL Credentials

    Open database.py and update your MySQL credentials:
        HOST = "localhost"
        USER = "root"
        PASSWORD = "your_mysql_password"
        DATABASE = "campusx"

### 5️⃣ Run the Application
    python main.py

## 🧠 Concepts Demonstrated
✅ Modular architecture (separation of layers)

✅ Relational Database Design (MySQL)

✅ Secure SQL queries (parameterized queries)

✅ Exception handling & input validation

✅ OOP (Object-Oriented Programming)

✅ Scalable backend design
