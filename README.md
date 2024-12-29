## Hospitality Domain Dashboard

![image](https://github.com/user-attachments/assets/d1b247cc-2c95-477d-8e3e-03521809da96)

### Overview
This repository contains the documentation for a hospitality domain PowerBI dashboard. The dashboard provides insights into various metrics related to hotel bookings, revenue, and occupancy. The project includes the use of DAX formulas to create custom measures and leverages different visualizations to present the data effectively.

### Dashboard Components
### Tables
dim_date: Dimension table containing date-related information.
dim_hotels: Dimension table with details about different hotels.
dim_rooms: Dimension table containing information about various rooms.
fact_aggregated_bookings: Fact table with aggregated booking data.
fact_bookings: Fact table containing detailed booking information.

### Visualizations
Line Chart - Trends by Metrics: Visualizes trends over time for selected metrics.
Donut Chart - % Revenue by Category: This represents the percentage distribution of revenue across different categories.
Cards:
Revenue
RevPAR (Revenue Per Available Room)
DSRN (Daily Sales Revenue per Night)
Realisation %
ADR (Average Daily Rate)
Occupancy %
Line and Stacked Columns Chart - Realisation % and ADR by Platform: Compares Realisation % and ADR across different platforms.

### Tooltips
Tooltips have been implemented to provide additional context and details when interacting with visualizations. Hover over data points to view dynamic information such as specific values, trends, and other relevant insights.

### DAX Formulas
Implemented custom measures using Data Analysis Expressions (DAX) to derive meaningful insights from the data.

DAX Formulas
Implemented custom measures using Data Analysis Expressions (DAX) to derive meaningful insights from the data.
