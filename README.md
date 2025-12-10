# powerbi_classic
A Power BI dashboard that analyzes vehicle sales performance across models, regions, dealers, and time periods. The report provides insights into revenue trends, top-selling models, customer preferences, and dealership performance to support data-driven sales decisions.
The Vehicle Sales Analysis Dashboard provides an interactive and insightful view of automotive sales data.
It helps stakeholders understand key business metrics such as total revenue, units sold, top-performing vehicle models, regional sales distribution, and customer purchase behavior.

This dashboard was built using Power BI, leveraging Power Query, data modeling, and DAX measures to transform raw vehicle sales data into actionable insights.

📁 Repository Contents
File/Folder	Description
Vehicle_Sales_Dashboard.pbix	Power BI report file
Data/	Raw and cleaned dataset used for the dashboard
Screenshots/	Images of dashboard pages
README.md	Documentation for the project
📊 Key Insights

The dashboard answers the following questions:

What are the total sales revenue and total units sold?

Which vehicle models and categories perform best?

What are the regional sales trends across dealers?

How do monthly and yearly sales compare?

Who are the top customers and what patterns exist in their purchases?

What is the average selling price per model?

How do discounts and pricing influence overall performance?

📈 Dashboard Features
🔹 Interactive Filters

Vehicle Model

Category (SUV, Sedan, Truck, EV, etc.)

Region / State

Dealer

Year / Month

🔹 Visualizations

KPI Cards (Revenue, Units Sold, Avg. Price)

Sales Trend Line Charts

Top & Bottom Performing Models

Sales by Region (Map Visual)

Customer Demographics

Dealer Performance Ranking

Profitability Analysis

🔹 Advanced Analytics

DAX Measures for KPIs

Time Intelligence (YoY, MoM growth)

Drill-through pages

Forecasting trends

🛠️ Technologies Used

Power BI Desktop

Power Query (M Language)

DAX (Data Analysis Expressions)

Excel / CSV Data Sources

Data Modeling

🧠 Data Model Overview

The data model consists of:

Sales Table – transaction details

Vehicle Table – model, category, specs

Dealer Table – dealership details

Customer Table – demographics

Date Table – calendar for time intelligence

Relationships were built following a star schema to optimize reporting performance.

🎯 Project Objectives

Provide a clear understanding of vehicle sales trends

Identify high-performing and low-performing models/dealers

Support business decision-making using data-driven insights

Enable forecasting for future sales planning

Improve visibility into customer segments and behavior

🖼️ Dashboard Preview

(Insert screenshots from your Screenshots folder)

Example:

![Dashboard Screenshot](./Screenshots/dashboard_main.png)

📥 How to Use the Dashboard

Download the .pbix file from this repository.

Open it in Power BI Desktop.

Refresh the data source (if needed).

Explore filters, drill-throughs, and visuals interactively.

🤝 Contributing

Contributions are welcome!
If you want to enhance visuals, improve DAX formulas, or add new features, feel free to create a pull request.
