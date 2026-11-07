# Pizza Sales Dashboard (Power BI)
<img width="1295" height="736" alt="Screenshot 2026-11-07 191228" src="https://github.com/user-attachments/assets/9da868d7-7781-43e6-8ea8-3e8ea95be5e5" />
<img width="1297" height="735" alt="Screenshot 2026-11-07 191307" src="https://github.com/user-attachments/assets/7d9b0a5c-c508-43b5-ba9b-f2518cc974e9" />


A two-page Power BI dashboard analysing a full year of pizza sales (January to December 2015), with page navigation, KPI cards, trend charts and best/worst seller comparisons.

## Pages
- **HOME:** KPIs, busiest days and months, and sales contribution by pizza category and size
- **BEST/WORST:** top 5 and bottom 5 pizzas by revenue, quantity and total orders

## KPIs
- Average Order Value: 38.31
- Average Pizzas per Order: 2.32
- Total Orders: 21.35K
- Total Pizzas Sold: about 50K
- Total Revenue: 817.86K

## Analysis
- **Daily trend:** total orders by day of the week (column chart)
- **Monthly trend:** total orders by month (area chart)
- **Sales by category:** share of sales by pizza category (donut chart)
- **Sales by size:** share of sales by pizza size (donut chart)
- **Pizzas sold by category:** funnel chart
- **Best and worst sellers:** six bar charts ranking the top 5 and bottom 5 pizzas by revenue, quantity and total orders

## Key insights from the dashboard
- Friday is the busiest day for orders (3.5K), followed by Thursday and Saturday (3.2K each)
- Monthly orders peak in July (1,935) and are lowest in October (1,646)
- Classic is the largest category by sales (26.91%) and by pizzas sold (14,888), followed by Supreme, Chicken and Veggie
- Large pizzas contribute the most sales (45.89%), followed by Medium (30.49%) and Regular (21.77%)
- The Thai Chicken Pizza and The Barbecue Chicken Pizza lead on revenue (43K each), while The Classic Deluxe Pizza leads on quantity sold and total orders
- The Brie Carre Pizza ranks last on revenue (12K), quantity (490) and total orders (480)

## How it was built
- DAX measures for Average Order Value, Average Pizzas per Order, Total Orders, Total Pizzas Sold and Total Revenue
- Day-name and month-name fields for the trend charts
- Page navigation buttons, text insight panels and a custom colour layout

## Tech
Power BI, DAX, Data Visualization

## Data
Pizza sales data for January to December 2015, with order records, pizza names, categories, sizes and quantities.

## How to open
Download `Pizza Double Dashboard.pbix` and open it in Power BI Desktop (free).
