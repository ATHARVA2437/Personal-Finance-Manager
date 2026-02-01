# 🏦 Personal Finance Management System

## 📌 Overview  
A **Java-based console application** designed to help users manage personal finances by tracking income and expenses, setting category-wise budgets, and monitoring savings goals. The system focuses on **modular design, clean code structure, and practical financial workflows**.

---

## ✨ Features  

### 💰 Transaction Management  
- Add income and expense transactions  
- Automatically categorize transactions  
- View transaction history with filters  
- Edit and track transaction details  

### 📊 Budget Management  
- Set monthly budgets for different categories  
- Track spending against budget limits  
- Get warnings when approaching budget limits  
- Compare actual spending vs budgeted amounts  

### 📈 Financial Reports & Analytics  
- Monthly and yearly financial reports  
- Category-wise spending breakdown  
- Spending trend analysis  
- Budget vs actual spending comparison  

### 🎯 Savings Goals  
- Create and manage multiple savings goals  
- Monitor progress toward financial targets  
- Calculate required monthly contributions  
- Get goal achievement notifications  

### 💾 Data Persistence  
- Automatic data saving using CSV files  
- Data backup and restore functionality  
- Export transactions to external files  
- Load previous data on application startup  

---

## 🛠️ Technical Stack  
- **Language:** Java 8+  
- **Data Storage:** CSV Files  
- **Architecture:** Object-Oriented Programming (OOP)  
- **Version Control:** Git & GitHub  

---

## 📁 Project Structure  
Personal-Finance-Manager/
├── src/
│ ├── FinanceManager.java # Main application class
│ ├── Transaction.java # Transaction data model
│ ├── Budget.java # Budget management
│ ├── SavingsGoal.java # Savings goals management
│ ├── Category.java # Category management
│ ├── ReportGenerator.java # Financial reports
│ └── DataManager.java # File I/O operations
├── data/ # Data storage directory
├── README.md
├── compile.bat # Windows compilation script
└── compile.sh # Unix/Linux compilation script


---

## 🚀 Getting Started  

### ✅ Prerequisites  
- Java Development Kit (JDK) 8 or higher  
- Command Line / Terminal access  

---

### ▶️ Installation & Running  

### Windows  
**Option 1 (Recommended):**  
Double-click:  
compile.bat


**Option 2 (Manual):**  
```bash
cd Personal-Finance-Manager
javac -d . src/*.java
java src.FinanceManager
Unix / Linux / Mac
Option 1 (Recommended):

./compile.sh
Option 2 (Manual):

cd Personal-Finance-Manager
javac -d . src/*.java
java src.FinanceManager
💡 Usage Examples
➕ Adding a Transaction
Select "Add Transaction" from the main menu

Choose Income or Expense

Enter amount, select category, and add a description

Optionally specify a date (defaults to today)

📊 Setting Up a Budget
Go to "Budget Management"

Select "Set Category Budget"

Choose a category and enter the monthly budget amount

The system automatically tracks spending against this limit

🎯 Creating a Savings Goal
Navigate to "Savings Goals"

Select "Create New Goal"

Enter goal name, target amount, and target date

Track progress by adding savings regularly

📊 Sample Categories
💵 Income Categories
Salary

Freelance

Business

Investments

Gifts

Other Income

🧾 Expense Categories
Food & Dining

Transportation

Shopping

Entertainment

Bills & Utilities

Healthcare

Education

Travel

Insurance

Miscellaneous

🎯 Key Programming Concepts Demonstrated
Object-Oriented Programming: Classes, encapsulation, modular design

Collections Framework: ArrayList, HashMap

File I/O: Reading and writing CSV files with exception handling

Date & Time API: LocalDate, YearMonth usage

Data Validation: Input validation and error handling

Menu-Driven Interface: User interaction design

Data Persistence: CSV-based storage system

📈 Highlights
This project demonstrates:

Real-world financial workflow implementation

Structured application design

Data management and persistence

Error handling and validation

Modular and readable codebase

Practical use of Java collections and file handling

🔧 Future Enhancements
GUI interface using JavaFX / Swing

Database integration (MySQL / PostgreSQL)

Data visualization using charts and graphs

Multi-user authentication system

Mobile application integration

Expense receipt scanning

Investment portfolio tracking

Automated bill reminders
