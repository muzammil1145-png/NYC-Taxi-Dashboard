# NYC Taxi Analytics Dashboard — Databricks SQL

**Databricks SQL · Delta Lake · Business Intelligence · Transportation Analytics**

This project analyzes NYC taxi trip activity in Databricks to identify demand patterns, revenue trends, high-volume pickup areas, and frequently traveled routes. The goal was to turn transactional trip data into a concise operational dashboard that demonstrates SQL analytics, KPI design, and business storytelling.

---

## Executive Summary

Using Databricks SQL and Delta Lake, I built an analytics workflow focused on trip demand, fare revenue, travel distance, and geographic movement across New York City. The final dashboard summarizes core transportation KPIs and highlights route and weekday patterns that can support operational planning and demand analysis.

### Portfolio Highlights

- Analyzed approximately **21.9K taxi trips**.
- Measured approximately **$270.8K in total fare revenue**.
- Calculated an **average trip distance of ~2.85 miles**.
- Identified **ZIP code 10001** as the highest-volume pickup area in the analyzed data.
- Identified **10023 → 10023** as the highest-frequency route.
- Used SQL aggregations and window-function techniques in Databricks to create dashboard-ready metrics.

---

## Business Questions

1. Where is taxi demand concentrated?
2. Which pickup and dropoff routes occur most frequently?
3. How does revenue change over time?
4. How does trip distance relate to fare behavior?
5. Which weekdays show stronger or weaker demand?

---

## Analytical Workflow

```text
NYC Taxi Trip Data
        │
        ▼
Delta / Databricks Tables
        │
        ▼
Databricks SQL Analysis
• aggregations
• route analysis
• time trends
• KPI calculations
        │
        ▼
Databricks Dashboard
• demand
• revenue
• trip distance
• geographic patterns
```

---

## Key KPIs

| KPI | Result |
| --- | ---: |
| Total Trips | ~21.9K |
| Total Revenue | ~$270.8K |
| Average Trip Distance | ~2.85 miles |
| Top Pickup ZIP | 10001 |
| Top Route | 10023 → 10023 |

---

## Dashboard Analysis

### Demand & Geography
- Compared pickup activity across NYC ZIP codes.
- Identified geographic areas with the highest observed trip demand.
- Evaluated recurring pickup-to-dropoff route patterns.

### Revenue & Trip Behavior
- Analyzed fare revenue over time.
- Compared trip distance with fare behavior.
- Reviewed daily and weekday variation in trip activity.

### Operational Insights
- Demand was not evenly distributed across locations or days.
- Certain short-distance routes appeared frequently in the dataset.
- Trip distance and fare amount showed a strong positive relationship.
- Weekday demand varied meaningfully across the observed period.

---

## Technologies & Skills

- Databricks SQL
- Delta Lake
- SQL aggregations
- Window functions
- KPI development
- Dashboard design
- Transportation analytics
- Data visualization
- Business storytelling

---

## Repository Contents

```text
NYC-Taxi-Dashboard/
├── README.md
├── NYC Taxi Analytics ... 23_50.pdf
└── NYC Taxi Analytics ... 23_52.pdf
```

The PDF files contain exported dashboard views from the Databricks analysis.

---

## What This Project Demonstrates

This project demonstrates my ability to move from raw transportation data to decision-ready reporting using a modern analytics platform:

**Data → SQL Analysis → KPI Development → Dashboard → Business Insight**

It is especially relevant to Data Analyst, BI Analyst, Analytics Engineer, and entry-level Data Engineering roles because it shows hands-on SQL and Databricks experience rather than only static visualization work.

---

## Future Improvements

- Add time-of-day demand analysis.
- Build incremental ingestion into Delta tables.
- Add demand forecasting by ZIP code.
- Add medallion-style Bronze / Silver / Gold transformations.
- Connect a downstream Power BI semantic model for cross-platform reporting.
