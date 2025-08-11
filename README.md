# SQL Sales & Customer Analytics Project

## 📌 Project Overview
This project demonstrates **SQL queries** to analyze sales, customers, products, employees, and revenue data from a sample database (similar to **AdventureWorks**).  
It covers **data retrieval, filtering, aggregation, joins, and reporting** to solve various real-world business problems.

---

## 🎯 Objectives
- Retrieve customer and product data based on specific conditions.
- Identify top customers, best-selling products, and country-wise sales.
- Perform revenue analysis and order tracking.
- Explore employee-manager relationships and workforce structure.
- Filter products and customers using different SQL operators.

---

## 📂 Database Used
The project uses a **sample sales database** with the following key tables:
- **Sales.Customer**
- **Sales.Store**
- **Sales.SalesOrderHeader**
- **Sales.SalesOrderDetail**
- **Production.Product**
- **Production.ProductModel**
- **HumanResources.Employee**
- **Person.Person**
- **Person.Address**
- **Purchasing.Vendor**

---

## 🛠 SQL Concepts Covered
- `SELECT`, `WHERE`, `ORDER BY`, `DISTINCT`
- `LIKE`, `IN`, `BETWEEN`
- `JOIN` (INNER, LEFT)
- `GROUP BY`, `HAVING`
- Aggregate functions: `SUM`, `COUNT`, `AVG`, `MIN`, `MAX`
- Subqueries

---

## 📜 Query Highlights
| Query No. | Description |
|-----------|-------------|
| 1 | List of all customers |
| 2 | Customers with company name ending in 'N' |
| 3 | Customers from Berlin or London |
| 7 | Customers who never placed an order |
| 10 | Customers who ordered "Tofu" |
| 16 | Orders with total quantity > 300 |
| 20 | Country-wise sales report |
| 29 | Orders placed by best customer |
| 36 | Top 10 countries by sales |
| 39 | Product revenue analysis |
| 42 | Total company revenue |

---

## 🚀 How to Run
1. Open SQL Server Management Studio (SSMS) or any SQL query tool.
2. Restore/load the **AdventureWorks** sample database (or similar schema).
3. Run the queries in `queries.sql` file sequentially.
4. Review results in the output pane.

---

## 📊 Expected Output Examples
- **Customer Reports** → Names, locations, order history.
- **Product Reports** → Best-sellers, discontinued products, low stock items.
- **Sales Analysis** → Total sales, revenue by country, top customers.
- **Employee Reports** → Managers and their reporting staff.

---

## 📄 License
This project is for **educational purposes** and can be reused or modified for learning SQL.

