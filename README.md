🏦 Bank Account Management System (Java + Oracle)
📌 Introduction

The Bank Account Management System is a Java-based console application developed using Object-Oriented Programming (OOP) principles and integrated with an Oracle Database using JDBC.

The project simulates real-time banking operations such as:

Account handling

Deposits

Withdrawals

Balance inquiries

Fund transfers

All operations include proper validations and exception handling.

🎯 Problem Statement

The objective of this project is to design and implement a Bank Account Management System using Java with an object-oriented approach.

✔ System Allows

Creating and managing customer bank accounts

Performing core banking operations:

Deposit

Withdrawal

Balance inquiry

Fund transfer

📊 Maintains Account Details

Account Number

Customer Name

Current Balance

🔒 Validations Implemented

Minimum balance check

Invalid account number detection

⚠ Exception Handling

Insufficient balance

Invalid operations

🧠 OOP Concepts Used

Encapsulation

Inheritance

Polymorphism

🛠️ Technologies Used
Category	Technology
Language	Java
IDE	Eclipse IDE
Database	Oracle 11g
Connectivity	JDBC (Oracle Driver)
Architecture	Layered Architecture

## 📂 Project Structure

```
packagecreationdemo
│
├── src
│   ├── com.wipro.bank.bean
│   │       └── TransferBean.java
│   │
│   ├── com.wipro.bank.dao
│   │       └── BankDAO.java
│   │
│   ├── com.wipro.bank.service
│   │       └── BankService.java
│   │
│   ├── com.wipro.bank.util
│   │       ├── DBUtil.java
│   │       └── InsufficientFundsException.java
│   │
│   └── com.wipro.bank.main
│           └── BankMain.java
│
└── JRE System Library [JavaSE-22]
```

⚙️ How to Run in Eclipse IDE
Step 1 — Install Eclipse

Download from
👉 https://www.eclipse.org/downloads/

Step 2 — Create Project
File → New → Java Project
Project Name: packagecreationdemo

Step 3 — Create Packages inside src
com.wipro.bank.bean
com.wipro.bank.dao
com.wipro.bank.service
com.wipro.bank.util
com.wipro.bank.main

Step 4 — Add Java Classes

Create these files:

TransferBean.java

BankDAO.java

BankService.java

DBUtil.java

InsufficientFundsException.java

BankMain.java

Step 5 — Run Application
Right click → BankMain.java → Run As → Java Application

📸 Output

Add your console output screenshot here:

<img width="1712" height="364" alt="image" src="https://github.com/user-attachments/assets/1ae0c14b-463a-4c5f-8dae-dd2efa4a69a1" />



<img width="1881" height="439" alt="image" src="https://github.com/user-attachments/assets/7edf8d52-37ae-4b94-9d51-b0ef0cd8a95a" />



🔮 Future Scope

GUI integration using JavaFX / Swing

Authentication & security features

Transaction report generation

Multi-branch banking simulation

👩‍💻 Author

Manasha A

Roll No: 717823P228

Project Type: Java & Oracle Database Mini Project
