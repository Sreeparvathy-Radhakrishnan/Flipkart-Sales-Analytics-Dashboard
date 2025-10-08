Flipkart Sales Analysis Dashboard (PostgreSQL & Power BI)

📌 Project Overview

This project is a comprehensive Business Intelligence solution that analyzes a hypothetical Flipkart Sales dataset. It transforms raw transactional data into a set of interactive, actionable dashboards using a robust pipeline.The solution starts with data ingestion into a relational database, progresses through data modeling, and culminates in a three-page analytical report designed to uncover sales trends, evaluate product performance, and analyze customer behavior to inform strategic business decisions. The project highlights proficiency in both server-side data preparation and front-end analytical modeling (DAX).

⚙️ Tech Stack

This project is a hybrid SQL and BI development solution, emphasizing the following technologies :<br>
- PostgreSQL	Used for centralized data storage, defining the initial schema, and performing basic ETL (Extract, Transform, Load) operations on the raw data.
- Power BI	Primary platform for Data Modeling, Report Authoring, and Dashboard Design.
- DAX (Data Analysis Expressions)	Utilized heavily for creating all custom Key Performance Indicators (KPIs) and complex analytical measures (e.g., aggregations, temporal calculations).
- CSV Dataset	The initial format of the raw Flipkart sales data.

📂 Data Source

Dataset: Flipkart Sales Data (Transactional and Order Details)
Key Fields: Order ID, Product Name, Category, Price, Quantity Sold, Total Sales (INR), Order Date, Payment Method, and Customer Rating.

🛠️ Data Cleaning and Transformation

This step involved preparing the raw CSV for reliable analysis across both PostgreSQL and Power BI :<br>

- Schema Definition (PostgreSQL): Defined precise data types for each column upon import to ensure data integrity.
- Date Field Extraction: Extracted Year, Month, and Quarter from the Order Date column to enable precise time-series analysis and filtering.
- Data Type Conversion: Ensured all numerical fields (e.g., Price (INR), Total Sales (INR)) were correctly cast as numeric types suitable for aggregation.
- Relationship Modeling (Power BI): Established a robust data model by creating necessary relationships and marking date tables (if applicable) to optimize DAX query performance.

🚀 Business Problem (Key Questions)

The dashboard was specifically designed to answer the following core business questions :

- What are the overall sales performance and order volume trends over time?
- Which product categories and individual products are the primary drivers of revenue and quantity sold?
- What are the most and least popular payment methods used by customers?
- How is customer satisfaction (Customer Rating) distributed, and are there correlation between low ratings and specific products or categories?
- What is the average transaction value (Average Sales Price)?

🎯 Goal of the Dashboard

The central goal of the dashboard is to provide an interactive and intuitive analytical view of the Flipkart sales performance, allowing stakeholders (category managers, marketing teams) to :

- Track Performance : Monitor key operational and financial KPIs in real-time.
- Identify Opportunities : Pinpoint best-selling products/categories for inventory prioritization and marketing focus.
- Optimize Operations : Understand customer payment preferences and rating feedback to improve service quality.

📈 Dashboard Overview

The final Power BI solution is structured across three primary pages, accessible via a user-friendly navigation layout:

- Sales Overview : High-level summary of all KPIs, top-line financial metrics, and overall time-based sales trends.
-Product Insights	: Detailed analysis of category and product-level performance, highlighting best-sellers and revenue contribution.
-Customer and Payment Insights :	Focus on customer behavior, specifically distribution of customer ratings and analysis of payment method usage.


📊 Walkthrough of Key Visuals

The dashboard employs dynamic visuals powered by custom DAX measures to communicate insights effectively.

Page 1: Sales Overview<br>

-Total Sales and Total Orders (Card Visuals)
-Monthly Sales Trend (Line Chart)
-Total Sales by Category (Bar Chart)

Page 2: Product Insights<br>

-Top 10 Products by Revenue (Table Visual)
-Product Count by Category (Donut Chart)
-Average Price by Product (Bar Chart)

Page 3: Customer and Payment Insights<br>

-Total Orders by Payment Method (Pie Chart)
-Customer Rating Distribution (Column Chart)
-Orders by Customer Location (Bar Chart)

🚀 Future Enhancements

- SQL View Optimization : Create pre-aggregated SQL Views in PostgreSQL for complex summaries and connect Power BI to these views, shifting heavy processing away from the DAX layer.
- Advanced Customer Segmentation : Integrate additional data to segment customers (e.g., high-value vs. frequent buyers) and create dedicated segmentation reports.
- What-If Analysis : Implement DAX parameters to allow users to simulate promotional scenarios or price changes and see the potential impact on sales.

🎉 Conclusion

This Flipkart Sales Analysis Dashboard successfully transforms raw transactional data, demonstrating a complete data lifecycle from PostgreSQL ingestion to highly interactive visualization in Power BI. The project proves proficiency in SQL, data modeling, and advanced DAX, delivering a crucial tool for data-driven commerce strategy.

🎥 Demo

Click the button below to explore the full, interactive Power BI Dashboard : [Live Demo]().

✍️ Author

Sreeparvathy Radhakrishnan
[LinkedIn ]()














Tools

