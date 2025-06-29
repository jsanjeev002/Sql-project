# 📚 Online Bookstore SQL Project

This project is a SQL-based mini data analysis system that simulates the working of an online bookstore. It demonstrates SQL table creation, data importing, and various data analysis queries using real-world inspired datasets.

---

## 📁 Files Included

- Books.csv – Dataset containing book details.
- Customers.csv – Dataset containing customer information.
- Orders.csv – Dataset representing book purchase transactions.
– Full SQL script with schema, data import, and solved queries.
– Version with only the questions for practice.

---

## 🗃️ Database Structure

**Database Name:** OnlineBookstore

### Tables:

#### 🟦 Books
| Column         | Type         |
|----------------|--------------|
| Book_ID        | SERIAL (PK)  |
| Title          | VARCHAR(100) |
| Author         | VARCHAR(100) |
| Genre          | VARCHAR(50)  |
| Published_Year | INT          |
| Price          | NUMERIC(10,2)|
| Stock          | INT          |

#### 🟨 Customers
| Column      | Type         |
|-------------|--------------|
| Customer_ID | SERIAL (PK)  |
| Name        | VARCHAR(100) |
| Email       | VARCHAR(100) |
| Phone       | VARCHAR(15)  |
| City        | VARCHAR(50)  |
| Country     | VARCHAR(150) |

#### 🟥 Orders
| Column       | Type         |
|--------------|--------------|
| Order_ID     | SERIAL (PK)  |
| Customer_ID  | INT (FK)     |
| Book_ID      | INT (FK)     |
| Order_Date   | DATE         |
| Quantity     | INT          |
| Total_Amount | NUMERIC(10,2)|

---

## 🔍 Sample Queries Performed

- 📌 List all fiction books.
- 📌 Find books published after 1950.
- 📌 Total stock and total revenue.
- 📌 Most expensive book.
- 📌 Top customers and bestselling books.
- 📌 Cities with high-spending customers.
- 📌 Stock remaining after all orders.
- 📌 Orders placed in a specific month.

Each of these queries helps understand relational operations and aggregation in SQL.

---

## 📚 Skills Practiced

- SQL Joins (INNER, LEFT)
- Aggregation (`SUM()`, `AVG()`, `COUNT()`)
- Filtering and Grouping
- Subqueries and Data Summarization
- CSV Importing
- Business Insight Extraction

---

## 👨‍💻 Author

**Sanjeev Kumar**  
This project was created as part of a practice challenge.

---


