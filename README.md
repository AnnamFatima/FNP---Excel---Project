# FNP---Excel---Project

Steps followed in the project are as follows :
1. Extraction of Data
2. Cleaning of Data
3. Transformation
4. Data Modelling 
5. Data Analysis
6. Create Dashboard
7. Executive Summary

1. Extraction of Data
We have used Power Query Editor . Its an ETL tool (Extract Transform Load). 

2. Cleaning of Data &  3. Transformation
We have used Power Query Editor .Its an ETL tool (Extract Transform Load). 

- Customer table - No chnages made

-Orders Table
From order dates extracted order months.
From Odert Time cloumn extarted the oder hour
From Delivery Time column extracted the hour of delivery
Added new column showing the difference between Delivery date and order date to check the time taken for delivery ( its format was DD,HH,MM,SS so transformed the column duration to Days)
Wanted the product price in the orders table - so we merged Queries - selected common column and merged choosing only price from the products table

- Products Table - No chnages made

4. Data Modelling 

We have used Power Pivot. 
We tried to insert some pivot tables like gender with Price  or products category with Price and the amount was the same for every row. So we opened the power pivot and under the diagram view made connections between the dataset.

Added Revenue column (through the power pivot) under data view by multiplying Price with Quantity

5. Data Analysis
We have used Pivot Tables and Measures.
Started working on your Questions:
1.Identify the overall revenue - 35,20,984.00
2.Avg order with delivery time- We have a column with diff between  Delivery date and order date - It is giveing us the sum so Under value feild settings chnaged it to average - The avg is 5.53 
3.Monthly sales performance - created pivot table with Sum of Revenue and Months - had months in alphabetical ascending oder - under more setting changed it to ascending by month name . 
4. Top products by revenue - created pivot table with product name and sum of revenue
and sorted the top 5.
5. Avg of Customer spending analysis - avg order value - avg of revenue 
6. Sales performance of top 5 products- created pivot table with Category name and sum of revenue.
7. Top 10 cities with number of orders - created pivot table with City name and order id ( but not sum - cunt of order ID) and choose top 10.
8. Order Quantity vs. Delivery time - analyze if higher order quantities impact delivery timw  - Used correlation to analyze that - 0.003478174
9. Revenue Comparision Between different occasions - created pivot table with Occasion name and Revenue
10. Product popularity by occassion - Added slicer for this


6. Create Dashboard
We have used basic charts - Inserted basic charts . created some extra measures and charts .
Added Timeline and slicer.
Reported connections between Slicer and timelines.

7. Executive Summary

Overview
This sales analysis evaluates the key metrics driving business revenue, customer spending, and order trends across various occasions, product categories, and time periods.

Key Metrics
Total Orders: 1,000
Total Revenue: ₹35,20,984.00
Average Customer Spending: ₹3,520.98
Average Order-Delivery Time: 5.53 days

Revenue Insights

Revenue by Occasion:
Anniversary and Raksha Bandhan generate the highest revenue, followed by Holi.

Diwali and Valentine's Day sales are comparatively lower.

Revenue by Category:
Colors drive the highest revenue, significantly surpassing other categories.
Soft Toys and Sweets are the next highest revenue-generating categories.
Mugs and Plants contribute the least revenue, indicating areas for improvement.

Revenue by Month:
February and August see the highest revenue spikes, likely influenced by major festive or seasonal demand.
March and November show moderate revenue.
May and June experience lower sales, indicating potential opportunities for targeted promotions.

Revenue by Hour (Order Time):
Peak order placement occurs between 6 AM - 8 AM and 6 PM - 8 PM, suggesting key hours for targeted marketing efforts.

Top 5 Products by Revenue:
Magaman Set generates the highest revenue.
Quia Gift, Harum Pack, Dolores Gift, and Deserunt Box follow closely in performance.

Top 10 Cities by Orders:
Dhanbad, Kavali, and North Dumdum have the highest order volume.
Other cities like Imphal and Haridwar also show strong order activity.

Conclusion & Recommendations
Target Key Sales Hours: Invest in promotional campaigns during 6 AM - 8 AM and 6 PM - 8 PM when order volumes peak.
Enhance Seasonal Promotions: March and September see high revenue, while May and June are weaker, suggesting the need for marketing efforts in low-revenue months.
Boost Underperforming Categories: Mugs and Plants have low revenue; bundling them with popular categories could improve sales.
Expand in High-Order Cities: Dhanbad, Kavali, and North Dumdum are key markets that should be prioritized for regional campaigns.
Monitor Top-Selling Products: Magaman Set and Quia Gift are bestsellers, making them ideal candidates for premium placement in marketing and inventory management.
