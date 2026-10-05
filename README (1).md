# Exploring Customer Behavior Through Database Analysis

## Project Overview

This project uses **MS-SQL Server** to explore customer behavior for an online food ordering platform.

The analysis focuses on:

- Sales revenue
- Product performance
- Customer spending
- Customer visit frequency
- Favorite products
- Year-wise sales trends
- Gold membership behavior

## Problem Statement

The project analyzes customer visits, spending and favorite menu items to understand customer behavior and support data-driven business decisions.

## Objectives

1. Analyze sales revenue by product.
2. Find top products by revenue.
3. Analyze customer spending and visit frequency.
4. Identify first orders and popular products.
5. Analyze Gold membership behavior.
6. Analyze yearly sales trends.
7. Generate actionable business insights.

## Database

**Database Name:** `OnlineFoodDelivery`

### Tables

| Table | Purpose |
|---|---|
| Sales | Stores sales transactions |
| Product | Stores product details and price |
| User_name | Stores customer names |
| Users | Stores customer signup information |
| Goldusers_Signup | Stores Gold membership information |

## SQL Analysis

The project contains 20 SQL analysis questions covering:

1. Total sales revenue per product
2. Top 3 products by sales revenue
3. Gold membership users
4. Revenue from Gold users
5. Total Gold-user revenue
6. Gold membership duration
7. Popular product among Gold users
8. Year-wise sales revenue
9. Revenue change over years
10. Average time to Gold signup
11. Orders by Gold members
12. Customer spending
13. Customer visit frequency
14. First order by customer
15. Most purchased item
16. Most popular item for each customer
17. First item after Gold signup
18. Item before Gold signup
19. Orders and amount before Gold signup
20. Transaction ranking while Gold

## Methodology

- Database and tables were created in MS-SQL Server.
- Available project data was inserted into the tables.
- JOINs were used to combine related tables.
- GROUP BY and aggregate functions were used for summaries.
- CTEs and Window Functions were used for advanced analysis.
- Date functions were used for time-based analysis.

## SQL Concepts Used

- SELECT
- JOIN
- GROUP BY
- COUNT()
- SUM()
- MIN()
- YEAR()
- DATEDIFF()
- CTE
- RANK()
- ROW_NUMBER()
- LAG()
- TOP

## Key Insights

- Product revenue can be compared to identify stronger-performing products.
- Customer spending helps identify higher-value customers.
- Visit frequency helps measure customer engagement.
- Popular products can support menu and promotion decisions.
- Year-wise revenue helps understand sales trends.
- Gold membership analysis can help evaluate loyalty-program behavior.

## Recommendations

- Promote stronger-performing products.
- Retain high-value customers.
- Use visit frequency for customer engagement.
- Use popular-product data for marketing and menu planning.
- Evaluate the Gold membership program using complete Gold-user data.
- Use sales trends for business planning.

## Tools & Technologies

- MS-SQL Server
- SQL
- Relational Database
- CTE
- Window Functions

## Project Limitation

The project material states that there are 62 Sales records and 5 Gold members, but complete readable Gold membership records were not available in the supplied material used for this implementation. Therefore, Gold-membership results requiring those missing records should not be treated as complete numerical findings.

## Conclusion

This project demonstrates how SQL and MS-SQL Server can be used to convert customer and transaction data into useful business insights. The analysis supports understanding of customer spending, visits, products, sales trends and loyalty-program behavior.

## Author

**Vaishnavi Patil**
