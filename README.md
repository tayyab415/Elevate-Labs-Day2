# Elevate-Labs-Day2
# Video Game Sales Dashboard Methodology

## Dataset and Dashboard Links
- [Dataset](https://github.com/tayyab415/Elevate-Labs-Day2/blob/main/vgsales.csv)  : 'vgsales.csv'
- [Dashboard(Download)](https://github.com/tayyab415/Elevate-Labs-Day2/blob/main/dashboard-elevatellabs-day2.pdf) : 'elevatellabs-day2.pdf'
 
## Data Preparation
- **Source**: Used a video game sales dataset (e.g., from Kaggle) with columns: Name, Platform, Year, Genre, Publisher, Global_Sales.
- **Cleaning**: Removed missing/duplicate entries, standardized platform/publisher names, filtered years (1980-2020), ensured correct data types.
- **Calculations**: Aggregated Global_Sales for trends and rankings.

## Dashboard Design
1. **Sales by Genre & Year**: Stacked area chart showing sales (Y-axis) over years (1980-2020, X-axis), colored by genre.
2. **Dataset Stats**: Text boxes for total names (11,493), publishers (579), platforms (31), genres (12).
3. **Top 10 Publishers by Sales**: Horizontal bar chart, sales by publisher (e.g., Nintendo: 1,784M).
4. **Top 10 Platforms by Sales**: Grid of boxes (e.g., PS2, PS3, Wii).
5. **Top 10 Names by Sales**: Vertical bar chart, sales by game (e.g., Wii Sports: 82.74M).

## Interactivity
- **Filters**: Zone Sales (default: Global), Genre (default: All), Date Range (1980-2020 sliders).
- **Purpose**: Allow users to explore specific genres, regions, and time periods.

## Analysis
- **Trends**: Sales peaked in 2008-2010 (~600M), declined post-2010. Action genre led.
- **Top Performers**: Nintendo (publishers), PlayStation platforms, Wii Sports (games).
- **Challenges**: Managed overlapping genres with filters, optimized performance by pre-aggregating data, adjusted labels for readability.

## Conclusion
The dashboard provides a clear overview of video game sales trends, top performers, and genre dynamics from 1980 to 2020, with interactive filters for deeper analysis.
