# 💰 Expense Calculator App (Java Console Project)

This is a simple **Expense Calculator** built using **Java OOP concepts**. It allows users to add, view, and calculate total expenses through a console-based menu. The project demonstrates the use of **abstraction, inheritance, encapsulation**, and basic object-oriented programming techniques.

---

## 🔧 Features

- 👤 User registration with automatic user ID generation.
- ➕ Add expenses (up to 10).
- 📋 View all recorded expenses.
- 💵 Calculate the total amount spent.
- 📦 Uses Java interface, inheritance, and encapsulation principles.

---

## 🧱 OOP Concepts Used

- **Abstraction**: Implemented using the `ExpenseOperations` interface.
- **Inheritance**: `Expense` class inherits from the `User` class.
- **Encapsulation**: Expense details (category, amount, date) are encapsulated within the `ExpenseItem` class.

---

## 📂 Project Structure

```plaintext
ExpenseCalculatorApp.java
This single file contains:

ExpenseOperations – Interface for abstraction.

User – Parent class.

ExpenseItem – Encapsulates individual expense data.

Expense – Child class implementing the interface and inheriting from User.

ExpenseCalculatorApp – Main class with menu-driven console logic.

🚀 How to Run
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/expense-calculator-app.git
Compile the Code

bash
Copy
Edit
javac ExpenseCalculatorApp.java
Run the Program

bash
Copy
Edit
java ExpenseCalculatorApp
🧪 Sample Output
pgsql
Copy
Edit
Welcome to Expense Calculator!
Enter your name: Anshu 

--- User Info ---
Name: Anshu
User ID: 1

---- Menu ----
1. Add Expense
2. View Expenses
3. Calculate Total
4. Exit
⚠️ Limitations
Maximum of 10 expenses can be added (for simplicity).

No file or database storage (data is not saved after program exit).

🏗️ Possible Improvements
Replace hardcoded expense slots with dynamic arrays or collections.

Add file/database support for storing expense history.

Add category-based reports and filtering.

GUI version using JavaFX or Swing.

👨‍💻 Author
Anjani

