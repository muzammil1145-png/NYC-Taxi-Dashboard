# 🚕 NYC Taxi Analytics Dashboard (Databricks)
## 📌 Overview
This project showcases an interactive analytics dashboard built in Databricks SQL to analyze NYC taxi trip data. The dashboard provides insights into trip demand, revenue patterns, geographic hotspots, and route flows using real-world data.
## 🎯 Objectives
* Identify high-demand pickup locations across NYC
* Analyze revenue trends and trip behavior
* Discover top-performing routes (pickup → dropoff)
* Understand relationships between fare, distance, and demand
## 🧰 Tech Stack
* Databricks SQL
* Delta Lake
* SQL (Aggregation, Window Functions)
* Data Visualization (Databricks Dashboards)
## 📊 Dashboard Features
🔹 KPI Analysis
* **Total Trips**: ~21.9K
* **Total Revenue**: ~$270.8K
* **Average Trip Distance**: ~2.85 miles
* **Top Pickup ZIP Code**: 10001
* **Top Route**: 10023 → 10023

🔹 Trend Analysis
* Revenue trends over time
* Trip distribution across weekdays
* Average trip distance by day

👉 **Example insight**: Demand peaks toward the end of the week, with noticeable fluctuations in daily revenue

## 📍 Key Insights
* ZIP 10001 generates the highest pickup demand
* Certain routes dominate short-distance, high-frequency travel
* Strong correlation between trip distance and fare amount
* Demand varies by weekday, with peaks toward weeken

## 🚀 Future Improvements
* Add A/B testing for pricing strategies
* Introduce demand forecasting models
* Enhance Sankey with revenue-based flows
* Add time-based hotspot filtering (peak hours)
