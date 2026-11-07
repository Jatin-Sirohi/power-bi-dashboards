# Live Weather & Air Quality Forecast Dashboard (Power BI)

<img width="1180" height="667" alt="Screenshot 2026-11-07 163919" src="https://github.com/user-attachments/assets/3d9ff388-e2dc-41be-8a44-7a08ffe3b600" />
<img width="1167" height="653" alt="Screenshot 2026-11-06 011234" src="https://github.com/user-attachments/assets/f38a442e-3110-46d5-8f12-305b95046de6" />


A single-page Power BI dashboard that shows current conditions, a 7-day forecast and air quality, using live data pulled from WeatherAPI.com.

## What it shows
- **Current conditions:** temperature, weather condition, humidity, wind speed, visibility, pressure, UV index and precipitation
- **7-day forecast:** daily temperature strip and a forecast line chart
- **Chance of rain:** day-wise bar chart
- **Air quality:** index with PM10, PM2.5, CO, NO2, O3 and SO2 readings
- **Sunrise and sunset** times
- **Location selector** for 6 cities: Meerut, Moradabad, Ludhiana, Amritsar, Chandigarh and Hyderabad

## How it works
- Data is fetched from the WeatherAPI.com forecast endpoint (7-day forecast with air quality enabled) as JSON and loaded into Power BI with Power Query, which flattens the nested fields into columns
- Custom DAX measures and columns drive the wind-speed card, the PM10 gauge, the chance-of-rain bars and the weekday labels
- Custom layout with cards, slicers, images and shapes

## Tech
Power BI, DAX, Power Query, REST API data (WeatherAPI.com)

## Data freshness
This project uses a free WeatherAPI.com key. The dashboard refreshes from the API whenever a valid key is configured, and the data currently saved in the file is from the last refresh on 24 Jan 2026.

## How to open and refresh
1. Download `Weather.pbix` and open it in Power BI Desktop (free).
2. No API key is included in this file. Get a free key from weatherapi.com and enter it in Power Query under Transform data, then Advanced Editor, then click Refresh.
