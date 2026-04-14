# Retail-Store Performance Analysis
This project provides a comprehensive analysis of retail sales data to identify key revenue drivers, optimize inventory and understand customer purchasing behavior. The project transforms raw transactional data into actionable business intelligence using SQL for query, Python for EDA, and Power BI for interactive dashboard.
I utilized a multi-stage analytical pipeline to ensure data integrity and deep insight generation:

Excel: Used for initial data exploration and quick ad-hoc calculations. Leveraged Pivot Tables and lookup functions to identify early trends and perform data sanity checks.

SQL: Acted as the backbone for data management. I wrote complex queries—including JOINs, CTEs, and Window Functions—to aggregate multi-table datasets, calculate Year-over-Year (YoY) growth, and filter high-value customer segments.

Python: Employed for advanced data cleaning (Pandas) and exploratory data analysis (EDA). Used Python scripts to handle missing values, outliers, and to perform statistical correlations that informed the visualization strategy.

Power BI: Developed an interactive executive dashboard to visualize KPIs such as Total Revenue, Profit Margins, and Monthly Sales Trends. Implemented DAX measures for dynamic time-intelligence reporting and slicers for regional performance breakdowns.

Key Insights:

Customer Satisfaction Gap: The Average Rating of 3.30 suggests a "neutral-to-positive" sentiment, but indicates significant room for improvement in service or product quality to reach a 4.0+ benchmark.

Low-Performing Inventory: The "Least Rated Products" chart identifies products of low rating. This warrants a quality audit or a change in supplier for that specific line.

Sales vs. Satisfaction Correlation: The scatter plot shows a high density of products moving in quantities between 45 and 65 units, but with widely varying ratings. This suggests that high sales volume does not necessarily correlate with high customer satisfaction in this store.

Concentration Risk: The revenue is heavily concentrated among the top 5 customers. Implementing a loyalty program specifically for these "Power Users" is critical for revenue stability.
