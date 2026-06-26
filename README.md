# Blinkit Grocery Data Analysis Dashboard

An end-to-end Power BI business intelligence project analyzing the sales performance, customer satisfaction, and inventory distribution of Blinkit (instant-grocery commerce). This project transforms raw transactional data into interactive, executive-level insights driven by dynamic business metrics.

## 📊 Dashboard Preview
![Blinkit Dashboard Performance](https://github.com/saiGx007/BlinkitDataAnalysis/blob/main/DashBoard.png)

---

## 🚀 Project Overview & Objectives
The goal of this project is to analyze Blinkit's grocery data to uncover performance trends, optimize inventory placement based on outlet sizing, and evaluate sales across different geographic tiers. 

By building a centralized **Metrics parameter framework**, the dashboard allows stakeholders to seamlessly track four core Key Performance Indicators (KPIs) across every single visual component seamlessly.

---

## 🛠️ Repository Structure
*   `BlikitGrocerydata.xlsx` - Raw, comprehensive grocery dataset.
*   `BlinkitDataAnalysis.pbit` - Power BI Template file housing the data model, transformations, and visual layouts.
*   `screenshot of dashboard.png` - High-resolution snapshot of the final polished UI.

---

## ⚡ Data Pipeline & Engineering Steps

### 1. Data Transformation (Power Query)
Before building visuals, the raw `BlikitGrocerydata.xlsx` sheet was loaded into Power Query for rigorous data cleansing:
*   **Quality Check:** Screened for missing/null values and eliminated data redundancies to maintain data integrity.
*   **Schema Standardization:** Verified and corrected column data types (text, numerical, decimals) ensuring optimized memory storage and accurate calculations.

### 2. KPI Engineering
Using Data Analysis Expressions (DAX), four foundational business performance calculations were established:
*   **Total Sales:** Aggregated revenue generated across all categories.
*   **Average Sales:** Calculated the mean revenue per transaction.
*   **Average Rating:** Evaluated overall customer satisfaction scores.
*   **Number of Items:** Maintained a distinct count of the operational inventory volume.

### 3. Dynamic Metrics Consolidation
*   Engineered a dedicated configuration layer to bind **Total Sales, Avg Sales, Avg Rating, and No. of Items** into a singular switchable matrix. 
*   This enabled an interactive user interface where all dashboard charts automatically adapt context based on the highlighted metric.

---

## 🎨 Dashboard Architecture & Visual Elements

The dashboard is structured with a clean, high-contrast, modern UI/UX layout featuring individual high-impact analytical views:

| Visual Type | Business Insight Delivered |
| :--- | :--- |
| 📇 **KPI Cards** | Dedicated micro-cards displaying high-level summaries for all core metrics at a glance. |
| 🍩 **Fat Content Breakdown (Donut)** | Evaluates the distribution of item performance categorized by low-fat vs. regular variations. |
| 📊 **Outlet Tier Assessment (Clustered Bar)** | Breaks down metrics across geographical regions segmented by **Tier 1, Tier 2, and Tier 3** outlets. |
| 📦 **Item Type Distribution (Stacked Bar)** | Ranks product performance across granular sub-categories (Fruits, Dairy, Snacks, etc.). |
| 📈 **Historical Performance (Line Chart)** | Tracks growth trajectories across different **Outlet Establishment Years**. |
| 🎯 **Outlet Sizing Impact (Donut)** | Correlates performance efficiency based on store footprint size (Small, Medium, High). |
| ⏳ **Location Efficiency (Funnel)** | Visualizes transactional flow through the organizational supply chain based on geographical placement. |
| 🧮 **Comprehensive Matrix** | A deep-dive cross-tabulation detailing **Outlet Type** performance across every single dynamic metric. |

### 🎛️ Interactive Controls
*   **Advanced Slicers & Filters:** Seamlessly embedded into the canvas to allow end-users to drill down by dates, categories, or regions instantly while preserving the clean visual layout.

---

## 🧠 Key Technical Skills Demonstrated
*   **Data Preparation:** Data Cleansing, Data Profiling, Power Query (M Language).
*   **Data Modeling:** Variable Metric Frameworks, Relational Data Mapping.
*   **UX/UI Design:** Color Palette Harmony, Information Hierarchy, Scannability, Interactive Canvas Controls.
*   **Business Intelligence:** Executive Dashboards, Trend Tracking, Descriptive Analytics.
