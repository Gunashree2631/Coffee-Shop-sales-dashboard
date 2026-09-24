# ☕ Coffee Shop Sales Dashboard

## 📊 Project Overview
The **Coffee Shop Sales Dashboard** is an interactive Power BI project designed to analyze coffee shop sales, product performance, customer footfall, and store-level performance.  
It transforms raw sales data into **interactive visualizations and KPIs**, helping users understand revenue trends, product performance, customer activity, and store performance.

---

## 🎯 Project Objectives
- Analyze overall coffee shop sales performance  
- Track total sales and items sold  
- Understand customer footfall across store locations  
- Compare sales across different product categories  
- Identify high-performing and low-performing products  
- Analyze sales trends over time  
- Provide interactive filtering for better business analysis  
- Create a professional and user-friendly Power BI dashboard  

---

## 📌 Key KPIs
| KPI | Description |
|-----|-------------|
| **Total Sales** | Overall revenue generated |
| **Total Items Sold** | Total number of items sold |
| **Average Order** | Average order value |
| **Average Spent per Customer** | Average customer spending |
| **Total Footfall** | Number of customers/visitors |

---

## 📈 Dashboard Visualizations
1. **Total Footfall by Store Location** – Pie chart (Astoria, Hell's Kitchen, Lower Manhattan)  
2. **Total Items Sold by Product Category** – Donut chart  
3. **Total Sales by Product ID** – Trend-style visual  
4. **Total Sales by Product Category** – Horizontal bar chart (Coffee, Tea, Bakery, Drinking Chocolate, Coffee Beans, Flavours, Packaged Chocolate, Loose Tea)  
5. **Product Sales Table** – Detailed category-level sales information  
6. **Interactive Slicers** – Filters for Date, Store Location, Product Category, Product Type  

---

## 🛠️ Tools & Technologies
- Microsoft Power BI  
- Microsoft Excel  
- Power Query  
- DAX  
- Data Modeling  
- Data Visualization  

---

## 🔄 Data Analysis Process
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

---

## 📊 Data Modeling
The project follows a **star schema** data model:
- **Fact Sales**  
- **Dimension Product**  
- **Dimension Store**  
- **Dimension Calendar**  

This enables relationships between sales transactions, products, stores, and dates for effective reporting.

---

## 🧮 DAX Measures
```DAX
Total Sales = SUM('Fact Sale'[Total Sales])
Total Items Sold = SUM('Fact Sale'[transaction_qty])
Total Footfall = DISTINCTCOUNT('Fact Sale'[transaction_id])
Avg Order = DIVIDE([Total Sales], [Total Footfall])
Avg Items per Order = DIVIDE([Total Items Sold], [Total Footfall])
💡 Business Insights
Identify top revenue-generating product categories

Compare customer footfall across store locations

Highlight products contributing significantly to overall sales

Track sales performance trends over time

Understand the relationship between customer activity and sales

Discover opportunities for improving product and store performance

🎨 Dashboard Features
✅ Interactive slicers
✅ KPI cards
✅ Donut & pie charts
✅ Bar charts
✅ Trend analysis
✅ Detailed sales table
✅ Date filtering
✅ Store-level analysis
✅ Product-level analysis
✅ Interactive Power BI experience

👨‍💻 Project Skills Demonstrated
Power BI

DAX

Power Query

Excel

Data Cleaning

Data Modeling

Data Visualization

Business Analytics

KPI Development

Interactive Dashboard Design

🚀 Future Enhancements
Add sales forecasting

Monthly and yearly growth analysis

Customer segmentation

Sales targets and achievement indicators

Advanced decomposition-tree analysis

Automated data refresh

