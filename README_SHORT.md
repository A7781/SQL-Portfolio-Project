# SQL Portfolio Project – Online Bookstore

## Overview
A SQL-based project for managing an **Online Bookstore**, covering database creation, CSV data import, and 20 practical SQL queries for analyzing books, orders, and customers.

---

## Techniques & Tools
- **Database Design:** `Books`, `Customers`, `Orders` tables with PK & FK relationships.
- **SQL Queries:** `SELECT`, `JOIN`, `GROUP BY`, `ORDER BY`, `SUM`, `AVG`, `COUNT`, `LIMIT`.
- **Data Import:** Bulk data insertion using `COPY` command.
- **Analytics:** Revenue, stock tracking, top customers, and sales insights.

---

## Key Features
- Find books by genre or publication year.
- Calculate total stock and total revenue.
- Identify most expensive and most frequently ordered books.
- Analyze customers (repeat buyers, highest spenders).
- Determine remaining stock after orders.

**Example Query – Most Expensive Book:**
```sql
SELECT * FROM Books
ORDER BY Price DESC
LIMIT 1;
```

---

## Skills Demonstrated
- SQL Development & Database Schema Design.
- Data Analysis & Bulk Data Management.
- Real-world business problem-solving.

---

## Future Enhancements
- Add triggers & stored procedures.
- Build a dashboard (Power BI / Tableau).
- Implement indexing & query optimization.

---

## How to Run
1. Create the database and run `SQL Portfolio Project.sql`.
2. Use `COPY` to import data from CSVs.
3. Run queries to explore insights.

---

## Contact
**Author:** Abhishek Rai  

