# Start-Dynamics-Item-Sales-Report
A comprehensive, 3-page interactive Power BI dashboard designed to turn raw transactional data into actionable business insights. This project focuses on tracking core retail KPIs, mapping regional sales performance, and analyzing product profitability to drive data-driven decision-making.

📊 Dashboard Breakdown
1. Sales Analysis
Focuses on top-line revenue metrics and historical sales trends.

Core KPIs: Displays $20M in Total Sales and 1.0M in Total Quantity sold.

Trend Analysis: Features a Total Sales by Year line chart to monitor performance trajectory.

Geographical Insights: Includes a Sales by State matrix that categorizes performance tiers (e.g., Amazing, Average, Poor) to easily spot high-performing regions.

2. Profitability Deep-Dive 
Shifts focus to the bottom line, helping stakeholders evaluate margins and cost structures.

Core KPIs: Displays $9.9M in Total Profit alongside a strong 49.9% Profitability margin.

Item-Level Performance: Uses a dual-metric horizontal bar chart (Profit, Total Sales and Sum of Quantity by Stock Item) to directly contrast product revenue against its associated cost.

3. Granular Details 
Provides a deep dive into product distribution networks and high-volume territories.

Market Shares: Utilizes a structured Treemap to visualize tax-exclusive totals by state, highlighting California and Washington as dominant markets.

Logistics Breakdown: Includes a pie chart analyzing Buying Package types, revealing that individual packaging ("Each") accounts for 70.29% of the total quantity distributed.

🛠️ Technical Implementation
Data Transformation: Leveraged Power Query for data extraction, cleaning, and schema normalization.

Data Modeling & DAX: Developed calculated measures and explicit columns to handle high-level performance categorization and dynamic margin metrics.

UI/UX & Interactive Design: Built a clean, corporate-blue interface featuring native tab navigation (Sales | Profit | Details). Integrated multi-layer slicers for Employee, Customer, City, Buying Group, and Sales Territory to support effortless analytical drill-downs.
