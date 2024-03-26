
# Bike Stores Database Analysis Project


## Overview

This project involves analyzing the Bike stores database to gain valuable insights into the company's performance over time. The analysis includes various SQL queries and actions performed on the dataset to answer specific business questions and generate meaningful reports.





## Objectives
- Calculate total revenue by summing up the total price column in the dataset and determine the monthly average number of orders placed per year.
- Identify the top 5 and bottom 5 products based on revenue to focus on high-performing and low-performing items, and assess stock status for products by identifying which products are low in stock or out of stock.
 - Track new customer acquisition by analyzing the number of new customers acquired in the last year and calculate the average spending per customer to understand customer behavior and preferences.
 - Analyze sales trends for products by determining which products have seen significant increases or decreases in sales and identify the 2 most sold products per state.
 - Determine the most selling category and calculate the 7-day moving average to understand short-term sales trends.
- Find the top 10 customers based on their order history.
 - Assess staff performance by determining how many sales each staff member made in the last year and calculating the average order size for each staff member.
 - Segment customers based on region, number of purchases, and total spending to analyze how spending patterns differ across different customer groups.


## Techniques Used
 - Subqueries: Utilized subqueries to retrieve specific data subsets for analysis.
 - Common Table Expressions (CTEs): Used CTEs for calculations such as average spending per customer.
 - Window Functions: Employed window functions like lag and rank to analyze sales trends, identify repeat purchases, and calculate a 7 day moving average
 - Case Statements: Used case statements to categorize products based on their stock status.

## Insights and Recommendations
- The total revenue generated from the 3 stores is $7686188.71.
- On average, 2017 had the highest number of monthly orders placed (57.33), followed closely by 2016, whereas 2018 had the least.
- Trek Slash 8 generated the highest revenue - $555,558.46, followed closely by Trek Conduit. On the other hand, Electra Savannah had the least revenue - $223.99.
- Only 2 new customers were acquired by the company in 2018, where as, on average, each customer had spent $5322.84.
- Top Spenders: Sharyn Hopkins had spent the highest amount of money ($34,807.93), followed by Pamelia Newman ($33,634.24).
- Staff Performance: Venita Daniel had the highest sales ($625,358.01) in 2018, while Marcelene Boyer came in second, and Layla Terrell had the least sales ($56,531.3). Each staff registered an equal number of average order size - 3.
- Most Sold Products by State: Trek Slash 8 was the most sold product in each state. Trek Conduit was the second most sold in CA and NY, while Trek Fuel was the second most sold in TX. Mountain bikes were the most sold category in each state, while Children Bikes were the least sold.
- Single-purchase customers exhibited the highest spending levels, indicating a potential focus area for maximizing revenue from this segment.




