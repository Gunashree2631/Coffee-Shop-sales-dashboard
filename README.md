☕ Coffee Shop Sales Dashboard
📊 Project Overview
The Coffee Shop Sales Dashboard is an interactive Power BI data analytics project designed to analyze coffee shop sales, product performance, customer footfall, and store-level performance.
The dashboard transforms sales data into interactive visualizations and KPIs, helping users understand revenue trends, product performance, customer activity, and store performance.
🎯 Project Objectives
Analyze overall coffee shop sales performance.
Track total sales and items sold.
Understand customer footfall across store locations.
Compare sales across different product categories.
Identify high-performing and low-performing products.
Analyze sales trends over time.
Provide interactive filtering for better business analysis.
Create a professional and user-friendly Power BI dashboard.
📌 Key KPIs
The dashboard provides the following key performance indicators:
KPI
Description
Total Sales
Overall revenue generated
Total Items Sold
Total number of items sold
Average Order
Average order value
Average Spent per Customer
Average customer spending
Total Footfall
Number of customers/visitors
📈 Dashboard Visualizations
1. Total Footfall by Store Location
A pie chart showing customer footfall across:
Astoria
Hell's Kitchen
Lower Manhattan
2. Total Items Sold by Product Category
A donut chart showing the distribution of items sold across product categories.
3. Total Sales by Product ID
A trend-style visual showing sales performance across product IDs.
4. Total Sales by Product Category
A horizontal bar chart comparing sales across categories such as:
Coffee
Tea
Bakery
Drinking Chocolate
Coffee Beans
Flavours
Packaged Chocolate
Loose Tea
5. Product Sales Table
A detailed table providing category-level sales information and totals.
6. Interactive Slicers
The dashboard includes interactive filters for:
Date
Store Location
Product Category
Product Type
Users can select filters to dynamically analyze specific parts of the business.
🛠️ Tools & Technologies
Microsoft Power BI
Microsoft Excel
Power Query
DAX
Data Modeling
Data Visualization
🔄 Data Analysis Process
Raw Sales Data
      ↓
Data Cleaning
      ↓
Power Query Transformation
      ↓
Data Modeling
      ↓
DAX Measures
      ↓
Interactive Visualizations
      ↓
Power BI Dashboard
      ↓
Business Insights
📊 Data Modeling
The project follows a structured data model consisting of:
Fact Sales
Dimension Product
Dimension Store
Dimension Calendar
The model enables relationships between sales transactions, products, stores, and dates for effective reporting.
🧮 DAX Measures
Examples of measures used in the dashboard:
Total Sales = SUM('Fact Sale'[Total Sales])
Total Items Sold = SUM('Fact Sale'[transaction_qty])
Total Footfall = DISTINCTCOUNT('Fact Sale'[transaction_id])
Avg Order = DIVIDE([Total Sales], [Total Footfall])
Avg Items per Order = DIVIDE([Total Items Sold], [Total Footfall])
💡 Business Insights
The dashboard can be used to identify:
Which product categories generate the most revenue.
Which store locations receive the highest customer footfall.
Which products contribute significantly to overall sales.
How sales performance changes over time.
The relationship between customer activity and sales.
Opportunities for improving product and store performance.
🎨 Dashboard Features
✅ Interactive slicers
✅ KPI cards
✅ Donut and pie charts
✅ Bar charts
✅ Trend analysis
✅ Detailed sales table
✅ Date filtering
✅ Store-level analysis
✅ Product-level analysis
✅ Interactive Power BI experience
📷 Dashboard Preview
The dashboard provides a consolidated view of sales, products, customers, and stores, allowing business users to explore performance through interactive filters and visualizations.
👨‍💻 Project Skills Demonstrated
This project demonstrates practical skills in:
Power BI | DAX | Power Query | Excel | Data Cleaning | Data Modeling | Data Visualization | Business Analytics | KPI Development | Interactive Dashboard Design
🚀 Future Enhancements
Add sales forecasting.
Add monthly and yearly growth analysis.
Add customer segmentation.
Add sales targets and achievement indicators.
Add advanced decomposition-tree analysis.
Add automated data refresh.
Publish the dashboard to Power BI Service.
