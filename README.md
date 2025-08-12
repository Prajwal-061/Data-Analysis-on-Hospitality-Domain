🏨 Hotel Booking Data Analysis

📌 Project Overview:

This project focuses on exploring, cleaning, transforming, and analyzing hotel booking datasets to uncover patterns, detect anomalies, and generate actionable business insights.
The dataset contains multiple CSV files with information about hotel properties, bookings, room categories, and aggregated booking data.
Through data exploration, cleaning, transformation, and visualization, this project answers key business questions such as:
Which cities and room categories have the highest occupancy rates?
Do weekends perform better than weekdays?
Which months generate the most revenue?
Are there anomalies in bookings or revenue records?

📂 Dataset Description:

The analysis uses the following CSV files (stored in the datasets folder):
fact_bookings.csv – Detailed booking transactions (dates, guests, revenue, etc.).
fact_aggregated_bookings.csv – Aggregated booking and capacity data.
dim_hotels.csv – Information about hotel properties (city, category, etc.).
dim_rooms.csv – Room category details.
dim_date.csv – Calendar reference for mapping dates.

🛠 Steps Performed

1. Data Exploration
   Loaded and inspected all datasets.
   Checked dataset sizes, unique values, and overall structure.
   Visualized booking platform distribution.
   Identified hotel distribution by city and category.

2. Data Cleaning
   Removed bookings with negative or zero guests.
   Detected and removed extreme revenue outliers using the Z-score (3σ rule).
   Validated no negative revenue entries.
   Handled anomalies in revenue_generated and revenue_realized.

3. Data Transformation
   Merged datasets for unified analysis.
   Derived new metrics (occupancy rate, monthly revenue, etc.).
   Grouped and aggregated data by city, date, and room category.

4. Insights Generation
   Occupancy Analysis:
   Average occupancy rate per room category.
   City-wise occupancy rate.
   Weekday vs. weekend performance.
   Monthly occupancy trends (example: June city-wise performance).
   Revenue Analysis:
   Revenue per city.
   Month-by-month revenue trends.

📊 Key Findings:

Certain room categories consistently outperform others in occupancy.
Weekends generally have higher occupancy rates than weekdays.
Peak revenue months vary by city, with some seasonal trends.
Outlier bookings existed with unrealistic revenue figures, requiring data cleaning.

📈 Technologies Used:

Python
Pandas – Data manipulation and analysis.
Matplotlib – Data visualization.
Jupyter Notebook – Interactive analysis environment.

📌 Future Improvements:

Automate data cleaning pipeline for new datasets.
Create an interactive Streamlit dashboard for live hotel performance monitoring.
Add forecasting models for revenue and occupancy.

📜 License:

This project is for educational and analytical purposes.

THis is a trial.
