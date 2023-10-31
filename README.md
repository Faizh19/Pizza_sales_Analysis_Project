# Pizza_sales_Analysis_Project
I Analyzed and visualized pizza sales report using sql query and power bi dax functions.

KPI’s REQUIREMENT 

I analyzed the key performance indicators for the pizza sales data to gain insights into this business performance. Specifically, I calculated the following metrics as per the company reuirement.

1.Total Revenue

2.Average order value

3.Total pizzas sold

4.Total orders 

5.Average pizzas per order

CHARTS  REQUIREMENT 

I visualized  various aspects of our pizza sales data to gain insights and understand key trends. We have identified the following requirements for creating charts:

1.Daily Trend for Total Orders

2.Monthly Trend for Total Orders 

3.Percentage of Sales by Pizza Category 

4.Percentage of sales by pizza size 

5.Total Pizzas Sold by Pizza Category 

6.Top 5 Best Sellers by Total Pizzas Sold 

7.Bottom 5 Worst Sellers by Total Pizzas Sold 

Dax Functions (Power BI)

1. Total Revenue = SUM(pizza_sales[total_price])

2. AOV = [Total Revenue]/[Total Order]
   
3. Total Pizza's Sold = SUM(pizza_sales[quantity])
   
4. Total Order = DISTINCTCOUNT(pizza_sales[order_id])
  
5. Avg Pizza's Per Order = [Total Pizza's Sold]/[Total Order]
   

SQL Query with result - (https://docs.google.com/document/d/1n45CqvI-cF03D7yO_IzdFAZ_Yb9t3USCebDyiIxDsu0/edit?usp=sharing)

we calculated on both sql and power bi to confirm our result. 

Conclusion - Now we can make the business discussion for further investment and launch a new category of pizza or removal of under performance category based on there performance and sales.














 


