# Hospital Performance Analysis Dashboard
## Project Overview
This project provides a comprehensive analysis of patient admissions and hospital efficiency across 90 facilities. The dashboard was designed to help healthcare administrators monitor patient demographics, stay durations, and volume trends from 2023 through 2026.

## Key Features
Executive Summary: High-level KPIs showing Total Admissions (5K), Average Stay (5 days), and Long-stay Patient percentage (48.4%).

Patient Demographics: Breakdown by Gender and Age Groups (Infant, Young Adult, Middle-aged, Senior) using donut and pie charts.

Trend Analysis: A line chart tracking patient volume growth/decline over a 4-year period.

Operational Efficiency: A ranked bar chart of 90 hospitals to identify outliers in stay duration.

Correlation Study: A scatter plot comparing "Stay Duration" vs. "Total Patients" by diagnosis to spot resource bottlenecks.

## Technical Stack
Tool: Power BI Desktop

Data Transformation: Power Query (M) for data cleaning and binning patient ages.

Data Modeling: Star Schema with a central Fact table and Dimension tables for Hospitals and Calendar.

DAX Measures: * Avg Hospital Stay = AVERAGE(Fact_Admissions[Stay_Days])

Long Stay % = DIVIDE(CALCULATE(COUNT(…), [Stay] > 7), COUNT(…))

## How to Use
Download the Hospital_Performance.pbix file.

Open with Power BI Desktop.

Use the Filter Panel at the top to toggle between Age Bins, Gender, and Year to see dynamic updates.
