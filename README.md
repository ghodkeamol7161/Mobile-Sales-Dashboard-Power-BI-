# Mobile-Sales-Dashboard-Power-BI-

## Objective of the Dashboard
This repository contains an interactive Power BI dashboard built for analyzing mobile phone sales data. The dashboard helps users understand sales trends, performance by product, region, and more through visually engaging and dynamic reports.

## Purpose
- The purpose of this dashboard is to provide a clear, interactive visualization of mobile phone sales data. It helps stakeholders understand how different products, regions, and time periods contribute to overall sales performance.
- Gives upper management a quick overview of the company’s mobile sales performance.

## Description
- This project is three pages Dashboard.
    -  Dashboard Report
    -  MTD(Month To Date) Report
    -  Same Period Last Year Report 

- Custom Calender: Four years of custom calender.
- Calculate Dax


 ## Calculated Dax Formulaes:
 
- 'Mobile_Sales_Data'[Transactions] = COUNTROWS(Mobile_Sales_Data)
- 'Mobile_Sales_Data'[Total_Sales] = SUMX(Mobile_Sales_Data, Mobile_Sales_Data[Units Sold] * Mobile_Sales_Data[Price Per Unit])
- 'Mobile_Sales_Data'[Total_Quantity] = sum(Mobile_Sales_Data[Units Sold])
- 'Mobile_Sales_Data'[Average_Price] = AVERAGE(Mobile_Sales_Data[Price Per Unit])
- 'Mobile_Sales_Data'[MTD] = TOTALMTD([Total_Sales],Custom_Calender[Date].[Date])
- 'Mobile_Sales_Data'[QTD] = TOTALQTD([Total_Sales],Custom_Calender[Date].[Date])
- 'Mobile_Sales_Data'[YTD] = TOTALYTD([Total_Sales],Custom_Calender[Date].[Date])
- 'Mobile_Sales_Data'[Same Period Last Year] = CALCULATE([Total_Sales],SAMEPERIODLASTYEAR(Custom_Calender[Date].[Date]))



## 📁 File Details
- "Mobile Sales Dashboard.pbit": Power BI template file. You can open it using [Power BI Desktop].
- <a href="https://github.com/amolghodake1714/Mobile-Sales-Dashboard-Power-BI-/blob/main/Mobile_Sales_Dashboard.pbit">Mobile Sales Dashboard</a>


## 📌 How to Use

1. Download and open the `.pbit` file in Power BI Desktop.
2. Connect to your mobile sales dataset or use sample data.
3. Customize visuals as needed.


## 💡 Tools Used

- Power BI Desktop
- Power Query Editor
- Data Modeling and Transformations
- Custom Calender
- Slicers, charts, Cards, Maps
- DAX (Data Analysis Expressions)
- Navigator (Page navigator and bookmarks)
- Edit Interactions


## 📚 Insights

This dashboard helps answer questions like:
- Which mobile brand is generating the highest revenue?
- Which region is performing best in terms of sales?
- What are the monthly and yearly sales trends?
- Which products are most popular among customers?

## Key Components and Pages
## 🟦 Page 1: Executive Summary / KPI Overview
•	KPIs Displayed:
-	Total Revenue – Indicates the total earnings from mobile sales.
-	Units Sold – Number of mobile phones sold.
- Purpose - - Gives upper management a quick overview of the company’s mobile sales performance.

## 📈 Page 2: Sales Trends
-	Line/Area Chart: Shows monthly or quarterly sales trends.
-	Insights Provided:
-	Growth or decline in sales over time.
-	Impact of promotions, holidays, or product launches.


## 🌍 Page 3: Regional Analysis
-	Map Visual: Highlights sales by City
-	Bar/Column Chart: Top 5 regions by sales.
-	Slicer: Allows filtering by region to drill down.
-	Use Case: Identifies which locations are performing best or need attention.



## 🚀 Features

- **Overall Sales Summary**
  - Total Revenue(sales), Units Sold, and Profit
- **Sales Trends**
  - Monthly sales trend line
- **Regional Analysis**
  - Sales by City
- **Product Performance**
  - Top-performing brands and models
 

## Interactive Features
- 	Slicers and Filters:
- 	Time period (Day, Month, Quarter, Year)
-	Product category or brand
-  Drill-Down: Click on visual elements to dive deeper into specific segments.



## 🧠 Insights Gained

- Identified top-selling brands and models
- Tracked cities with highest profitability
- Monitored monthly growth patterns






## ✍️ Author

**Amol Ramdas Ghodake**  
📧 ghodkeamol7161@gmail.com]  
🔗 LinkedIn Profile: https://www.linkedin.com/in/amol-ghodke-b77b5b371/
