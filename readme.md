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
- Sales value is concentrated in Bikes: Bikes account for about 94.9% of estimated sales—approximately $23.64M—but only 13,929 units.
- Accessories lead in unit volume: Accessories account for 57,809 units, about 68.7% of all units sold, but only around 3.6% of estimated sales. This shows why unit volume and sales value tell different stories.
- Australia is the largest territory by estimated sales: about $7.42M, or 29.8% of the total.
- Returns: the source records 1,828 returned units. Compared with 84,174 units sold, that is about 2.2% as a period-level comparison—not a true return rate, because returns can’t be linked to their original orders.
- Time coverage matters: sales run through June 30, 2022, so 2022 is a partial year. Avoid presenting a direct full-year comparison with 2020 or 2021 as if the periods were equivalent.

## Screenshots
![Dashboard Overview](images/dashboard-overview-1.png, images/dashboard-overview-2, images/dashboard-overview-3, images/dashboard-overview-4)

## How to View
Download `Adventure_Works_Dashboard.pbix` and open it in Power BI Desktop (free download from Microsoft).

## Author
Gopal Mukherjee
