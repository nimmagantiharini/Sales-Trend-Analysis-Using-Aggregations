# Sales-Trend-Analysis-Using-Aggregations
Analyze online sales performance by aggregating monthly revenue and order volume using PostgreSQL. The queries help identify trends across specific years, months, or date ranges, enabling better insights for decision-making and business growth.
## Output
- <a href="https://github.com/nimmagantiharini/Sales-Trend-Analysis-Using-Aggregations/blob/main/sql%20sales%20file.pdf"> Output Pdf</a>
## Dataset
Table: sales12

a.order_id (INT, Primary Key)
b.order_date (DATE)
c.amount (DECIMAL)
d.product_id (INT)

## SQL Techniques Used

A.EXTRACT(YEAR/MONTH FROM order_date) → to break down sales by year & month
B.SUM(amount) → to calculate total revenue
C.COUNT(DISTINCT order_id) → to calculate total orders
D.GROUP BY year/month → to aggregate results
E.ORDER BY year/month → to sort results chronologically
F.LIMIT/WHERE → to filter specific time periods

## Insights

 -Peak Sales Months: Because of seasonal demand, some months (like March and November) saw more revenue.
 -Orders against Revenue: In certain months, there were more orders, but the average revenue per order was lower, which may indicate that the tickets were smaller.
 -Consistent Growth: Revenue grew steadily month after month, a sign of a growing business.
 -Low Volume Months: Possibly as a result of low marketing activity or seasonal slowdowns, months such as July had fewer orders.
## Conclusion
Important trends in consumer purchasing behavior are shown by the sales trend study.  Businesses may efficiently manage resources, schedule promotions, and optimize inventory by detecting sluggish and high-performing months.  With the aid of this aggregation-based method, unprocessed sales data can be turned into useful insights for improved decision-making.
  
