# ATM Simulation Application

This project is a simple ATM simulation application built using Java. 
The application allows users to perform basic banking operations such as withdrawing money, depositing money, and checking their account balance.

## Features

- **Withdraw Money:** Allows the user to withdraw money from their bank account.
- **Deposit Money:** Enables the user to deposit money into their bank account.
- **Check Balance:** Displays the current balance of the user's bank account.
- **User Input Validation:** Ensures that users cannot withdraw more money than they have in their account and checks for other input errors.
- **User Feedback:** Provides clear messages to the user based on the outcome of their transactions.

## Classes

### 1. `ATM`
This class represents the ATM machine and provides methods for withdrawing money, depositing money, and checking the balance.

- `withdraw(double amount)`: Withdraws a specified amount from the user's account.
- `deposit(double amount)`: Deposits a specified amount into the user's account.
- `checkBalance()`: Returns the current balance of the user's account.

### 2. `BankAccount`
This class represents a user's bank account and stores the account balance.

- `balance`: A variable that stores the current balance of the account.
- `deposit(double amount)`: Adds a specified amount to the account balance.
- `withdraw(double amount)`: Subtracts a specified amount from the account balance.

# Getting Started

## Prerequisites

- Java Development Kit (JDK) installed
- A Java IDE or a simple text editor
# Running The File

- Compile the Java file: ```javac ATM.java```
- Run the file: ```java ATM```

# Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.

# Author
Your Vijay Patel
- Feel free to edit the content according to your specific project details and preferences. 
