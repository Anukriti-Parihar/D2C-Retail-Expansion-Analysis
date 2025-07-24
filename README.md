# D2C-Retail-Expansion-Analysis
# Objective
The goal of this project is to analyze 1.5 years of sales data for Monday Coffee, a direct-to-consumer (D2C) coffee brand that has been operating online since January 2023. Using SQL-based data exploration and business intelligence techniques, we aim to identify the top three Indian cities for launching new physical retail outlets. The recommendations are driven by consumer demand, sales performance, operational feasibility, and customer segmentation.

# Key Business Questions Solved
1. Coffee Consumers Count
Estimate number of potential coffee consumers per city (25% of population).
2. Total Revenue from Coffee Sales
Calculate revenue generated in Q4 2023 across all cities.
3. Sales Count for Each Product
Identify best-selling coffee and merchandise products by total orders.
4. Average Sales Amount per City
Compute average customer spend per city using sales and customer counts.
5. City Population and Coffee Consumers
Combine population data with actual customer base to find potential growth.
6. Top Selling Products by City
Use DENSE_RANK() and PARTITION BY to find top 3 products per city.
7. Customer Segmentation by City
Count unique customers per city who purchased coffee products only.
8. Average Sale vs Rent
Calculate both average sales and average estimated rent per customer.
9. Monthly Sales Growth
Use LAG() and window functions to compute month-over-month growth by city.
10. Market Potential Analysis
11. Multi-factor comparison of all cities based on:
    Total revenue
    Total customers
    Estimated rent
    Estimated coffee consumers
    Average rent per customer
    Average revenue per customer
    
# Final Recommendation
After comprehensive analysis, the following cities are ideal for new store launches:

Pune -	Highest total revenue, low average rent per customer, high avg sales per customer
Delhi	- Largest consumer base (7.7M estimated), highest total customers (68), reasonable rent
Jaipur - Highest unique customer count (69), very low rent per customer, strong avg sales
