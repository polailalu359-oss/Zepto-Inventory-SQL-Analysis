# Zepto Inventory SQL Analysis



![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?logo=postgresql&logoColor=white)




![SQL](https://img.shields.io/badge/SQL-Analysis-orange)




![Status](https://img.shields.io/badge/Status-Completed-brightgreen)



End-to-end SQL analysis of Zepto grocery inventory data using PostgreSQL. The project covers data exploration, data cleaning, and business insight queries on pricing, discounts, stock, and revenue.

## Table of Contents

1. [Project Goal](#project-goal)
2. [Dataset](#dataset)
3. [Tools Used](#tools-used)
4. [Project Workflow](#project-workflow)
5. [Business Questions Answered](#business-questions-answered)
6. [Key SQL Concepts](#key-sql-concepts)
7. [How to Run](#how-to-run)
8. [Repository Structure](#repository-structure)
9. [Key Learnings](#key-learnings)
10. [Contact](#contact)

## Project Goal

Turn raw product data into clear business insights using SQL only, the way a data analyst works with a real inventory database.

## Dataset

- **File:** `zepto_v2.csv`
- **Columns:** Category, name, mrp, discountPercent, availableQuantity, discountedSellingPrice, weightInGms, outOfStock, quantity

## Tools Used

- PostgreSQL
- pgAdmin
- Git and GitHub

## Project Workflow

1. **Database setup:** create the table and import the CSV.
2. **Data exploration:** row count, sample data, null values, distinct categories, in-stock vs out-of-stock count.
3. **Data cleaning:** remove products with MRP = 0, convert prices from paise to rupees, find duplicate product names.
4. **Business analysis:** answer key business questions with SQL queries.

## Business Questions Answered

1. Which are the top 10 best-value products by discount percentage?
2. Which high-MRP products are out of stock?
3. What is the estimated revenue for each category?
4. Which products have MRP above Rs. 500 and a low discount?
5. Which top 5 categories offer the highest average discount?
6. What is the price per gram for each product?
7. How can products be grouped into Low, Medium, and Bulk by weight?
8. What is the total inventory weight per category?

## Key SQL Concepts

- SELECT, WHERE, GROUP BY, ORDER BY, LIMIT
- Aggregate functions: COUNT, SUM, AVG, ROUND
- CASE WHEN for categorization
- DISTINCT and duplicate detection
- Data cleaning with UPDATE and DELETE

## How to Run

1. Install PostgreSQL and pgAdmin.
2. Create a new database.
3. Run the table creation query from `Zepto-SQL-Project.sql`.
4. Import `zepto_v2.csv` into the table.
5. Run the remaining queries one by one.

## Repository Structure

```
Zepto-Inventory-SQL-Analysis/
├── zepto_v2.csv              # Raw dataset
├── Zepto-SQL-Project.sql     # All SQL queries
└── README.md                 # Project documentation
```

## Key Learnings

- Cleaning messy data before analysis (zero MRP, paise to rupees).
- Writing business-focused queries instead of only practice queries.
- Using CASE WHEN and aggregates to build useful categories and summaries.

## Contact

**Lalu Prasad Polai**
MCA (AI & ML) Student | Aspiring Data Analyst / Data Scientist

- LinkedIn: [linkedin.com/in/laluprasadpolai](https://www.linkedin.com/in/laluprasadpolai)
- GitHub: [polailalu359-oss](https://github.com/polailalu359-oss)
- Email: [polailalu359@gmail.com](mailto:polailalu359@gmail.com)

If you found this project useful, please give it a star.
