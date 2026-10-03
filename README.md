# Task-17-monthly-sales-trend
Monthly Sales Trend Analysis

Day 17 of 45 — Data Analytics Internship

This project was completed as part of my Data Analytics Internship at Veda Technology.

The objective was to summarize retail sales by month and visualize the sales trend using a line chart.

Project Objectives

•
Convert transaction dates correctly

•
Group sales by month

•
Create a monthly sales summary table

•
Sort months chronologically

•
Create a monthly sales line chart

•
Practice Python and Excel data analysis

Dataset

This project uses the UCI Online Retail Dataset.

Dataset source: 

UCI Online Retail Dataset

The dataset contains online retail transactions from a UK-based retailer.

Tools and Technologies

•
Python

•
Pandas

•
Matplotlib

•
Excel

•
XlsxWriter

Methodology

Transaction sales were calculated using:

Plain Text


Sales = Quantity × UnitPrice



The following data-cleaning steps were applied:

1.
Converted InvoiceDate into a proper date format.

2.
Removed canceled invoices.

3.
Removed invalid or zero-value transactions.

4.
Grouped transactions by calendar month.

5.
Calculated total sales, orders, units sold, and unique customers.

Key Findings

•
Highest sales month: November 2011 — £1,509,496.33

•
Lowest sales month: February 2011 — £523,631.89

•
Sales increased strongly from September to November 2011.

•
December 2011 recorded lower sales and may represent an incomplete month in the source data.




Project Files

File
Description
monthly_sales_trend.py
Python script used for cleaning and analysis
Online Retail.xlsx
Original UCI dataset
retail_sales_dataset.csv
Cleaned transaction-level dataset
monthly_sales_summary.csv
Monthly sales summary table
monthly_sales_line_chart.png
Monthly sales trend visualization
monthly_sales_trend.xlsx
Excel workbook containing the data, summary, and chart




How to Run the Project

Install the required Python packages:

Bash


pip install pandas matplotlib openpyxl XlsxWriter



Run the analysis script:

Bash


python monthly_sales_trend.py



Internship Update

Day 17 of 45 — Data Analytics Internship at Veda Technology

Today, I completed a Monthly Sales Trend Analysis using Python, Excel, Pandas, and Matplotlib.

Acknowledgement

Thanks to Veda Technology for providing this learning opportunity and helping me develop practical data analytics skills.

License

This project is created for educational and internship purposes.

