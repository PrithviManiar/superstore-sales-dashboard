# 🛒 Superstore Sales Dashboard — Power BI

An interactive sales analytics dashboard built in Power BI using the Sample Superstore dataset.

## 📸 Screenshots
![Overview](screenshots/overview_page.png)
![Regional Analysis](screenshots/regional_page.png)

## 📊 Features
- KPI Cards: Total Sales, Profit, Orders, Profit Margin %
- Monthly Sales Trend (Line Chart)
- Sales by Category & Sub-Category (Bar Charts)
- US Sales Map (Filled Map)
- Regional Profit Matrix with conditional formatting
- Interactive slicers: Year, Region, Segment

## 🛠️ Tools & Skills
- Power BI Desktop
- Power Query (data cleaning)
- DAX (custom measures)
- Data modeling (Star schema with Date Table)

## 📁 Dataset
[Sample Superstore Dataset — Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## 💡 Key DAX Measures
```dax
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
Total Orders = DISTINCTCOUNT(Orders[Order ID])
```

## 🚀 How to View
Download `Superstore_Sales_Dashboard.pbix` and open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop) (free).
