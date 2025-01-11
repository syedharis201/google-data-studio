Looker Studio Dashboard Project

Overview
This project demonstrates how to create an interactive dashboard in Looker Studio (formerly Google Data Studio) using a sample dataset. The dashboard provides visual insights into sales data, including revenue trends, regional performance, and product-level analysis.

Features
Data Source Integration**: Connected a sample dataset with fields like Sales Amount, Units Sold, Date, and Region.
Computed Fields:
Total Revenue: Calculates total sales revenue.
Average Sales per Unit: Shows the average revenue per unit sold.
Year and Month: Extracts temporal details from the date field for time-based analysis.

Visualizations:
Scorecards: Highlights key metrics (e.g., Total Revenue, Average Sales per Unit).
Bar Chart: Displays sales by product category.
Time Series Chart: Shows sales trends over time.
Line chart :- show trends of data

Customizations:
Interactive filters for date range and categorical data.
Color-coded charts for better visualization.

Prerequisites
A Google account to access Looker Studio.
Basic understanding of data visualization concepts.

Steps to Recreate the Dashboard

1. Connect the Data Source
   Open Looker Studio and create a new report.
   Connect to your dataset (e.g., CSV, Google Sheets, or BigQuery).
   Verify that the fields have the correct data types (e.g., Date, Number).

2. Add Computed Fields
   Go to the Data Source Settings.
   Click Add a Field and create the following fields:
   Total Revenue: SUM(Sales Amount)
   Average Sales per Unit: SUM(Sales Amount) / SUM(Units Sold)
   Year: YEAR(Date)
   Month: MONTH(Date)


3. Add Interactivity
   Add a Date Range Filter to allow users to filter data by time.
   Add filters for categorical fields like Region or Product Category.

4. Finalize the Dashboard
   Arrange the charts logically (e.g., scorecards at the top, detailed charts below).
   Added titles and descriptions to guide users.

