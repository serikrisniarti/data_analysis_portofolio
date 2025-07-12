# 🛍️ Sales Transaction Analysis Project

### 📌 Overview
This project analyzes one year of sales transactional data to uncover customer behavior, product trends, and key performance indicators. The primary goal is to deliver actionable insights that can support strategic decision-making to improve sales performance and customer retention. This project using **Python** for data cleaning, data analysis, and creating visualizations.

### 🎯 Objectives
1. Identify monthly sales trends and seasonal peaks.
2. Segment customers using RFM analysis and rule-based logic.
3. Analyze popular products and purchasing behavior.
4. Understand basket size, price elasticity, and retention trends.
5. Provide recommendations to improve marketing and business strategies.

### 🧩 Dataset

The dataset is "SalesTransactionv4a-230918-164139.csv" file that includes:
- CustomerNo: Unique customer identifier. 
- TransactionNo: Unique transaction identifier.
- ProductNo, ProductName: Information about products.
- Quantity, Price, Date: Order details.
- Country: Customer location. 
The dataset covers transactions throughout the year 2019.

### 🔍 Key Analyses Performed
📈 1. Monthly Sales Trend
- Found a significant spike in November 2019.
- Recommended to optimize promotion strategies around high-performing months.

📦 2. Top Selling Products
- Identified the most frequently purchased items.
- Suggested bundling and stock prioritization for popular items.

🛒 3. Basket Size Analysis
- Evaluated basket size by transaction and by country.
- Revealed variations in average purchase value by region.

💸 4. Price Sensitivity (Elasticity)
- Discovered some products with negative correlation between price and quantity sold.
- Recommended avoiding price increases for sensitive products.

👥 5. Customer Segmentation
- RFM Analysis classified customers into 10 behavioral segments.
- Rule-Based Segmentation grouped customers into VIP, High, Medium, and Low using revenue, recency, frequency, and basket size.
- Combined view highlights overlap and differences in both segmentation approaches.

📆 6. Cohort Analysis
- Identified customer retention by cohort month.
- July and August had the best retention, suggesting effective campaign strategies.

### 📊 Visualizations
The analysis includes rich visualizations such as:
1. Line charts (sales trend)
2. Bar charts (top products, basket size)
3. Scatter plots (price elasticity, segmentation)
4. Heatmaps (cohort retention)
5. Cluster plots (RFM & Rule-Based segmentation)

### 💡 Strategic Recommendations
- Maximize revenue during seasonal peaks (e.g., November).
- Retain high-value (VIP) customers with loyalty programs.
- Apply price adjustments only to low-elasticity products.
- Promote product bundles to increase average order value.
- Replicate effective marketing strategies from high-retention cohorts.
