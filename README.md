# Hospital Patient Data Analysis & Efficiency Tracking

## 📊 Project Overview
This project provides a comprehensive analysis of hospital performance and patient demographics across a network of 90 facilities. Using a dataset of 5,000 records, I built a data pipeline that transitions from raw data cleaning in **Python** to an interactive dashboard in **Power BI**. The goal was to identify operational trends, patient admission patterns, and hospital efficiency benchmarks.

## 🛠️ Tech Stack
* **Data Cleaning & Processing:** Python (Pandas, NumPy)
* **Statistical Analysis:** Python (Matplotlib, Seaborn)
* **Data Visualization:** Power BI (DAX, Power Query)
* **Documentation:** Microsoft Word (Technical Reporting)

## 📁 Repository Structure
* `data/`: Contains the hospital patient dataset (CSV).
* `notebooks/`: `hospital.ipynb` - Python script for data audit, cleaning, and preliminary EDA.
* `dashboard/`: `Hospital Dashboard.pbix` - Interactive Power BI report.
* `reports/`: Full technical report detailing observations and insights.

## 🔍 Key Insights & Features
* **Data Transformation:** Converted categorical date strings into datetime objects and calculated "Length of Stay" (LOS) metrics.
* **Demographic Analysis:** Visualized patient distribution by Gender and Age (Average age: 41.5 years).
* **Admission Trends:** Identified a peak in admissions during 2024 and analyzed the 2026 data "incomplete data" anomaly.
* **Efficiency Benchmarking:** Created a ranking system for 90 hospitals based on average stay duration to identify high-performing facilities.
* **Correlation Mapping:** Used scatter plots to correlate diagnosis volume with resource-heavy stay durations (5.3–5.7 days avg).

## 🖥️ Dashboard Preview
![Hospital Dashboard](Hospital%20Dashboard.jpg)

## 🚀 How to Use
1. **Python Analysis:** Run the `hospital.ipynb` to see the data cleaning steps and statistical validation.
2. **Interactive Report:** Open the `.pbix` file in Power BI Desktop to filter data by diagnosis, year, or hospital ID.
