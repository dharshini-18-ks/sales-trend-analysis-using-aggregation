# sales-trend-analysis-using-aggregation
Task 6: Sales Trend using Aggregation

The analysis is performed using a single SQL query that leverages the following concepts:
1. ​EXTRACT(MONTH FROM order_date): To isolate the month from the full date.
​2. SUM(amount): An aggregate function to calculate total revenue.
​3. COUNT(DISTINCT order_id): An aggregate function to count the number of unique orders.
​4. GROUP BY: To group the data by month, allowing for separate calculations for each period.
​5. ORDER BY: To sort the final results chronologically.
