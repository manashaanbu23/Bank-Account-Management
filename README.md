🏦 Bank Account Management System (Java + Oracle)
📌 Introduction
The Bank Account Management System is a Java-based console application developed using Object-Oriented Programming (OOP) principles and integrated with an Oracle Database using JDBC.
The project simulates real-time banking operations such as account handling, deposits, withdrawals, balance inquiries, and fund transfers with appropriate validations and exception handling.

🎯 Problem Statement
The objective of this project is to design and implement a Bank Account Management System using Java with an object-oriented approach.

The system allows:
Creating and managing customer bank accounts
Performing core banking operations:
Deposit
Withdrawal
Balance inquiry
Fund transfer
Maintaining account details such as:
Account Number
Customer Name
Current Balance
Applying validations:
Minimum balance check
Handling invalid account numbers
Handling exceptions:
Insufficient balance
Invalid operations
Displaying transaction updates through a clean console-based interface
Ensuring modular design using OOP concepts:
Encapsulation
Inheritance
Polymorphism
🛠️ Technologies Used
Programming Language: Java
IDE: Eclipse IDE
Database: Oracle 11g
JDBC: Oracle JDBC Driver
Architecture: Layered Architecture
📂 Project Structure
packagecreationdemo │ ├── JRE System Library [JavaSE-22] │ ├── src │ │ │ ├── com.wipro.bank.bean │ │ └── TransferBean.java │ │ │ ├── com.wipro.bank.dao │ │ └── BankDAO.java │ │ │ ├── com.wipro.bank.service │ │ └── BankService.java │ │ │ ├── com.wipro.bank.util │ │ ├── DBUtil.java │ │ └── InsufficientFundsException.java │ │ │ └── com.wipro.bank.main │ └── BankMain.java

⚙️ How to Run in Eclipse IDE
Step 1: Install Eclipse IDE
Download from: https://www.eclipse.org/downloads/

Step 2: Create Java Project

Open Eclipse
Go to File → New → Java Project
Project Name: packagecreationdemo
Click Finish
Step 3: Create Packages
Inside src, create the following packages:

com.wipro.bank.bean
com.wipro.bank.dao
com.wipro.bank.service
com.wipro.bank.util
com.wipro.bank.main
Step 4: Add Java Classes
Create the following files and paste your code:

TransferBean.java
BankDAO.java
BankService.java
DBUtil.java
InsufficientFundsException.java
BankMain.java
Step 5: Run the Application

Navigate to com.wipro.bank.main → BankMain.java
Right-click → Run As → Java Application
📸 Output
Eclipse Console Output
<img width="1712" height="364" alt="image" src="https://github.com/user-attachments/assets/b69b6e94-c101-4d2c-a5a6-841c1c550e4e" />

<img width="1881" height="439" alt="image" src="https://github.com/user-attachments/assets/b6bce341-a71a-4019-95d7-924ef89f174b" />

🔮 Future Scope
Integrate a GUI using JavaFX or Swing
Add authentication and security features
Generate transaction reports
Extend to multi-branch banking simulation
👩‍💻 Author Details
Name: Manasha A
Roll No: 717823P228
Project Type: Java & Oracle Database Mini Project
