# Task 1: Delhi Air Quality Analysis (AQI Data Visualization)
**ShadowFox Data Science Internship**

## Project Overview

This project performs **exploratory data analysis (EDA)** on air pollution data from Delhi. The goal is to analyze pollutant concentrations, identify patterns across time, and understand relationships between different pollutants using **Python data analysis and visualization libraries**.

The dataset contains hourly measurements of several pollutants such as CO, NO, NO₂, O₃, SO₂, PM2.5, PM10, and NH₃.

---

## Objectives

* Analyze the **distribution of major pollutants**
* Study **correlations between pollutants**
* Identify **hourly pollution patterns**
* Identify **daily pollution trends**
* Compare **average pollutant concentrations**
* Calculate **total pollution per day**

---

## Technologies Used

* Python
* Pandas – data manipulation and analysis
* Matplotlib – data visualization
* Seaborn – statistical visualization

---

## Dataset Features

| Column | Description                    |
| ------ | ------------------------------ |
| date   | Date and time of measurement   |
| co     | Carbon Monoxide concentration  |
| no     | Nitric Oxide concentration     |
| no2    | Nitrogen Dioxide concentration |
| o3     | Ozone concentration            |
| so2    | Sulfur Dioxide concentration   |
| pm2_5  | Particulate Matter (PM2.5)     |
| pm10   | Particulate Matter (PM10)      |
| nh3    | Ammonia concentration          |

Additional features were created during analysis:

* **hour** – extracted hour from datetime
* **day** – extracted day from datetime
* **total_pollution** – combined pollution index

---

## Analysis Performed

### 1. Data Exploration

Basic inspection of the dataset using:

* `head()`
* `info()`
* `describe()`

This helps understand data structure, data types, and statistical properties.

---

### 2. Distribution of Pollutants

Histograms are used to visualize the distribution of pollutant concentrations and identify patterns or skewness in the data.

---

### 3. Correlation Analysis

A heatmap is used to analyze relationships between pollutants. Strong correlations may indicate pollutants originating from similar sources.

---

### 4. Hourly Pollution Trends

Pollutant levels are grouped by hour to understand how air quality changes throughout the day.

---

### 5. Daily Pollution Trends

Pollution levels are grouped by day to identify daily variations in air quality.

---

### 6. Average Pollutant Comparison

Bar charts compare the average concentration of key pollutants.

---

### 7. Total Pollution Index

A new variable **total_pollution** is created by summing all pollutant values for each observation. This helps identify which day had the highest overall pollution level.

---

## Key Insights

* Particulate pollutants such as **PM2.5 and PM10 show strong correlation**.
* Pollution levels vary significantly across different hours of the day.
* Certain days show higher overall pollution levels when combining multiple pollutants.
* Some pollutants appear to increase together, suggesting possible common sources.

---

## How to Run the Project

1. Clone the repository
2. Install required libraries

```
pip install pandas matplotlib seaborn
```

3. Run the notebook or Python script.

---

## Project Structure

```
Delhi-AQI-Analysis/
│
├── delhiaqi.csv
├── analysis.ipynb
└── README.md
```

---

## Future Improvements

* Calculate **Air Quality Index (AQI) categories**
* Perform **time-series forecasting**
* Build **machine learning models for pollution prediction**
* Create **interactive dashboards using Tableau or Power BI**

---

## Author

Darshan Patil
