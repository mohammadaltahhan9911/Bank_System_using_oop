# 🏦 Bank System Using OOP

A robust, console-based banking management application built with Object-Oriented Programming principles and a unique binary permission system.

---

## 📖 Overview

Bank System Using OOP is a comprehensive console application designed to simulate core banking operations.  
It demonstrates the practical application of Object-Oriented Programming (OOP) concepts such as:

- Encapsulation  
- Inheritance  
- Abstraction  

The system is designed with security and scalability in mind, featuring a custom-built **Bitwise Permission System** to manage user access levels efficiently.

---

## ✨ Key Features

### 👥 Client Management
- Add New Customer: Create new client accounts with unique IDs.  
- Update Customer: Modify existing client details.  
- Delete Customer: Remove client records safely.  
- View Client List: Display all active clients.  

### 💼 User & Admin Management
- User Management: Create and manage system users.  
- Granular Permissions: Assign specific roles and access rights.  

### 💰 Transactions
- Deposits: Add funds to accounts.  
- Withdrawals: Deduct funds with validation.  
- Total Balances: View total liquidity.  

---

## 🔐 Security Highlight: Binary Permission System

This project uses a **Bitwise Permission System**:

- `1 (001)` → Show List  
- `2 (010)` → Add Client  
- `4 (100)` → Delete Client  

👉 Example:  
User with value `3 (011)` can **Show List + Add Client**

---

## 🛠️ Technical Implementation

- Language: **C++**
- OOP Design: Classes for Clients, Users, Transactions  
- Data Storage: `.txt` files  
- Algorithm: Bitwise operations  

---

## 🚀 Future Roadmap

- 🌐 Web Migration (API + Frontend)  
- 🗄️ Database Integration (SQL)  
- 📜 Transaction History  
- 💡 Interest Calculation  

---

## 🙏 Acknowledgment

Special thanks to **Dr. Mohammed Abu Hadhoud**  
for his guidance and support.

Inspired by: Programmingadvices.com

---

## 📬 Contact

Feel free to reach out for collaboration or questions!
