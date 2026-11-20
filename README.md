# Food Delivery Customer Analysis Using MySQL

## About the Project

For this project, I worked with a food delivery dataset to explore customer behaviour and understand what happens after a customer places their first order.

Rather than just practising SQL queries, I wanted to use the data to answer some business-related questions.

I focused on customer acquisition, repeat orders, retention, and promotional codes to identify patterns that could help a food delivery business better understand its customers.

## Business Questions

- How many orders were delivered and cancelled?
- How many unique customers placed orders?
- How many customers made repeat purchases?
- Which months brought in the most new customers?
- How many January customers returned in February and March?
- Did customers who used promotional codes on their first order return more often?

## Tools & SQL Concepts

**Tool:** MySQL

**SQL concepts used:**
- Common Table Expressions (CTEs)
- Joins and Self Joins
- Aggregate Functions
- GROUP BY and HAVING
- Subqueries
- Window Functions (ROW_NUMBER)
- Date Functions
- COUNT and DISTINCT

## Key Findings

- Analysed 73 orders from 47 unique customers.
- 72 orders were delivered and 1 was cancelled.
- 35 customers placed only one order, while 12 placed repeat orders.
- January had the highest number of new customers (41), followed by February (4) and March (2).
- Out of 41 customers acquired in January, only 6 returned at least once during February or March.
- Customers using FIRSTORDER and NEWUSER promotions had an observed return rate of 18.18%, compared with 5.56% for customers who did not use a promotion.

## What the Data Tells Us

Most customers in this dataset placed only one order, which suggests there may be an opportunity to improve repeat purchases.

The promotional-code analysis also showed higher return rates among customers who used FIRSTORDER and NEWUSER codes. However, this does not establish that the promotions caused customers to return.

## Limitations

The dataset covers only three months and contains a relatively small number of orders. It also does not include order value, revenue, delivery time, or marketing costs.

The findings should therefore be treated as observations from this dataset rather than conclusions about the wider food delivery industry.

## Conclusion

This project gave me an opportunity to apply SQL to a practical business scenario, connect different SQL concepts, and translate query results into meaningful business observations.
