# 🏥 Hospital Management System (Java + MySQL)

A console-based **Hospital Management System** developed using **Java**, **JDBC**, and **MySQL**. This project demonstrates CRUD operations, database connectivity, and appointment management through a simple command-line interface.

## 🚀 Features

* 👤 Add new patients
* 📋 View all patients
* 👨‍⚕️ View doctor details
* 📅 Book appointments
* ✅ Check doctor availability before booking
* 🔗 MySQL database integration using JDBC
* 🖥️ Interactive menu-driven console application

## 🛠️ Technologies Used

* Java
* JDBC (Java Database Connectivity)
* MySQL
* IntelliJ IDEA
* Git & GitHub

## 📂 Project Structure

```
HospitalManagementSystem/
│── HospitalManagmentSystem.java
│── Patient.java
│── Doctor.java
│── mysql-connector-j.jar
└── README.md
```

## 🗄️ Database

Create a MySQL database named:

```sql
CREATE DATABASE hospital;
```

The project uses the following tables:

* `patients`
* `doctors`
* `appointments`

Update your MySQL credentials in `HospitalManagmentSystem.java`:

```java
private static final String url = "jdbc:mysql://localhost:3306/hospital";
private static final String username = "root";
private static final String password = "YOUR_PASSWORD";
```

## ▶️ How to Run

1. Clone the repository.
2. Open the project in IntelliJ IDEA.
3. Add the MySQL JDBC Connector JAR to the project.
4. Create the required MySQL database and tables.
5. Update your MySQL username and password.
6. Run `HospitalManagmentSystem.java`.

## 📸 Sample Menu

```
===== HOSPITAL MANAGEMENT SYSTEM =====

1. Add Patient
2. View Patients
3. View Doctors
4. Book Appointment
5. Exit
```

## 🎯 Learning Outcomes

* Java Object-Oriented Programming
* JDBC API
* Prepared Statements
* SQL CRUD Operations
* MySQL Database Design
* Exception Handling
* Git & GitHub Workflow

## 🌱 Future Improvements

* Update and delete patient records
* Search patient by ID or name
* Doctor management (Add, Update, Delete)
* Appointment cancellation
* User authentication (Admin Login)
* GUI using Java Swing or JavaFX
* Spring Boot REST API version
* Export reports to PDF

## 👨‍💻 Author

**Manthan Nayak**

If you found this project helpful, feel free to ⭐ the repository and share your feedback.
