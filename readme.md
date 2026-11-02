# Adventure Works Sales Dashboard

An interactive Power BI dashboard that analyses sales, profit and customer trends for Adventure Works.

## Problem
Management needs a quick view of how sales and profit are performing across products, regions and time, and which customers and categories drive the most revenue and what is the return rate (specially over which product).

## Dataset
- Source: Microsoft Adventure Works sample dataset
- Tables used: Sales data (2020-2022), Calendar lookup, customer lookup, Product category lookup, Prduct lookup, Product subcategories lookup, Returns data, Territory lookup.

## Tools Used
Python(Pandas and numpy), Power BI, DAX, Power Query, Data Modelling

## What I Did
- Cleaned and transformed the data in Python using pandas and numpy
- Built a star-schema data model with relationships between fact and dimension tables
- Created DAX measures such as Total Sales, Total Profit, Profit Margin %, [and YoY Growth]
- Designed an interactive dashboard with KPI cards, charts and slicers for [year, region, category]

## Key Findings
- Retained revenue was $1,176.65 across 20 orders, after discounts and excluding returned orders.
- The overall return rate was 15%: 3 of 20 orders were marked returned.
- Home was the top category by retained revenue, contributing $523.55—about 45% of the total. Clothing contributed $347.68, and Electronics $305.42.
- Electronics had the most returned orders: 2 of 7 orders (about 29%). Clothing had 1 of 6 returned (about 17%); Home had none of 7.
- Seattle had the most orders, with 8 of 20 (40%), followed by Portland with 6. Boise and Spokane had 3 each.
- Average shipping time was 3.65 days.

## Screenshots
![Dashboard Overview](images/dashboard-overview-1.png, images/dashboard-overview-2, images/dashboard-overview-3, images/dashboard-overview-4)

## How to View
Download `Adventure_Works_Dashboard.pbix` and open it in Power BI Desktop (free download from Microsoft).

## Author
Gopal Mukherjee