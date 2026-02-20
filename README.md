👟 Adidas US Sales Performance Analysis

📌 Project Overview
This project provides a comprehensive analysis of Adidas sales performance across the United States. Using a dataset of over 9,000 transactions, I developed a dynamic Power BI dashboard to help stakeholders identify regional sales trends, product demand, and profitability across various sales channels and retailers.

The primary goal was to transform raw transactional data into actionable business intelligence that can drive inventory and marketing strategies.

📊 Key Business Questions Answered
Which regions and states are the top revenue drivers?

Which product categories have the highest profit margins?

How do different sales methods (In-store, Online, Outlet) compare in terms of efficiency?

Who are our most valuable retail partners (e.g., Foot Locker, Kohl's, Walmart)?

🛠️ Technical Stack & Workflow
1. Data Cleaning & ETL (Power Query)
Data Standardization: Handled inconsistent date formats and regional naming conventions.

Column Profiling: Ensured data quality for numeric fields like Total Sales and Operating Profit.

Feature Engineering: Created custom columns for fiscal periods and regional groupings.

2. Data Modeling
I implemented a Star Schema to optimize report performance and ensure accurate filtering across multiple dimensions.

3. DAX Calculations
Advanced DAX measures were created to calculate key performance indicators (KPIs), including:

Total Sales & Total Profit

Average Operating Margin

Units Sold by Product Category

Year-over-Year (YoY) Growth Metrics

4. Data Visualization
The dashboard features several interactive components:

Geospatial Maps: To visualize sales density across the US.

Trend Lines: To monitor sales fluctuations over time.

Decomposition Trees: To drill down into the root causes of regional profit variances.

💡 Key Insights & Recommendations
Top Product: "Men's Street Footwear" consistently outperformed other categories in both volume and revenue.

Sales Channel Shift: While "In-store" sales currently lead in revenue, "Online" sales show a higher operating margin, suggesting a pivot toward e-commerce could increase net profitability.

Regional Opportunity: The West region shows a high unit sales count but a lower average price per unit, indicating a potential market for premium product launches.

📂 Repository Structure
/Data: Contains the raw CSV/Excel datasets.

/Report: The .pbix Power BI file for local exploration.

/Screenshots: High-resolution images of the final dashboard pages.
