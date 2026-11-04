VRINDA STORE
DATA ANALYSIS
Project Documentation & Analysis Workflow
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Prepared by
Harsh Dev Singh
Data Analyst  |  Microsoft Excel
Tool: Microsoft Excel
Dataset: Vrinda Store FY 2022 E-commerce Data

 Project at a Glance
This project uses Microsoft Excel to explore Vrinda Store’s FY 2022 e-commerce sales data. The work covers data inspection and cleaning, preparation of analysis fields, exploratory data analysis, Pivot Table summaries, KPI calculations, charts, and an interactive dashboard.
The final dashboard brings key sales, customer, product, channel, geographic, and order-performance views together in one place. Interactive slicers allow users to filter the report by month, channel, and category.
Project	Vrinda Store Data Analysis
Business area	E-commerce sales and order performance
Primary tool	Microsoft Excel
Analysis methods	Data cleaning, Pivot Tables, KPI calculations, charts and slicers
Dataset period	FY 2022
Author	Harsh Dev Singh
Contents
•	1. Project Overview and Objective
•	2. Project Workflow
•	3. Data Collection
•	4. Data Cleaning
•	5. Data Preparation
•	6. Exploratory Data Analysis
•	7. Pivot Table Analysis
•	8. KPI Analysis
•	9. Dashboard Development
•	10. Interactive Dashboard and Filters
•	11. Data Visualization
•	12. Business Insights and Outcomes
•	13. Tools and Technologies
•	14. Project Files
•	15. Conclusion
1. Project Overview and Objective
The purpose of this project is to convert raw transactional sales data into meaningful information that can support business understanding and decision-making. The analysis focuses on sales performance, customer purchasing patterns, product demand, sales channels, geographic performance, and order outcomes.
Project objectives
•	Evaluate overall sales performance, order volume, and quantity sold.
•	Understand monthly sales trends and identify stronger-performing periods.
•	Compare sales across product categories, sizes, and sales channels.
•	Explore customer purchasing patterns by gender and age group.
•	Review state-wise sales performance and geographic demand.
•	Examine order status, delivery performance, and return patterns.
•	Present the analysis in an interactive Excel dashboard.
2. Project Workflow
The project followed a structured workflow from raw data to a business-facing dashboard:
Raw Data  →  Data Cleaning  →  Data Preparation  →  Exploratory Analysis
→  Pivot Tables  →  KPI Calculations  →  Dashboard  →  Insights
PROJECT WORKFLOW FLOWCHART
01
Raw Data
Vrinda Store dataset	→	02
Data Cleaning
Check and clean records	→	03
Data Preparation
Organize analysis fields	→	04
Exploratory Analysis
Explore trends and patterns
Continue to the reporting stage  ↓
08
Insights & Findings
Interpret business results	←	07
Dashboard Creation
Build charts and slicers	←	06
KPI Calculation
Calculate key measures	←	05
Pivot Tables
Summarize the data
The workflow moves from raw transactional data through Excel analysis and ends with an interactive dashboard and business insights.
3. Data Collection
The project began with the Vrinda Store FY 2022 e-commerce dataset. The source data was imported into Microsoft Excel and reviewed to understand its structure, fields, and suitability for analysis.
Key dataset fields
•	Order ID and Customer ID
•	Gender, Age, and Age Group
•	Date and Month
•	Sales Channel
•	Product Category and Size
•	Quantity and Amount
•	Shipping or delivery information
•	Order Status
•	State
4. Data Cleaning
Before analysis, the dataset was checked for common data-quality issues. Cleaning was intended to improve consistency and reduce errors in the summaries and visualizations.
1.	Reviewed the dataset structure and identified the available columns.
2.	Checked for duplicate records and removed unnecessary duplicates where appropriate.
3.	Checked for blank or missing values.
4.	Verified data types, including dates and numerical fields.
5.	Reviewed and corrected date-related fields where required.
6.	Standardized categorical values such as Channel, Category, and Order Status.
7.	Checked numerical fields such as Amount and Quantity for consistency.
8.	Reviewed Order Status values to support reliable order and delivery analysis.
The objective of cleaning was to make the data consistent and suitable for analysis. Any exclusions or corrections should be retained in the workbook so that the process remains traceable.
5. Data Preparation
After cleaning, the fields required for analysis were organized and used to build comparable views of the business. The main dimensions used throughout the project were:
•	Month
•	Gender
•	Age Group
•	Channel
•	Category
•	Size
•	State
•	Order Status
These dimensions were used to group and compare sales, quantity, customer segments, and order outcomes. Where fields such as Month or Age Group were already present in the source data, they were checked for consistency.
6. Exploratory Data Analysis
Exploratory Data Analysis (EDA) was performed to understand the dataset and identify patterns worth investigating through Pivot Tables and charts.
Sales performance
•	What is the total sales amount?
•	How many orders were placed?
•	What is the total quantity sold?
•	Which month recorded the highest sales?
Customer analysis
•	Which gender contributes more to sales?
•	Which age group purchases the most?
•	Which customer segments generate higher revenue?
Product analysis
•	Which categories generate the most sales?
•	Which sizes are ordered most frequently?
•	Which categories show the strongest demand?
Channel analysis
•	Which sales channel generates the highest sales?
•	Which channels receive the most orders?
Geographic analysis
•	Which states generate the highest sales?
•	Which regions show stronger customer demand?
Order analysis
•	How many orders were delivered?
•	How many orders were cancelled or returned?
•	What does the order-status distribution indicate about fulfillment?
7. Pivot Table Analysis
Excel Pivot Tables were used to summarize transactional records and compare performance across different business dimensions. They provided a flexible way to aggregate sales and order information.
•	Sales by Month
•	Sales by Gender
•	Sales by Age Group
•	Sales by Category
•	Sales by Channel
•	Sales by State
•	Quantity by Category
•	Order Status distribution
•	Delivery performance
•	Return performance
The Pivot Table summaries served as the analytical foundation for the dashboard charts and KPI calculations.
8. KPI Analysis
Key Performance Indicators (KPIs) were included to provide a quick view of the store’s overall performance. The dashboard uses the following measures:
KPI	What it represents	Typical calculation concept
Total Sales	Total revenue represented in the dataset.	Sum of Amount
Total Orders	Number of orders represented in the dataset.	Distinct count of Order ID, where appropriate
Total Quantity	Total number of product units sold.	Sum of Quantity
Delivery Rate	Share of orders successfully delivered.	Delivered orders ÷ eligible total orders × 100
Return Rate	Share of orders returned.	Returned orders ÷ eligible total orders × 100
Note: The denominator and treatment of cancelled, refunded, or other order statuses should be defined consistently for delivery and return rates. The workbook’s actual formulas should be used as the final reference.
9. Dashboard Development
After the analysis was completed, an interactive, single-page Excel dashboard was assembled. Its purpose is to bring the most relevant measures and comparisons into one view.
•	KPI cards for the headline business measures
•	Monthly sales analysis
•	Category and channel analysis
•	Gender and age-group analysis
•	State-wise sales analysis
•	Order-status analysis
•	Delivery and return analysis
•	Interactive filters or slicers
10. Interactive Dashboard and Filters
The dashboard includes slicers for Month, Channel, and Category. When a slicer selection changes, the connected Pivot Tables, charts, and KPI values update to reflect the selected data.
Example use
Selecting a particular month allows the user to review the sales, orders, quantity, delivery rate, and return rate associated with that period. Selecting a channel or category narrows the view to the corresponding part of the business.
11. Data Visualization
Charts were used to make the results easier to interpret and to highlight differences, trends, and distributions that may be difficult to identify in raw rows of data.
•	Monthly sales trends
•	Category performance
•	Channel performance
•	Gender-wise sales
•	Age-group analysis
•	State-wise sales
•	Order-status distribution
•	Delivery and return performance
The visualizations are intended to support quick comparisons and help users explore the data through the dashboard filters.
12. Business Insights and Project Outcomes
The analysis framework helps a user investigate business questions and identify:
•	High-performing months and sales trends
•	Product categories with stronger sales or quantity demand
•	Sales channels contributing more to revenue or order volume
•	Customer segments with different purchasing patterns
•	States contributing more to sales
•	Product size and category demand patterns
•	Order fulfillment and delivery performance
•	Return and cancellation patterns
Reporting note: This document describes the analysis performed and the questions the dashboard is designed to answer. Specific numerical findings or rankings should be added from the final workbook after validating the Pivot Tables and dashboard values; no figures have been assumed or fabricated here.
Skills developed
•	Data cleaning and preparation
•	Exploratory data analysis
•	Excel functions and calculations
•	Pivot Table analysis
•	KPI development
•	Data visualization
•	Interactive dashboard development
•	Business-oriented reporting
13. Tools and Technologies
Tool / Feature	Purpose in the project
Microsoft Excel	Primary environment for data preparation, analysis, and dashboard development
Excel Pivot Tables	Summarizing and grouping transactional data
Excel Charts	Visual presentation of trends and comparisons
Excel Slicers	Interactive filtering by selected dimensions
Excel Functions	Supporting calculations and analysis
Data cleaning techniques	Improving consistency and reliability of the dataset
14. Project Files
1. Vrinda Store Data Analysis (PROJECT 1).xlsx
The Excel workbook contains the project’s working analysis, including:
•	Cleaned dataset
•	Data analysis and calculations
•	Pivot Tables
•	Dashboard
•	Interactive filters and slicers
•	Charts and visualizations
2. Final Vrinda_Store_Analysis_Report.docx
The detailed report contains the written explanation of the analysis, observations, findings, and conclusions.
3. Final Dashboard Screenshot
A screenshot or image of the completed dashboard provides a quick visual reference to the final report layout.
15. Conclusion
The Vrinda Store Data Analysis project demonstrates how raw e-commerce transaction data can be organized and transformed into a structured analytical report and interactive dashboard using Microsoft Excel. The workflow covered data inspection, cleaning, preparation, exploratory analysis, Pivot Tables, KPI calculations, visualization, and dashboard development.
By bringing multiple business dimensions into one interactive report, the project provides a practical way to explore sales performance, customer behavior, product demand, channel contribution, geographic trends, and order outcomes. The resulting analysis can support better-informed discussions around sales, marketing, inventory, and customer targeting.
Project Author
Harsh Dev Singh
Data Analyst  |  Microsoft Excel
Thank you for exploring this project.
