# Clinic Management System  
**Java Desktop App | NetBeans + MySQL | dotenv Integration**

## 📘 Project Overview

The **Clinic Management System** is a Java desktop application built with Apache NetBeans IDE. It was designed to streamline patient management in a clinic setting, with two account types: **Doctor** and **Receptionist**.  

This project demonstrates:
- GUI development with Java Swing  
- Role-based dashboards (Doctor vs Receptionist)  
- Database integration using MySQL via XAMPP  
- Secure configuration management with `.env` and `dotenv-java`  
- JDBC connectivity using MySQL Connector  

---

## 🛠 Technologies Used

| Component            | Stack/Tool                  |
|----------------------|-----------------------------|
| IDE                  | Apache NetBeans IDE 25      |
| Language             | Java 24 (JDK 24.0.1)        |
| GUI Framework        | Java Swing                  |
| Database             | MySQL (via XAMPP)           |
| Configuration        | `.env` + `dotenv-java.jar`  |
| JDBC Driver          | `mysql-connector-java.jar`  |
| Runtime              | Java SE Runtime Environment |

---

## 🧩 Core Features

### Account Types
- **Receptionist**  
  - Add and remove patients  
  - Manage patient lists  
  - Assign doctors to patients  

- **Doctor**  
  - View assigned patients  
  - Update patient status  
  - Display patient details  

### Functional Modules
- Login and account creation  
- Role-based dashboards (Doctor vs Receptionist)  
- Patient list management with scheduling and status updates  
- Add patient form with details (name, age, gender, date, notes)  
- Status changer (e.g., pending, completed)  

---

## 🚀 Getting Started

clone the project on your desired folder location cd

```bash
git clone https://github.com/JobParado/BiteRide
```



## 🗃 Database Setup

Navigate to folder: Bite Ride\dist\Database xampp netbeans (Setup)

and either use executable commands of mysql database
1 table at a time

Or use it on netbeans recreate table files are provided on the folder 

## ⚙️ Configuration with `.env`

This project uses a `.env` file to store internal configuration values such as admin credentials and database connection strings.

### Example `.env` file:
```
Admin_Name=root
Admin_Password=
Database_URL=jdbc:mysql://localhost:3306/biteride?zeroDateTimeBehavior=CONVERT_TO_NULL
```
Edit the following file (turn this into ( .env) .TXT) based on your credentials and save it as .env


## 🚀 Running the App

1. Open the BiteRide.jar make sure u have jdk libs are already included
2. And the app should be working as usual


---

## 🖼️ Suggested Screenshots for README

| Section | Screenshot |
|---------|------------|
| Login Page | `Clinic System/img/login page.png` |
| Account Creation | `Clinic System/img/create page.png` |
| Doctor Dashboard | `Clinic System/img/doctor homepage.png` |
| Receptionist Dashboard | `Clinic System/img/receptionist hoempage.png` |
| Add Patient Form | `Clinic System/img/receptionist add page.png` |
| `.env` Setup | `Clinic System/img/env setup.png` |

---

## 📚 Learning Outcomes

This project helped me explore:
- GUI design and layout structuring in Java  
- Connecting NetBeans to MySQL using XAMPP  
- Handling user input and form validation  
- Managing role-based workflows (Doctor vs Receptionist)  
- Using `.env` for secure configuration management  
- Structuring readable, maintainable Java code  

---

## 📌 Notes

- This project was built for academic demonstration purposes.  
- Some features may be mockups or partially implemented.  
- The `.env` file must be manually created before running the JAR.  
- Role-based redirection is handled via database role assignment.  
---
