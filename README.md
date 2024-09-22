Overview
The Banking Management System is a console-based application built in Java, leveraging JDBC for database connectivity and SQL for data storage. This project provides a comprehensive solution for managing banking operations, including account creation, transaction handling, and account inquiries.

Features
Account Creation: Create new bank accounts for customers.
Transaction Handling: Perform deposit, withdrawal, and transfer operations.
Account Inquiries: Check account balance and transaction history.
Admin Functions: Manage customer accounts and view reports.
Technologies Used
Java: Core programming language.
JDBC: Java Database Connectivity for database operations.
MySQL: Database management system.

Database Setup:
Install MySQL and create a database named banking_system.
Run the SQL script schema.sql provided in the repository to create necessary tables.
Configure Database Connection:
Update the DBConnection.java file with your MySQL database credentials.
Java

public class DBConnection {
    private static final String URL = "jdbc:mysql://localhost:3306/banking_system";
    private static final String USER = "yourusername";
    private static final String PASSWORD = "yourpassword";
    // Other connection details
}
Compile and Run:


Usage
Login: Admin logs in using their credentials.
Main Menu: Access various functionalities like account creation, transactions, and reports.
Account Operations: Perform deposit, withdrawal, and transfer operations.
Reports: View account details and transaction history.
