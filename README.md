# Sales-Profit-Analysis-dashboard-using-Power-BI
This is a Sales analysis Dashboard created using Power BI based on one Publicly available Dataset. This project is created for Data Visualization and Data Analysis purpose.This Power BI dashboard provides a comprehensive analysis of sales and profit analysis for a fictional Superstore business.It enables business users to track regional performance
This Power BI dashboard provides a comprehensive analysis of sales and profit performance for a fictional Superstore business. It enables business users to track regional performance, understand customer buying behaviour, evaluate profitability across different segments, and identify sales trends over time.
The dataset covers key attributes such as Order Details, Customer Segments, Regions, Product Categories, and Time Period, offering rich, actionable insights through interactive visuals and KPIs.
The primary objectives of this dashboard are: 

•	To monitor overall sales and profit performance.

•	To evaluate regional and segment-wise contribution.

•	To understand customer behavior through top buyers and profit margins.

•	To observe sales trends and support business forecasting.
# Key Performance Indicators (KPIs)
KPI Name	Description	DAX Measure (likely)	Purpose
Total Sales	Sum of all sales revenue	SUM(Orders[Sales])	Tracks gross revenue earned across orders.
Total Profit	Sum of profit earned from all transactions	SUM(Orders[Profit])	Measures the profitability across all orders.
Order Count	Total number of distinct orders placed	DISTINCTCOUNT(Orders[Order ID])	Monitors business volume and frequency.
Sales by Region/Segment	Bar or map visuals showing region-wise or segment-wise performance	SUM(Sales) with slicers on Region/Segment	Aids in comparing performance across business dimensions
Top Customers	Customers with the highest purchase value	TOPN() with SUM of Sales	Helps in identifying loyal or high-value customers.
Top Products	Products generating the highest profit or revenue	TOPN() based on SUM of Sales or Profit	Highlights best-selling and high-margin products.
Sales Trend	Time-based line chart showing monthly or yearly sales/profit trends	SUM(Sales) grouped by Order Date	Reveals patterns and seasonality in sales.

