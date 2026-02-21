# Sales-Dashboard-with-maps.
This dashboard provides an overview of sales performance across countries, cities, products and time.
This Power BI dashboard answers key business questions such as:

- Which countries and cities generate the highest sales? (e.g., Uzbekistan, USA, France, Germany, Spain)
- Which products perform best? (Laptop, Tablet, Printer, Phone, Monitor)
- What are the total sales, quantity sold, and average metrics?
- How are sales distributed geographically? (interactive world map with bubbles)
- How do sales trends change over time? (year-over-year growth, monthly filtering)

## Features

- Interactive slicers – filter by month, product, region, etc.
- World map visual – bubble markers sized and colored by sales/quantity (latitude & longitude based)
- Bar/column charts – average sales by country, quantity by product
- KPI cards – instant view of total sales, quantity, top city/product
- Purple-themed design – modern and visually appealing dark map style
- Dynamic insights – hover tooltips, cross-filtering between visuals

## Technologies Used

- Power BI Desktop (or Power BI Service)
- Power Query – for data cleaning and transformation
- DAX – calculated measures (Total Sales, Average Sales, YoY Growth, etc.)
- Data Source: Excel (.xlsx) with columns: City, Country, Date, Latitude, Longitude, Product, Quantity, Sales, Region, State/Province
