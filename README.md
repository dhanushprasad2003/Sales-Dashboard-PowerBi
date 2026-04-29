# Power BI Sales Dashboard Project

## Overview

This project is a **Power BI Sales Analytics Dashboard** created using the dataset provided in `PowerBI_Sales_Dataset.xlsx`. It analyzes product-wise sales, customer segments, discounts, and revenue performance through interactive visualizations.

## Files Included

* `product wise sales data.pbix` – Main Power BI report file
* `PowerBI_Sales_Dataset.xlsx` – Source dataset used for reporting
* `README.md` – Project documentation

## Dataset Structure

The Excel workbook contains 3 sheets:

### 1. Products

Contains product master data:

* ProductID
* ProductName
* Category
* Price
* CostPrice
* ProfitMargin%

### 2. Customers

Contains customer information:

* CustomerID
* CustomerName
* City
* Segment
* Region
* CleanedName

### 3. Sales

Transactional sales data:

* OrderID
* Date
* ProductID
* CustomerID
* Quantity
* UnitPrice
* SalesAmount
* Discount%
* FinalAmount
* IsCleaned
* LoadDate

## Dashboard Features

* Total Sales Revenue KPI
* Final Amount after Discounts
* Product-wise Sales Analysis
* Category-wise Performance
* Region-wise Customer Distribution
* Customer Segment Insights
* Discount Impact Analysis
* Time-based Sales Trends

## Power BI Concepts Used

* Data Modeling using relationships
* Power Query data cleaning & transformation
* DAX Measures & KPIs
* Slicers and interactive filtering
* Charts, Cards, Tables, and Trend visuals

## Suggested KPIs

* Total Sales
* Total Orders
* Average Order Value
* Discount Given
* Profit Margin %
* Top Selling Product
* Top Region by Revenue

## How to Use

1. Download all project files.
2. Open `product wise sales data.pbix` in Power BI Desktop.
3. If needed, refresh data source connection to the Excel file.
4. Explore dashboard visuals and filters.

## Skills Demonstrated

* Business Intelligence
* Data Visualization
* Data Cleaning
* DAX Calculations
* Dashboard Design
* Analytical Thinking

## Author

**Dhanush Prasad**  
[GitHub](https://github.com/dhanushprasad2003)

## License

Free to use for learning and portfolio purposes.
