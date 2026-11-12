# Coffee Shop Sales Analysis

## Project Overview
This project analyzes coffee shop sales and inventory data for April 2019 to identify sales trends, product performance, customer patterns, and pastry waste.

The project uses Python for data cleaning and exploratory data analysis, and Power BI to build an interactive dashboard that presents key business insights.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Power BI
- DAX
- Microsoft Excel

## Dataset
The dataset contains multiple tables covering:
- Sales transactions
- Products
- Customers
- Staff
- Sales outlets
- Pastry inventory
- Sales targets
- Date and generation information

**Period Covered:** April 2019

## Project Workflow

### 1. Data Analysis with Python
- Explored datasets and checked data types.
- Identified missing values and duplicate records.
- Checked relationships and consistency between tables.
- Merged sales data with product information.
- Analyzed sales by product group and time.
- Examined pastry inventory and recorded waste.

### 2. Power BI Dashboard
Built a two-page interactive dashboard:

**Page 1 – Sales Overview**
- Key Performance Indicators (KPIs)
- Sales by Product Group
- Sales by Outlet
- Sales by Hour
- Daily Sales Trend
- Top 10 Products by Sales

**Page 2 – Product & Customer Analysis**
- Total Waste by Product
- Product Waste Rate
- Waste Rate by Branch
- Sales by Generation
- Sales by Gender

## Key Business Insights

### Sales Performance
- Beverages generated 77.29% of total revenue.
- Beverages and Food together accounted for 88.82% of total revenue.
- 10 AM recorded the highest sales revenue and quantity.
- 11 AM recorded the highest number of distinct transaction IDs.

### Customer Analysis
- Sales associated with customer ID 0 represented 51.07% of total revenue.
- This indicates a significant portion of sales could not be linked to a known customer profile.

### Inventory & Waste Analysis
- Total recorded pastry waste was 4,500 units.
- Overall waste rate was 60.93% of starting inventory.
- Ginger Scone accounted for 47.56% of recorded waste.
- Outlet 5 had the highest overall recorded waste rate at 63.10%.

## Limitations
- The sales dataset covers April 2019 only.
- Pastry inventory data covers only outlets 3, 5, and 8.
- Some sales records are not linked to known customer profiles.
- A difference of 32 units exists between starting inventory and the sum of recorded sold and wasted quantities. The cause could not be confirmed from the available data.

## Conclusion
This project demonstrates an end-to-end data analysis workflow, from data exploration and preparation using Python to interactive business reporting with Power BI.

The findings highlight opportunities to improve product performance monitoring, customer data collection, and inventory waste management.