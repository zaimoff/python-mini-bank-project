# python-mini-bank-project# Mini Banking System (Python)

A simple and educational Python project that simulates basic banking operations such as account creation, deposits, withdrawals, and transaction tracking.

---

## 🚀 Project Overview

The Mini Banking System allows users to create accounts, manage balances, and view transaction histories. It includes validation to prevent invalid operations (e.g., overdrafts, negative deposits) and stores all data in memory using Python lists and dictionaries.

A built‑in test runner demonstrates example usage and error handling.

---

## 🧩 Features

### ✔️ Account Management
- Create new accounts with an initial balance  
- Prevent duplicate account names  
- Validate that initial balance is non‑negative  

### ✔️ Transactions
- Deposit money into an account  
- Withdraw money with overdraft protection  
- Track all transactions (type + amount)  

### ✔️ Account Summary
- Display current balance  
- Show full transaction history  
- Handle accounts with no transactions  

### ✔️ Exception Handling
- Raises and handles errors for invalid operations  
- Prevents negative or zero‑value transactions  

---

## 📁 Project Structure

├── find_account()
├── create_account()
├── deposit()
├── withdraw()
├── show_account()
└── run_tests()

Code

All logic is contained in a single Python file for clarity and learning purposes.

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
Run the script:

bash
python mini_bank.py
View the output:

Account creation

Deposits and withdrawals

Overdraft error handling

Full account summary

🎯 Learning Objectives
This project helps you practice:

Python programming fundamentals

Working with lists and dictionaries

Writing modular, reusable functions

Implementing validation logic

Using exceptions to handle errors

Designing small console‑based systems

🔮 Future Enhancements
Here are some optional improvements you can build on:

Add account numbers instead of names

Add timestamps to transactions

Export account data to JSON or CSV

Add interest calculation

Build a CLI or GUI interface

Add unit tests using pytest

📜 License
This project is open‑source and available under the MIT License.
