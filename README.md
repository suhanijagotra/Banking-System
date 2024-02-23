# Banking-System
This is a Banking System project using C++
<br>
Author - suhani jagotra 

This project implements a simple banking system using C++. Here's a breakdown of its components:

1. **Classes:**
   - `Account`: Represents a bank account with attributes like account number, first name, last name, and balance. It includes methods for depositing, withdrawing, and getting account information.
   - `Bank`: Manages a collection of accounts using a map data structure. It includes methods for opening an account, checking balance, depositing, withdrawing, closing an account, and showing all accounts.

2. **Exception Handling:**
   - `InsufficientFunds`: An exception class thrown when a withdrawal would result in a balance below the minimum allowed balance.

3. **File Handling:**
   - The program reads and writes account information to a file named "Bank.data" using file streams. This allows the program to persist account data between different runs.

4. **Main Functionality:**
   - The main function presents a menu-driven interface for interacting with the banking system.
   - Users can open accounts, check balances, deposit and withdraw funds, close accounts, and view all existing accounts.

5. **Data Persistence:**
   - When the program starts, it reads existing account data from the "Bank.data" file into memory.
   - When the program ends, it writes the updated account data back to the file, ensuring that changes are saved for future sessions.

Overall, this project provides a basic implementation of a banking system, demonstrating concepts such as object-oriented programming, exception handling, file handling, and data persistence in C++.
