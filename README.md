 expense-
A Java web application to track personal expenses with user authentication, CRUD operations, category-wise reporting, and CSV export.
 # 💰 Expense Tracker

A full-stack Java web application that helps users manage and monitor their personal expenses efficiently.

## 🚀 Features
- User Registration & Login with session management
- Add, View, Update, and Delete expenses
- Category-wise expense tracking (date, amount, description)
- Monthly expense reports
- Search expenses by filters
- Export expenses to CSV
- Profile management with profile picture upload
- Monthly budget setting per user

## 🛠️ Tech Stack
- **Backend:** Java (Servlet, JSP), Java 17
- **Frontend:** JSP, JSTL, HTML, CSS
- **Database:** MySQL
- **Build Tool:** Maven
- **Server:** Apache Tomcat (WAR deployment)

## 🗄️ Database Setup
1. Run the SQL script located at `sql/expense_db.sql` to create the database and tables.
2. Update DB credentials in the `DB.java` utility file.

## ▶️ How to Run
1. Clone the repository
2. Import as a Maven project in Eclipse/IntelliJ
3. Set up MySQL and run `expense_db.sql`
4. Deploy on Apache Tomcat
5. Access at `http://localhost:8080/ExpenseTracker`
