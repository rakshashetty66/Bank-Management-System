# Bank Management System

# Overview
The Bank Management System is a Java-based desktop application designed to manage customer accounts, handle transactions, and perform banking operations such as balance inquiries, deposits, withdrawals, and transaction history management. It features a user-friendly interface and uses MySQL as the database to store customer and transaction data.

# Features
1. User Login System
2. Account Balance Check
3. Money Deposit and Withdrawal
4. Transaction History
5. Account Management

# Technologies Used
1. Java: Core programming language for building the system.
2. MySQL: Database system used to store and retrieve account and transaction data.
3. NetBeans: Integrated Development Environment (IDE) used for writing, testing, and debugging the application.
4. JDK: Java Development Kit required to run the system.

# Prerequisites
Before running the project, ensure you have the following installed:
1. NetBeans IDE
2. MySQL Server
3. Java Development Kit (JDK)

# Setup Instructions
Step 1: Install MySQL Server
Download and install MySQL Server from the official website.
Create a new database called bank_management_system using the MySQL command line or MySQL Workbench.

Step 2: Setup JDK and NetBeans
Download and install the latest version of JDK from the official website.
Set up NetBeans IDE by downloading it from here.
In NetBeans, set the JDK path:
Go to Tools > Java Platforms > Add Platform, and select the JDK folder.

Step 3: Clone the Repository
Clone this GitHub repository to your local machine:
Open the project in NetBeans IDE:
Go to File > Open Project.
Select the cloned folder and open it.

Step 4: Configure Database Connection
Open the file DatabaseConnection.java located in the src folder.
Update the connection string with your MySQL credentials
Ensure the MySQL JDBC driver (mysql-connector-java.jar) is added to your project’s libraries.
Right-click on Libraries in the Project Explorer.
Select Add JAR/Folder and navigate to the location of mysql-connector-java.jar.

Step 5: Run the Application
In NetBeans, right-click on the project and select Run.
The Bank Management System will launch, allowing users to log in, perform transactions, and view their account details.
