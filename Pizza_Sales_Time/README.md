# Pizza Sales Time Analysis Dashboard (Power BI)
<img width="1170" height="747" alt="first 2026-11-07 191956" src="https://github.com/user-attachments/assets/898530bb-ab0a-4736-accc-00546b5069ed" />


A single-page Power BI dashboard showing when pizza orders happen (by hour, day and time of day) and which pizzas and categories drive sales. It uses the same pizza sales data as the Pizza Sales Dashboard in this repository.

## Analysis
- **Orders by hour:** order volume across the hours of the day (bar chart)
- **Orders by day:** order volume for each day of the week (bar chart)
- **Total sales:** headline figure of 817.86K (card)
- **Orders by time of day:** split across Morning, Afternoon, Evening and Night (donut chart)
- **Quantity by pizza:** units sold per pizza (bar chart)
- **Sales by pizza:** total sales per pizza (bar chart)
- **Sales by category:** Classic, Supreme, Chicken and Veggie (treemap)

## Key insights from the dashboard
- Order volume peaks around midday (6.5K) and again in the early evening (5.4K)
- Friday is the busiest day (8.1K), followed by Saturday (7.4K) and Thursday (7.3K), while Sunday is the quietest (5.9K)
- Afternoon accounts for nearly half of all orders (24K)
- The Classic Deluxe Pizza sells the most units (2.5K)
- The Thai Chicken Pizza and The Barbecue Chicken Pizza lead sales at 43K each
- Classic is the top category by sales (220.05K), followed by Supreme (208.20K), Chicken (195.92K) and Veggie (193.69K)

## How it was built
- Measures for Orders and Total Sales
- Hour, day name and time-of-day fields to break orders down by time
- Seven visuals on one page, with a custom background

## Tech
Power BI, DAX, Data Visualization

## Data
Pizza sales data with order records, pizza names, categories and quantities.

## How to open
Download `Pizza Sales Time Analysis.pbix` and open it in Power BI Desktop (free).
