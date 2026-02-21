# 🌧️ Tamil Nadu Rainfall Metrics Dashboard | Power BI Project

## 📌 Project Overview

The Tamil Nadu Rainfall Metrics Dashboard is a Power BI project that analyzes rainfall trends across districts, months, and seasons in Tamil Nadu. The dashboard helps identify rainfall patterns, flood-prone districts, seasonal variations, and supports decision-making for agriculture, disaster management, and planning.

This project demonstrates complete data analysis workflow including data cleaning, transformation, modeling, DAX calculations, and dashboard visualization.

---

## 🎯 Objectives

- Analyze district-wise rainfall distribution
- Compare Actual Rainfall vs Normal Rainfall
- Identify flood-prone districts
- Analyze seasonal and monthly rainfall trends
- Provide rainfall-based planning insights

---

## 📊 Data Source

- Source: NITI Aayog National Data and Analytics Platform (NDAP)
- Domain: Weather Analytics / Climate Monitoring
- Duration: 2024 – 2025
- Granularity: Daily rainfall data

---

## 🧾 Dataset Features

| Column | Description |
|------|-------------|
| Date | Rainfall measurement date |
| District | District name |
| Month | Month name |
| Year | Reporting year |
| Actual Rainfall | Actual rainfall recorded (mm) |
| Normal Rainfall | Expected rainfall (mm) |
| % Departure | Difference from normal rainfall |
| Severity | Excess / Normal / Deficit |
| Season | Seasonal classification |

---

## 🛠️ Tools & Technologies Used

- Microsoft Excel – Data Cleaning
- Power Query – Data Transformation
- Power BI – Data Modeling & Visualization
- DAX – Measures and Calculated Columns

---

## 🧹 Data Cleaning & Transformation

- Removed duplicate records
- Handled missing values
- Standardized column names
- Converted data types
- Created Calendar table
- Built fact and dimension tables

---

## 🧱 Data Model

Star Schema Model was used:

### Fact Table
- Rainfall Metrics

### Dimension Tables
- District Table
- Calendar Table

### Relationships
- District → Rainfall Metrics
- Calendar → Rainfall Metrics

---

## 📐 DAX Measures Created

Examples include:

- Monthly Actual Rainfall
- Monthly Normal Rainfall
- Rainfall % Departure
- Flood Risk Indicator
- Seasonal Rainfall Classification
- Year-over-Year Rainfall Change

---

## 📊 Dashboard Features

The dashboard includes:

- Seasonal Rainfall Cards
- Rainfall Intensity Donut Chart
- Top Rainfall District Funnel Chart
- Actual vs Normal Rainfall Line Chart
- Flood Risk Map
- Seasonal Waterfall Chart
- Seasonal Comparison Ribbon Chart
- Travel Suggestion Card

---

## 🔍 Key Insights

- Monsoon contributes the highest rainfall
- Nilgiris, Coimbatore, and Mayiladuthurai receive high rainfall
- Several districts show rainfall deficit patterns
- Rainfall distribution varies significantly across seasons

---

## 📈 Business Impact

This dashboard helps:

- Identify flood-risk districts
- Support disaster management planning
- Help agriculture and irrigation planning
- Monitor seasonal rainfall trends
- Assist in weather-based decision making

---
