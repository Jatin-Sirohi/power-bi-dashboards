# Multi-Year Sales Dashboard (Power BI)

<img width="1167" height="617" alt="multiple12026-11-07 192233" src="https://github.com/user-attachments/assets/045b6e23-2445-4269-b8f1-1b2267a7dc70" />


A two-page Power BI dashboard analysing retail sales across 1997 and 1998 by quarter, sales region and product brand.

## Pages
- **Page 1:** quarterly sales trend, total sales by region and each brand's share of total sales
- **Page 2:** pivot table view of the sales data

## Analysis
- **Quarterly sales trend:** daily net sales summed by quarter across 1997 and 1998 (area line chart)
- **Sales by region:** total sales for each sales region (column chart)
- **Brand share:** each product brand's percentage of grand total sales (column chart)

## Key insights from the dashboard
- Quarterly net sales peaked in October 1997 (61.0K) and dropped to their lowest in January 1998 (44.2K), then recovered to 57.8K by October 1998
- North West is the largest sales region by far (338.7K), more than 2.5 times the next region, Mexico Central (132.0K)
- Central West is the smallest region (3.8K)
- Hermanos is the top brand with 12.12% of total sales, followed by Tell Tale (11.04%) and Ebony (10.66%)
- Brand shares are close together: the top 10 brands each hold between 8.59% and 12.12%

## How it was built
- Time-based view of daily net sales by year and quarter
- Regional and brand breakdowns, with brand share shown as a percentage of the grand total
- Pivot table for detailed figures

## Tech
Power BI, Data Visualization

## Data
Retail sales data for 1997 to 1998, with daily net sales, total sales, sales region and product brand.

## How to open
Download `multi_year_sales_dashboard.pbix` and open it in Power BI Desktop (free).
