# SUPER-STORE-DATASET
The Superstore Sales dataset is a simulated data collection from a fictional retail company selling office supplies across the United States. It contains detailed records of sales, customers, regions, profits, discounts, and more.
This dataset is perfect for practicing:
 Data Analysis in Excel
 Business Dashboards in Power BI
 Data-driven decision making
 Dataset Summary
# File Format: CSV / Excel (.xlsx)
Rows: ~10,000+
Size: ~1MB
Source: Public (used in Tableau, Power BI, Kaggle, and academic projects)

# Column Descriptions
Column Name	Description
Order ID	Unique order identifier
Order Date	Date the order was placed
Ship Date	Date the order was shipped
Ship Mode	Shipping method
Customer ID	Unique customer identifier
Customer Name	Name of the customer
Segment	Market segment (Consumer, Corporate, Home Office)
Country	Country (mostly United States)
City	Customer city
State	Customer state
Postal Code	ZIP code
Region	Geographic region
Product ID	Unique product ID
Category	Product category (e.g., Furniture)
Sub-Category	Product sub-category (e.g., Chairs)
Product Name	Full product name
Sales	Total sales value
Quantity	Number of units sold
Discount	Discount applied
Profit	Profit earned

# Excel Analysis Ideas
You can use Excel to perform EDA and reporting with formulas, pivot tables, and charts:
Key Excel Features to Use:
Feature	Use Case
PivotTables	Summarize sales by Region, Category, or Customer
Conditional Formatting	Highlight negative profits
Slicers	Filter dashboards by Region or Segment
VLOOKUP/XLOOKUP	Fetch data across multiple sheets
Charts	Create column charts for Sales vs. Profit
IF statements	Calculate profitability logic (e.g., =IF(Profit<0,"Loss","Profit"))
Named Ranges	For cleaner formulas in dashboards
Data Validation	Create dropdowns for user inputs

Example Pivot Table:
Rows: Region
Values: Sales, Profit
Filters: Category

# Power BI Dashboard Ideas
Power BI is great for building interactive dashboards from this dataset. Here are some ideas:
 Load Steps:
Import the dataset via Get Data > Excel/CSV
Clean columns with Power Query
Create calculated columns or measures using DAX

# Suggested Power BI Visuals:
Visual	Purpose
Bar Chart	Top 10 Products by Sales or Profit
Map	Sales by State
Line Chart	Monthly Sales Trends
Treemap	Profit by Sub-Category
Donut Chart	Sales Share by Segment
Matrix Table	Sales & Profit by Region and Category
Slicer	Filter by Region, Segment, Year

# DAX Measures (Examples):
DAX
Copy
Edit
Total Sales = SUM(Superstore[Sales])
Total Profit = SUM(Superstore[Profit])

# Licensing
This dataset is free for educational and non-commercial use. Commonly used in Tableau, Power BI, Excel, and Kaggle communities.

# Deliverables (on request)
I can provide the following:
 Cleaned Excel version with Pivot Tables & Charts
 Power BI .pbix file with dashboard visuals
 Markdown / PDF version of this README
