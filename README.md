Sales Performance Analysis Using SQL

Problem Statement

	The company want to understand its sales performance across different regions, products, and Customers in order to:
  
•	Identify top-performing products

•	Understand customer purchasing behaviour 

•	Detect underperforming areas

•	Make data-driven business decisions



Data Analysis Include:

Total Sales

SELECT SUM(Sales) AS Total_Sales FROM sales;

Sales By Product

SELECT Product, SUM(Sales) AS Total_Sales FROM sales GROUP BY Product ORDER BY Total_Sales DESC;

Sales By Region

Top Customers

High value customers(>300)

Average Sales

Count Rows


Key Insights

	Lagos region generated the highest revenue, indicating strong market performance

	Milo is the top performing product, contributing the majority of total sales.

	Ada perform best, contributes significantly to total revenue ( High value customer)

	Abuja region needs improvement

Recommendations

	Increase inventory and marketing efforts for Milo

	Focus expansion strategies on high performing region (Lagos)

	Introduce loyalty programs for high-value customers

	Improve marketing in low-performing regions to boost sales(Abuja)
