🛒 SuperStore Sales Analysis Dashboard

An end-to-end Business Intelligence solution analyzing retail sales performance across segments, categories, and geographies using Power BI.

📌 Table of Contents

- Project Overview
- Business Objective
- Dataset
- Dashboard Overview
- Key Insights
- Tech Stack
- Project Structure
- Getting Started
- KPI Summary
- Methodology
- Contributing
- License

🎯 Project Overview
This project delivers a comprehensive Sales Performance Analysis Dashboard built with Microsoft Power BI, powered by the classic SuperStore retail dataset. It empowers business stakeholders to make data-driven decisions by visualizing sales trends, profitability patterns, regional performance, and customer segment behavior across a 2-year period (2019–2020).
The dashboard covers 5,901 transactions, 3,003 unique orders, and 773 distinct customers — spanning 3 product categories across 4 US regions.

💼 Business Objective

"To transform raw transactional data into actionable business intelligence that helps retail management optimize sales strategies, identify high-performing product segments, and improve regional profitability."

Core Questions Answered:

- Which product categories and sub-categories drive the highest revenue and profit?
- How does sales performance vary across customer segments (Consumer, Corporate, Home Office)?
- What are the monthly and yearly sales trends?
- Which states and regions contribute most to overall revenue?
- What payment modes and shipping preferences do customers exhibit?


📁 Dataset

- File Name : SuperStore_Sales_Dataset.csv
- Records : 5,901 rows
- Features : 23 columns
- Time Period : January 2019 – December 2020
- Geography : United States (49 States)
- Source : Kaggle

📋 Data Dictionary

  Column        |        Type        |        Description
- Row ID                Integer           Unique row identifier
- Order ID              String            Unique order identifier
- Order Date             Date             Date the order was placed
- Ship Date              Date             Date the order was shipped
- Ship Mode           Categorical         Shipping class (Standard, Second, First, Same Day)
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Profit
- Returns
- Payment Mode

📊 Dashboard Overview
The Power BI dashboard (Super_Store_Sales_Analysis_Dashboard.pbix) is structured across multiple report pages, each targeting a specific analytical lens:

Page 1 — Sales Overview
- Total Sales, Profit, Quantity, and Average Delivery Day KPI cards
- Monthly Sales trend line chart (Year-over-Year comparison)
- Sales by Category (donut chart)
- Sales by Segment (donut chart)
- Sales by Ship Mode (bar chart)
- Sales by Payment Mode (bar chart)

Page 2 — Geographic Analysis
- US State-level choropleth map (Sales by State)
- Regional performance (West, East, Central, South)
- Top 10 States by Revenue bar chart

Page 3 — Product & Profitability Analysis
- Profit by Sub-Category
- Sales vs. Profit scatter analysis
- Category-level breakdown
- Year-over-Year growth metrics


📈 Key Insights

💰 Revenue & Profitability
- Total Sales: $1,565,804
- Total Profit: $175,262 (11.19% profit margin)
- Total Units Sold: 22,317
- Average Order Value: $521.41
- Year-over-Year Growth: ~77% increase from 2019 to 2020

🏷️ Category Performance



💡 Insight: Technology drives the highest profit margin (19.2%) despite ranking 2nd in sales. Furniture is a high-revenue but low-margin category requiring pricing review.

👥 Customer Segments



💡 Insight: The Consumer segment is the primary revenue driver (48.1% of total sales). Corporate segment shows strong per-customer spend potential.

🌎 Regional Performance



💡 Insight: West and East combined contribute 62% of total revenue. South region is underperforming and may benefit from targeted campaigns.


📦 Shipping & Payment
- Standard Class is the dominant shipping mode (58.5% of orders)
- Cash on Delivery (COD) is the most preferred payment method (41.5%), followed by Online (36.6%) and Cards (21.7%)
- Top states: California ($335K), New York ($187K), Texas ($116K)


📅 Seasonal Trends
- Sales peak in Q4 (Oct–Dec) — December 2020 alone recorded $166K in sales
- September 2020 showed a mid-year spike at $119K
- Lowest activity observed in April–May

🛠️ Tech Stack
- Tool : Microsoft Power BI Desktop  |  Purpose : Dashboard creation, DAX measures, data modeling
- Tool : Python(Pandas)  |  Purpose : Exploratory data analysis & data validation
- Tool : CSV / Excel  | Purpose : Raw data storage and preprocessing
- Tool : DAX  |  Purpose : Custom KPI calculations and time intelligence measures
- Power Query(M)  |  Purpose : Data transformation and cleaning


📂 Project Structure
superstore-sales-dashboard/
│
├── 📊 Super_Store_Sales_Analysis_Dashboard.pbix   # Power BI Dashboard
├── 📄 SuperStore_Sales_Dataset.csv                # Raw dataset
├── 📋 README.md                                   # Project documentation
├── 📁 assets/
│   ├── screenshots/                               # Dashboard screenshots
│   └── icons/                                     # Report icons
└── 📁 docs/
    └── data_dictionary.md                         # Detailed data reference




