# Pune CityMotion: Urban Mobility & Public Transit Analytics

An end-to-end urban mobility and public transit analytics project evaluating traffic congestion, bus punctuality, travel time variability, and incident impacts across 25 monitored corridors in Pune.

---

## 📌 Problem Statement
Urban bus corridors in Pune experience recurring peak-hour slowdowns, high passenger loads, schedule delays, and unexpected disruptions from traffic incidents. The objective of this project is to analyze telemetry data, identify high-priority bottleneck corridors, and provide actionable transit and infrastructure planning recommendations.

---

## 📊 System Baseline & Key Findings
* **Average Speed:** ~36.5 km/h across monitored corridors.
* **Average Congestion Index:** ~27.3% (speed loss relative to free-flow speeds).
* **Transit On-Time Performance (OTP):** ~73.0% (buses arriving within 5 minutes of schedule).
* **Average Bus Load Factor:** ~64.5% passenger capacity occupancy.
* **Travel Time Variability:** ~9.43 minutes standard deviation across trips.
* **Peak Congestion:** Weekdays experience higher congestion (30.4%) compared to weekends (24.2%).
* **Incident Impact:** Signal failures and roadwork drop speeds to ~17 km/h and increase bus delays up to 14.7 minutes (vs. 3.7 minutes under normal conditions).

---

## 🛠️ Tech Stack & Tools
* **Python** (`pandas`, `numpy`, `matplotlib`, `seaborn`, `folium`, `duckdb`) — Data cleaning, SQL queries, statistical analysis, interactive map generation.
* **Microsoft Power BI** — Dynamic 3-page interactive dashboard (KPI cards, hourly speed line charts, corridor bar charts, incident column charts, scorecard tables with conditional formatting, and slicers).
* **Google Colab** — Exploratory data analysis, SQL query execution, data export workflow.

---

## 📂 Repository Structure
```text
pune-citymotion-mobility-analysis/
├── README.md
├── Pune_CityMotion_Dashboard.pbix
├── Pune_CityMotion_Dashboard.pdf
├── Monthly_Planning_Insight_Report.pdf
├── project1.ipynb
├── data/
│   ├── citymotion_pune_realtime.csv
│   ├── dashboard_corridor_scorecard.csv
│   ├── dim_corridors.csv
│   ├── dim_time.csv
│   └── fact_incidents.csv
└── screenshots/
    └── dashboard_preview.png
