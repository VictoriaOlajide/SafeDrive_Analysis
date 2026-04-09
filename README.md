# SafeDrive Ride-Hailing Analysis – Lagos, Nigeria

**End-to-End Exploratory Data Analysis (EDA)**

A comprehensive analysis of ride-hailing operations in Lagos using a realistic synthetic dataset for SafeDrive — a fictional, driver-friendly ride-hailing app.

### Project Overview
**Objective**: Understand fare structure, driver profitability, operational challenges, and key factors affecting ride-hailing in Lagos (congestion, island premium, weather, time of day).
**Dataset**: 100 synthetic rides with verified Lagos distances, fuel price at Feb 2026 (₦820 per liter), Toyota Corolla efficiency (12 km/l), 15% platform commission, and realistic congestion & weather effects.
**Key Focus Areas**: Pricing dynamics, driver net earnings after fuel & commission, time-based patterns, and island vs mainland differences.

### Key Insights
**Island Premium**: Rides originating from island areas (Lekki, Victoria Island, Ikoyi, Ajah) have significantly higher fares (statistically significant, p < 0.01).
**Congestion Impact**: High congestion increases rider fares but reduces driver earnings per hour due to longer trip durations and higher fuel consumption.
**Weather Effect**: Rainy conditions lead to higher fares and demand, but lower driver efficiency because of slower speeds and increased fuel costs.
**Peak Hours**: Morning (7–10 AM) and evening (5–9 PM) rushes show the highest ride volume and congestion.
**Driver Profitability**: On average, platform commission + fuel cost consume a substantial portion of the rider’s payment, leaving drivers with lower net take-home, especially during peak congestion

### Technologies Used
**Python**: pandas, matplotlib, seaborn, plotly, scipy, statsmodels
**Visualization**: Interactive scatter plots, boxplots, heatmaps, and time-series line charts

### Visualizations Included
- Fare vs Distance by Congestion Level
- Driver Earnings per Hour by Time of Day and Day of Week
- Island Pickup vs Non-Island Fare Comparison
- Weather Impact on Fare and Trip Duration
- Demand Heatmap (Hour vs Day of Week)
- Rolling 7-day Moving Averages for Ride Volume and Earnings

 ### Files in Repository
- SafeDrive_Ride_Hailing_EDA.ipynb → Full interactive notebook
- safedrive_100_rows.csv → Dataset used for analysis
- SafeDrive_EDA_Report.html → Clean HTML export (for easy viewing)

Author: Victoria  
Date: April 2026  
Portfolio Purpose: Demonstrating end-to-end EDA, statistical testing, and business insights in the ride-hailing / mobility domain.
