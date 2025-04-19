# 💸 Console-Based Expense Tracker (Java)

A feature-rich **Java console application** that allows users to track daily expenses, manage budgets, and even convert currencies. This lightweight app uses file storage to **persist data** and offers a user-friendly interface for expense management right from the terminal.

---

## ✨ Features

- 📌 Record expenses with category, amount, and description
- 📊 View expense summaries by category and total
- 💰 Set and view budgets for specific categories
- 🕒 View complete expense history with timestamps
- 💱 Convert currency (USD to other currencies)
- 💾 Save and load data using file I/O (serialization)
- ✅ Input validation and error handling for smooth user experience

---

## 🧰 Technologies Used

- Java (Core)
- Java I/O (`ObjectInputStream`, `ObjectOutputStream`, `FileInputStream`, `FileOutputStream`)
- `SimpleDateFormat`, `Currency`, `NumberFormat` for formatting
- `Map`, `List`, `ArrayList`, `HashMap` for data management

---

## 📁 File Structure

- `ExpenseTracker.java`: Main application logic
- `Expense.java`: Model class for storing individual expense data
- `expenses.txt`: Serialized file storing all recorded expenses
- `budgets.txt`: Serialized file storing category-wise budgets

---

## 📸 Sample Output

```bash
===== Expense Tracker Menu =====
1. Record an expense
2. View expense summary
3. Set budget
4. View budgets
5. View expense history
6. Convert currency
7. Save expenses
8. Load expenses
9. Exit
Enter your choice: 2

Total Spending: $320.50

Category-wise Spending:
Food: $120.00
Travel: $100.50
Groceries: $100.00
```

## ⚙️ How to Run
1.Clone this repository

2.Make sure you have JDK installed (Java 8 or above)

3.Compile the files:

```bash

javac ExpenseTracker.java Expense.java
```
4.Run the program:

```bash

java ExpenseTracker
```
## 📌 Future Enhancements
- Add graphical user interface (GUI) using JavaFX or Swing

- Connect to a MySQL or SQLite database using JDBC

- Export reports to CSV or PDF

- Add monthly/yearly analytics

## 👨‍💻 Author
- Amit Kumar
- 📧 amitk1602info@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/kumaramit02/) | [GitHub](https://github.com/amit-soham-16)

## ⭐️ Show Your Support
If you like this project, give it a ⭐️ on GitHub! Contributions and suggestions are always welcome.

