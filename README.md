# BDA-Big-Data-Analytics-4-1

# Netflix User Behavior Analysis

## Overview

This project analyzes **Netflix user behavior** using a dataset of **10,300 users**. It focuses on demographics, subscription patterns, spending habits, and device usage.

The goal is to understand user trends and provide actionable recommendations.

 ┌──────────────────────────┐
 │ User Activities           │
 │ (Watch history, clicks,   │
 │ search, ratings, likes)   │
 └─────────────┬─────────────┘
               │
               ▼
 ┌──────────────────────────┐
 │ Data Collection           │
 │ (Logs, APIs, Devices)     │
 └─────────────┬─────────────┘
               │
               ▼
 ┌──────────────────────────┐
 │ Data Storage              │
 │ (HDFS, Cloud DB, NoSQL)   │
 └─────────────┬─────────────┘
               │
               ▼
 ┌──────────────────────────┐
 │ Data Processing           │
 │ (Hadoop / Spark for ETL,  │
 │ cleaning, aggregation)    │
 └─────────────┬─────────────┘
               │
               ▼
 ┌──────────────────────────┐
 │ Data Analysis             │
 │ - Viewing patterns        │
 │ - Recommendation models   │
 │ - Churn prediction        │
 └─────────────┬─────────────┘
               │
               ▼
 ┌──────────────────────────┐
 │ Insights & Actions        │
 │ - Personalized content    │
 │ - Better recommendations  │
 │ - User retention strategy │
 └──────────────────────────┘

---

## Dataset

* **File:** `users.csv`
* **Records:** 10,300
* **Columns include:**

  * Age, Gender, Country, State, City
  * Subscription Plan, Subscription Start Date, Active Status
  * Monthly Spend, Primary Device, Household Size
  * User details (ID, Email, Name, Created At)

---

## Analysis Performed

* Data Cleaning (missing values, duplicates, outliers)
* Descriptive Statistics (mean, median, distributions)
* Visualizations (histograms, bar charts, pie charts, scatter plots, boxplots)
* Relationship Analysis (Age vs Spend, Plan vs Device, Country vs Plan)

---

## Key Findings

* Majority of users are **20–40 years old**.
* **Standard plan** is most common, followed by Premium+.
* **Laptop & Mobile** dominate as primary devices.
* Average monthly spend is around **$27**.
* USA, UK, India, and Canada have the largest user base.

---

## Recommendations

* Offer **family bundles** for large households.
* Improve **mobile streaming quality** for younger users.
* Launch **senior-friendly plans** for older audiences.
* Review outliers in spending (> $80).

---

## Tools Used

* Python (Pysark, Pandas, NumPy)
* Matplotlib, Seaborn
* Jupyter Notebook

---
