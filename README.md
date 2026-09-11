# Electronic-Sales-Performance-Dashboard-using-Tableau
An interactive Tableau dashboard built to transform electronic-sales records into a clear view of sales trends, product performance, geographic results, and warranty timelines.

Rather than presenting disconnected charts, the dashboard brings the most important business questions into one analytical experience: When are sales strongest? Which products lead or lag? Where is revenue coming from? And which purchases are approaching the end of their warranty period?

✨ What the Dashboard Explores
The dashboard combines five focused analytical views:

1. Weekly Total Sales
Examines total sales revenue across the days of the week, making it easier to identify strong and weak trading periods.

2. Weekly Average Sales
Shows average sales by weekday, offering a second perspective that is less influenced by transaction volume alone.

3. Products by Sales Revenue
Ranks products according to their sales contribution. A dynamic parameter allows users to switch between:

Top 10 products
Bottom 10 products
This helps highlight both leading products and potential underperformers.

4. City Sales Measure
Compares sales performance across cities. Users can switch the metric between:

Total Sales
Average Sales
The comparison helps distinguish cities generating the most overall revenue from those producing stronger average transaction values.

5. Warranty End Date
Provides order-level warranty tracking. Each warranty end date is calculated as six months after the original order date, supporting after-sales follow-up and warranty monitoring.

🎛️ Interactive Features
Dynamic Top 10 / Bottom 10 product ranking
Toggle between total and average city sales
Cross-filtering between dashboard views
Product, city, date, and warranty-based exploration
Automatic exclusion of incomplete records
Currency-formatted sales measures
Detailed order-level warranty information
Selections made in one view can filter related views, allowing users to move from a high-level pattern to a more focused investigation.

💡 Business Questions Supported
This dashboard is designed to help users investigate questions such as:

- Which weekdays generate the strongest total and average sales?
- Which products are the highest and lowest revenue contributors?
- Which cities lead by total sales?
- How does city performance change when average sales are considered?
- Which orders have upcoming or recently reached warranty end dates?
- How do product, city, and time-based selections affect the broader sales picture?
- Because the workbook file contains the dashboard logic rather than the underlying sales values, specific findings should be confirmed after reconnecting the source data.

🛠️ Tools & Techniques
Tableau Desktop 2023.1
Data preparation and validation
Calculated fields
Parameters
Dense ranking and table calculations
Interactive dashboard actions
Cross-filtering
Date calculations
Geographic segmentation derived from address data
