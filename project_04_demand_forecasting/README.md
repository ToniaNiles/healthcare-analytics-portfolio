# Project 4: Appointment Demand Forecasting

## Overview

This project explores historical appointment-demand patterns within NHS primary care services across Hertfordshire and West Essex and introduces predictive analytics through appointment-demand forecasting.

Building upon the previous projects in this Healthcare Analytics Portfolio, the analysis moves beyond descriptive reporting to estimate future appointment volumes and identify periods of anticipated service pressure. The project demonstrates how historical healthcare activity data can be transformed into actionable forecasts to support workforce planning and operational decision-making.

---

## Objective

The objective of this project is to forecast future appointment demand using historical appointment activity data.

The analysis aims to:

- Understand month-to-month demand variation
- Identify recurring seasonal demand patterns
- Assess year-on-year changes in appointment activity
- Forecast appointment demand for the next 12 months
- Identify periods of anticipated service pressure
- Explore workforce and capacity planning implications

---

## Dataset

**Source:**

NHS England – Appointments in General Practice

**Region:**

Hertfordshire and West Essex

**Key variables used in this project:**

- APPOINTMENT_MONTH
- COUNT_OF_APPOINTMENTS

Appointment volumes were aggregated to the monthly level to create a time series suitable for demand forecasting.

---

## Business Questions

This project addresses the following questions:

### 1. How much month-to-month variation exists in appointment demand?

Examined fluctuations in appointment activity over time and identified periods of increased or decreased demand.

### 2. How has appointment demand changed year-on-year?

Compared monthly appointment volumes between 2024 and 2025 to assess longer-term demand trends.

### 3. What is the forecasted appointment demand for the next 12 months?

Developed a forecasting model using historical appointment activity to estimate future demand.

### 4. Which periods are forecast to experience the greatest service pressure?

Ranked forecasted demand to identify anticipated peak and low-demand periods.

### 5. What workforce and capacity planning implications arise from the forecast?

Translated analytical findings into practical operational recommendations.

---

## Methods Used

### Data Preparation

- Data cleaning
- Monthly aggregation
- Datetime conversion
- Time-series preparation

### Exploratory Analysis

- Trend analysis
- Month-on-month percentage change analysis
- Seasonal demand analysis
- Year-on-year comparison

### Forecasting

- Holt-Winters Exponential Smoothing
- Trend modelling
- Seasonal modelling
- 12-month demand forecasting

### Visualisation

- Line charts
- Bar charts
- Forecast visualisation

---

## Key Findings

- Appointment demand remained relatively stable overall, although notable month-to-month fluctuations were observed.

- Seasonal demand patterns were evident, with October consistently recording the highest levels of appointment activity and August generally experiencing the lowest demand.

- Year-on-year demand remained broadly stable between 2024 and 2025, with most monthly changes remaining within a relatively narrow range.

- The forecasting model predicts that appointment demand will remain stable over the next 12 months, with expected monthly activity ranging from approximately 650,000 to 927,000 appointments.

- These forecasts should be interpreted as model-based estimates rather than precise predictions, as future demand may be influenced by factors not captured within the historical data.

- October 2026 is forecast to experience the highest demand, while August 2026 is forecast to experience the lowest demand.

- Recurring autumn and winter peaks suggest that workforce and capacity planning efforts should focus on these periods of increased service pressure.

- October repeatedly emerged as a high-demand month across historical, seasonal, and forecast analyses. While the dataset does not explain the underlying drivers of this pattern, the consistency of this finding suggests that October demand warrants further investigation in future analyses.

---

## Skills Demonstrated

### Healthcare Analytics

- Demand analysis
- Seasonal trend analysis
- Capacity planning
- Workforce planning interpretation
- Operational performance analysis

### Data Analysis

- Data cleaning
- Aggregation
- KPI development
- Trend analysis
- Time-series analysis

### Python

- pandas
- matplotlib
- datetime handling
- groupby()
- pivot()
- percentage calculations
- time-series analysis

### Predictive Analytics

- Forecast modelling
- Exponential smoothing
- Forecast interpretation
- Scenario-based planning

---

## Technologies Used

- Python
- pandas
- matplotlib
- statsmodels
- Jupyter Notebook
- Git
- GitHub

---

## Portfolio Progression

This project represents the transition from descriptive analytics to predictive analytics within the Healthcare Analytics Portfolio.

Previous projects focused on understanding:

- Operational performance
- Patient non-attendance (DNA)
- Workforce utilisation

This project extends those insights by forecasting future demand and exploring how analytical findings can support operational decision-making and service planning.

---

## Repository Structure

```text
project_04_demand_forecasting/
│
├── 04_demand_forecasting.ipynb
└── README.md
```