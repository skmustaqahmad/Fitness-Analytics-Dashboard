# Fitness-Analytics-Dashboard

🏋️‍♂️📊 Fitness Analytics Dashboard – Power BI Project
📌 Project Overview

The Fitness Analytics Dashboard is an interactive Power BI project designed to analyze daily, weekly, and monthly fitness activities.
It transforms raw fitness tracking data into clean, insightful visualizations that help users understand their workout patterns, calories burned, step count, and overall performance trends.

This project demonstrates skills in data cleaning, data modeling, DAX calculations, visualization design, and dashboard storytelling.

🎯 Objectives

Analyze fitness activity trends using interactive visual dashboards

Track key health indicators such as calories, steps, heart rate, and workout intensity

Provide users with actionable insights for improving fitness performance

Build a modern, intuitive, user-friendly BI solution using Power BI

📊 Dashboard Features
✔️ 1. KPI Highlights

Total Steps

Total Calories Burned

Average Workout Duration

Daily/Weekly/Monthly Active Minutes

✔️ 2. Activity Trends

Daily activity pattern

Weekly and monthly performance breakdown

Steps trend line

Calories trend area chart

✔️ 3. Workout Insights

Workout type distribution (e.g., Cardio, Strength, Running, Walking)

Intensity levels (Low / Moderate / High)

Heatmap showing activity frequency

✔️ 4. Interactive Filters

Date range slicer

Workout type filter

Activity category filter

🛠️ Tech Stack Used

Power BI Desktop

Power Query (ETL, Data Cleaning)

Data Modeling (Star schema)

DAX (Custom measures, calculated columns)

🧹 Data Cleaning & Preparation

In Power Query, the following cleaning steps were performed:

Removed duplicates and null values

Standardized date formats

Converted text columns to appropriate data types

Created new calculated fields for activity duration, calories per minute, etc.

Built relationships between activity tables for accurate modeling

🧮 DAX Measures Used

Some key DAX measures created:

Total Steps = SUM(Fitness[Steps])

Total Calories = SUM(Fitness[Calories])

Average Workout Duration = AVERAGE(Fitness[Workout Duration])

Steps Trend % = 
    DIVIDE(
        SUM(Fitness[Steps]) - CALCULATE(SUM(Fitness[Steps]), DATEADD(Fitness[Date], -1, MONTH)),
        CALCULATE(SUM(Fitness[Steps]), DATEADD(Fitness[Date], -1, MONTH))
    )


(You can add more based on your file.)

🎨 Dashboard Design Choices

Clean, modern UI with consistent color theme

Card visuals for KPIs

Line charts for trends

Bar charts for comparison

Slicers for better interactivity

Icons to improve visual storytelling

🚀 Key Insights Generated

Identified days with highest activity levels

Observed weekly pattern changes (peaks and drop-offs)

Understood which workout types contribute most to calorie burn

Tracked monthly progress and improvement areas

📌 Conclusion

This project demonstrates my ability to work with real-world data, clean and model it, apply DAX logic, and design a user-friendly Power BI dashboard that delivers clear and actionable insights.

This project strengthened my skills in:

Business Intelligence

Data Visualization

Power BI

DAX & Data Modeling

Analytical Problem Solving

 Fitness Analytics Dashboard:-https://github.com/skmustaqahmad/Fitness-Analytics-Dashboard/blob/main/Screenshot%202025-11-13%20155652.png
