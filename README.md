# 📈 E-commerce Performance Analysis (Power BI)

## 📌 Project Overview
This project focuses on analyzing a comprehensive e-commerce dataset to evaluate financial performance, product profitability, and marketing efficiency. I built this dashboard to help stakeholders move beyond raw data and identify exactly which products drive profit and which traffic sources deliver the highest conversion rates.

## 🛠️ Tools Used
- Power BI: Data modeling, DAX measure creation, and interactive visualization.

## ⚙️ Project Methodology
1. Data Preparation: Imported raw tables and excluded metadata files to focus purely on transactional data.
2. Data Cleaning: Standardized data types across all tables and performed a complete duplicate check to ensure data integrity.
3. Data Handling: Used the "Replace Values" function to address NULL values, standardizing them to "None" in the website_sessions table.
4. Data Modeling: Established a robust star-schema model, connecting 6 distinct tables to allow for seamless cross-table filtering.
5. DAX Implementation: Engineered custom measures to drive accurate performance tracking.

## 📊 Key KPIs & Metrics
I utilized DAX (New Measure) to engineer the following core performance metrics:
* Total Revenue
* Total COGS
* Total Gross Profit
* Gross Margin %
* Total Refund
* Conversion Rate: Calculated as DIVIDE(DISTINCTCOUNT(orders[website_session_id]), DISTINCTCOUNT('website sessions'[website_session_id]), 0)

## 💡 Key Business Insights
* Year-Over-Year Financial Performance: Plotted Total Revenue (Y-axis) against Time (X-axis) using year-based filtering to visualize growth trends.
* Product Profitability & Margin Erosion: Created a product performance matrix comparing Total Revenue, Total COGS, and Gross Margin to isolate products that are negatively impacting overall profitability.
* Revenue vs. COGS Analysis: Built a comparative visualization to measure Revenue against COGS per product, highlighting the cost-to-profit efficiency of the current product line.
* Marketing Efficiency & Conversion: Used the custom Conversion Rate measure to rank traffic sources by their ability to turn visitors into paying customers.
* Executive Strategy: Beyond the main dashboard, I have included an Executive Insights & Recommendations page. This section translates the data trends into clear, actionable business strategies for stakeholders.

## 🔗 How to View My Work
- The Dashboard: See the "Project Preview" below for a visual snapshot of the project.
- The Power BI File: [Download the full E-commerce_Project.pbix file here](E-commerce_Project.pbix). You are welcome to explore my data modeling, DAX formulas, and dashboard mechanics.

## 🖼️ Project Preview
![E-commerce Dashboard](insert-your-image-link-here)

> *Click the image above to view the dashboard.*

## Dataset

---
*Developed by Joseph — Data Analyst.*
