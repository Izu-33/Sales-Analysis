# Sales Insight Case Study

### Overview
This project analyzes sales data from Company XYZ to identify patterns and insights that could explain a recent decline in sales performance. The analysis answers key business questions regarding the best sales month, top-selling cities, optimal advertising times, popular product combinations, and the most sold products.

### Business Questions Addressed
What was the best month for sales? How much was earned that month?
Which city sold the most products?
What time should we display advertisements to maximize the likelihood of customer purchases?
What products are most often sold together?
Which product sold the most? Why do you think it sold the most?

### Data
The dataset consists of 12 months' worth of sales transactions from an electronics store, including product type, cost, purchase address, and other relevant details.

### Methodology
Data Preparation
*Merging Data:*
Combined data from 12 separate monthly CSV files into a single DataFrame.

*Data Cleaning:*
Removed NaN values.
Dropped rows with incorrect or missing data.
Converted columns to appropriate data types (e.g., to_numeric, to_datetime, astype).

*Feature Engineering:*
Created a Month column to facilitate monthly analysis.
Extracted and added a City column from the purchase address.

### Analysis & Visualization
Best Month for Sales: Bar graph showing monthly sales revenue to identify peak performance.
Top-Selling Cities: Bar graph comparing sales across different cities.
Optimal Advertising Time: Line graph plotting sales volume by hour of the day to determine the best time for advertisements.
Product Combinations: Analysis of products frequently bought together.
Top-Selling Product: Identification of the most popular product with an analysis of contributing factors (e.g., price, popularity).

### Tools Used
Pandas: Data manipulation and analysis.
Matplotlib: Data visualization.
Results
Best Month for Sales: [Insert the best month and sales amount]
Top-Selling City: [Insert the top city]
Optimal Advertising Time: [Insert the best time range for ads]
Popular Product Combinations: [Insert key product combinations]
Top-Selling Product: [Insert the top product and possible reasons for its popularity]

### Conclusion
This analysis provided actionable insights into Company XYZ's sales performance, helping to identify factors contributing to the recent decline and offering data-driven recommendations for improving sales strategies.
