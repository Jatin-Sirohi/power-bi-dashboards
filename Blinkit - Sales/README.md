# Blinkit Grocery Sales Analytics Dashboard (Power BI)

<img width="1152" height="701" alt="Screenshot 2026-11-06 011649" src="https://github.com/user-attachments/assets/9574383c-c937-49b3-ab67-02c9df6324ce" />


A single-page Power BI dashboard analysing Blinkit grocery sales across 8,523 items, outlet types, outlet sizes and locations, with a filter panel and a metric selector.

## KPIs
- Total Sales, Average Sales, Number of Items and Average Rating

## Analysis
- **Fat content:** sales split between Low Fat and Regular items (donut chart) and fat content by outlet location tier (bar chart)
- **Item type:** sales by product category (bar chart)
- **Outlet size:** Small, Medium and High outlets by sales share (donut chart)
- **Outlet location:** sales by Tier 1, Tier 2 and Tier 3 locations (funnel chart)
- **Outlet establishment year:** sales trend by year (line chart)
- **Outlet type:** table comparing Total Sales, Average Sales, Number of Items, Average Rating and Item Visibility, with conditional formatting
- **Filter panel:** slicers for outlet location type, outlet size and outlet type, plus a metric selector (Total Sales, Avg Sales, No of Items, Avg Rating)

## Key insights from the dashboard
- Total sales are $1.20M, with Low Fat items at $776K and Regular items at $425K
- Tier 3 locations have the highest sales ($472K), followed by Tier 2 ($393K) and Tier 1 ($336K)
- Medium-sized outlets generate the largest share of sales (42.27%)
- Supermarket Type1 leads outlet types by total sales, and average ratings stay close to 3.9 across all outlet types
- Sales peaked for outlets established in 2018 ($205K)
- Fruit and snack categories are the two largest item types at about $0.18M each

## How it was built
- Data model with DAX measures for Total Sales, Average Sales, Number of Items and Average Rating
- Interactive filtering with slicers and a metric selector
- Custom layout with cards, charts, a pivot table, images and shapes

## Tech
Power BI, DAX, Data Modelling, Data Visualization

## Data
Blinkit grocery sales dataset with 8,523 item records: item type, fat content, item visibility, outlet size, outlet location type, outlet type, outlet establishment year, sales and rating.

## How to open
Download `BLINKIT DATA.pbix` and open it in Power BI Desktop (free).
