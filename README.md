# Fork & Flame: Restaurant Sales & Order Distribution Dashboard

## 📌 Business Case & Problem Statement
In the fast-paced Food & Beverage (F&B) industry, restaurant chains capture massive volumes of daily transactional data. However, operations managers often fail to spot critical trends—such as peak operational hours, shifting customer preferences, or uneven branch performance—due to data being trapped in flat tables.

This project addresses these operational inefficiencies by establishing a multi-page, interactive sales analytics system. It transforms raw point-of-sale (POS) logs into strategic business insights, allowing stakeholders to optimize inventory, streamline staffing during peak hours, and maximize revenue across all locations.

## 📊 Key Analytical Features
*   **Operational Health Check (Main KPIs):** Delivers instant visibility into business volume, highlighting **Total Sales ($165K)** and **Total Quantity Sold (17K)** alongside continuous performance trend micro-charts.
*   **Menu & Category Performance:** Categorizes and filters sales metrics by food type (e.g., Burger, Coffee, Dessert, Pasta, Pizza), allowing managers to isolate specific category impacts instantly.
*   **Branch & Spatial Distribution:** Maps revenue and transaction distribution metrics across prime locations (**Downtown, Campus, Airport, and Mall**), revealing that the *Airport* and *Downtown* branches drive the highest cumulative volumes.
*   **Advanced Customer Insights & Executive Views:** Built with dedicated sub-navigation sheets focusing on historical performance comparisons (Sales vs. Sales PY) to easily identify year-over-year growth trajectories.

## 🛠️ Technical Architecture & Workflow
1.  **ETL & Data Cleaning (Power Query):** Processed raw transactional logs by fixing timestamp anomalies, splitting date/time components for hourly tracking, and eliminating data entry errors.
2.  **Star Schema Data Modeling:** Architected a solid data model connecting a central Fact table (Sales Transactions) to multi-dimensional lookup tables including Category Dimension, Location Dimension, and a dedicated Date/Time Calendar table.
3.  **Complex DAX Aggregations:** Developed customized DAX formulas to calculate Prior Year Sales (Sales PY), Year-to-Date parameters (Sales YTD), and transaction counts dynamically across any filtered context.
4.  **UI/UX Design Strategy:** Implemented a modern, responsive side-navigation layout with clean grid layouts, intuitive visual hierarchies, and synchronized slicers for seamless exploration.

## 📷 Dashboard Preview
![Fork & Flame Dashboard]

---
*Developed by Hazem Mohamed - Data Analyst & Computer Engineering Student.*
