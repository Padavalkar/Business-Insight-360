# Business-Insight-360 Power-BI Project.
### Business Insights 360 – Power BI Project By Codebasics.

The Business Insights project is part of the Codebasics Data Analytics Bootcamp. It’s a complete Data Analysis and Power BI project based on a fictional company, AtliQ Hardware.

### About AtliQ Hardware
AtliQ Hardware manufactures and sells products like PCs, mice, and printers to companies worldwide. Their customers include Croma, Amazon, Neptune, Staples, and Walmart, and they serve both physical stores and e-commerce platforms.

### Problem Statement
AtliQ Hardware is struggling in Latin America, relying on surveys and intuition for decisions. Previously, they used MS Excel for analysis due to limited data, but with growth, they now have ample data. Therefore, they hired a Data Analyst to make informed decisions using this data.

### Management’s Dashboard Requirements:
•	Finance View: Profit and loss statements by product, market, and customer.

•	Marketing View: Sales data by product.

•	Supply Chain: Reliability and accuracy metrics for supply chain performance.

•	Executive View: Key insights for executives.

This Power BI project simulates real-life business scenarios, including recorded stakeholder meetings, feedback loops, and iterative design changes to save time and provide essential metrics in a consolidated report.

### Project Execution:

**Step 1**: Load the data into a MySQL Database and connect it to Power BI.

**Step 2**: Review and delete default database relationships created by Power BI; create required dimension tables in Power Query.

**Step 3**: Validate data using tables in Power BI and match values with provided data.

**Step 4**: Transform data, e.g., create a dynamic Last Sales Month Reference table.

**Step 5**: Create calculated columns in Power Query (e.g., fiscal_year) and merge tables.

**Step 6**: Perform data modeling using a Star Schema to connect dimension tables with fact tables.

**Step 7**: Create calculated columns using over 40 DAX formulas, verifying them with MySQL or Excel.

**Step 8**: Optimize the report to reduce file size for easier sharing and access before designing and building dashboards.

### Building The Dashboard

I created 5 different report views for various stakeholders. Here’s an overview:

**Home Page**: The first page includes navigation to all views and a summary of each for easy access.

**Finance View**: Shows P&L statements, top/bottom performing products and customers, product segment performance by region, and Year on Year P&L comparison. A button displays Net Sales performance vs. Last Year and vs. Target.

**Sales View**: For the sales team to analyze product and customer performance in each region with similar filters as the Finance View.

**Marketing View**: Contains Gross Margin %, Net Profit %, Operational Expenses, and Cost of Goods Sold. Helps in deciding marketing budgets and identifying potential customers and markets.

**Supply Chain View**: Provides data on demand forecasting and inventory management. Shows historical forecast accuracy and highlights issues, like a drop in Accessories segment performance.

**Executive View**: A consolidated report with key metrics like Net Sales, Return on Capital %, Gross Margin %, Net Profit %, Forecast Accuracy %, Market Share, top-selling products, and top customers. Designed for senior stakeholders to get a quick overview without delving into details.

#### Tools Used in Project:
•	MS Excel
• MySQL
•	**Power BI**
•	**Power BI Service**
**Learnings from Project:**
•	Power BI skills
•	Data Modeling
•	Dashboard Creation & Designing
•	Project Charter
•	Stakeholder Mapping
•	Analyzing P&L Statements
**Project Work:**
**Focus:** Analyzing business transactions such as Profit %, Gross Margin %, Forecast %, and sales comparisons using DAX formulas.

**Learning Outcomes:**
•	Understanding P&L statements.
•	Comparing product, category, market, and customer performance.
•	Providing comprehensive financial stats and performance metrics on dashboards.
**Power BI Features Learned & Used:**
•	**DAX Formulas**: Key measures for building the report (detailed list below).
•	**Data Modeling**: Structuring data relationships.
•	**Table Creation**: Building tables for data representation.
•	**Creating Tool Tips**: Adding helpful information to visuals.
•	**Creating Switch using Bookmark**: Allowing dynamic view changes.
•	**Creating Dynamic Titles**: Updating titles based on data changes.
•	**Conditional Formatting**: Handling blank results after filtering.
•	**Dynamic Last Refresh Date**: Showing the latest data update.
•	**Different Views**: Tailoring reports for different departments in a single report.
**DAX Formulas Learned**: (List of formulas not provided in the summary)
This project involved both Power BI technical skills and understanding business scenarios to effectively compare and display product, market, and customer performance on dashboards.
This is my first Power BI project, and I've learned that creating a report is just one part of being a Data Analyst. Technical skills, soft skills, teamwork, a problem-solving mindset, and a "get it done" attitude are also essential for success in this role.
I’m excited to work on more data analytics projects in marketing, finance,logistics and other areas. If you’re a data aspirant looking to start your career as a Data Analyst, please like and share this post!




