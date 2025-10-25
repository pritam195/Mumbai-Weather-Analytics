# Mumbai-Weather-Analytics

This project presents an exploratory data analysis (EDA) of historical weather data from Mumbai, India, spanning over three decades (1990–2022). The goal is to understand long-term patterns in temperature and rainfall, highlight seasonal behavior, and identify anomalies in the city's climate.

## 📌 Project Objective

- Analyze historical weather data of Mumbai.
- Detect trends and outliers in temperature and rainfall.
- Understand seasonal climate behavior using visualizations.

---

## 🌦️ Dataset Description

The dataset contains daily weather observations recorded from 1990 to 2022, representing key climatic parameters for a specific location or region. Each record corresponds to one day and includes the following variables:

Column	Description
time	Date of observation (DD-MM-YYYY format), covering the period from January 1, 1990, to December 31, 2022.
tavg	Average daily temperature (°C), computed as the mean of the daily minimum and maximum temperatures.
tmin	Minimum temperature (°C) recorded on that day.
tmax	Maximum temperature (°C) recorded on that day.
prcp	Daily total precipitation (mm), indicating the amount of rainfall or snowfall.

📊 Data Summary

Time span: 33 years (1990–2022)
Temporal resolution: Daily
Data type: Numerical and time-series

Use cases: Climate trend analysis, temperature forecasting, precipitation pattern detection, and time-series modeling.

# Dataset link
https://drive.google.com/file/d/1D6jLPEsrPIwIsHlRx1kQWoLsStDaONmK/view?usp=sharing

---

## 📊 Key Features of the Analysis

- **Data Cleaning:** Missing values handled, datetime formatting, indexing.
- **Visual Explorations:** Line plots, correlation plots, bar charts for weather metrics.
- **Insights:** 
  - Monsoon peaks in July with highest rainfall.
  - Winters (Dec–Feb) are coolest, summers are long and intense.
  - Abnormal rainfall spikes detected in 2014, 2019, and 2021.

---

## 🧪 Libraries Used

- `pandas` – data wrangling  
- `numpy` – numerical computations  
- `matplotlib` & `seaborn` – data visualization  
- `missingno` – visualizing missing values  
- `datetime` – time parsing and formatting

---


## ✅ Insights

* **Mumbai's monsoon** is concentrated between June and September, with **July** being the wettest.
* **Heat waves** observed in pre-monsoon months like March–May.
* **Climate anomalies** in 2019 and 2021 signal abnormal rainfall outside monsoon season.

---

## ⚠️ Notes

* Do not rerun the cell where `time` column is dropped unless you've reloaded the dataset.
* The dataset used here represents a **single weather station** (Santacruz), so results may not generalize across all of Mumbai.

---