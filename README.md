# ATM-Machine

This repository contains a Java-based simulation of an ATM (Automated Teller Machine) user interface. The project emulates core ATM functionalities such as checking balances, withdrawing cash, and making deposits, with a focus on modularity and the use of design patterns.

Project Structure
ATM.java: Main class that manages the ATM operations and handles interactions with the user.
Account.java: Represents individual user accounts, containing essential attributes like account number, PIN, and balance.
BankDatabase.java: Acts as a simulated database, storing and retrieving account information for transactions.
Transaction Classes:
BalanceInquiry.java: Handles balance inquiry transactions.
Deposit.java: Manages deposit transactions.
Withdrawal.java: Manages withdrawal transactions.
Additional Components
AccountFactory.java: Implements the Factory design pattern to create account objects, allowing for better scalability.
AccountIterator.java: Implements the Iterator design pattern, facilitating easy traversal through account collections.
Design Patterns
This project makes use of various design patterns:

Factory Pattern: Used for creating account objects, providing flexibility in object creation.
Iterator Pattern: Allows for systematic access and traversal of account collections.
Setup and Usage
Clone this repository:
bash
Copy code
git clone https://github.com/KaustubhLabade/ATM_Machine_UI.git
Open the project in your preferred Java IDE (e.g., IntelliJ IDEA).
Compile and run ATM.java to start the ATM simulation.
Requirements
Java Development Kit (JDK) 8 or later
Recommended IDE: IntelliJ IDEA (project includes .idea configuration files)
Features
Balance inquiry
Cash withdrawal
Deposit transactions
Modular and scalable design using object-oriented principles
Future Enhancements
Adding a graphical user interface (GUI)
Implementing additional transaction types
Integration with a real database for persistent storage
License
This project is open-source and available under the MIT License.
