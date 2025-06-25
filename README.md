# ☕ Coffee Sales Dashboard 📊 (Excel Project)
 Overview
This Excel dashboard provides end-to-end analysis of coffee sales data across multiple years. It helps visualize key business metrics like total sales, top products, customer segmentation, and regional insights.

# Dataset Structure
The project is built on multiple Excel sheets:

orders: Transaction-level sales data

customers: Customer info (name, email, loyalty)

products: Product catalog with pricing and profit

TotalSales: Aggregated pivot table data

Top5Customers: Pre-calculated high-value customers

CountryBarChart: Sales per country

Dashboard: Final visual layout

# Project Steps

#  1️ Import & Clean Data
Load raw data into orders, customers, and products sheets.

Clean missing values, especially emails and country fields.

Add calculated column Sales = Quantity × Unit Price in orders.

#  2️ Data Integration
Use XLOOKUP/VLOOKUP or Power Query to bring in:

Product info (price, profit) into orders

Customer info (country, loyalty) into orders

#  3️ Create Pivot Tables
Create pivot tables in TotalSales, grouped by:

Year and Month

Coffee Type (Arabica, Robusta, etc.)

Create another pivot for:

Top 5 Customers by total sales

Country-wise sales totals

#  4️ Build Dashboard Visuals
On the Dashboard sheet, build:

Line chart: Monthly sales trends (TotalSales sheet)

Bar chart: Sales by country (CountryBarChart)

Pie chart: Sales by loyalty card or roast type

KPI cards: Total Sales, Avg Sale, Top Customer

#  5️ Add Interactivity
Add Slicers for Coffee Type, Year, Country, Roast Type

Use Conditional Formatting to highlight spikes in sales or profits

# Business Questions Answered
What are the top-selling coffee types over time?

Which customers and countries bring the highest revenue?

What product sizes or roasts yield the most profit?

How does loyalty card usage impact sales?

# Tools Used
Microsoft Excel

Pivot Tables

XLOOKUP / VLOOKUP

Charts (Line, Bar, Pie)

Slicers and Conditional Formatting
