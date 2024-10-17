# Sales Forecasting Using Time Series Analysis

## Project Overview

This project focuses on developing and evaluating time series forecasting models to predict monthly sales for a single product in one store. The dataset consists of 5 years of historical sales data, aiming to identify the most accurate models to inform future sales strategies.

## Dataset:
**Data source:**
https://www.kaggle.com/competitions/demand-forecasting-kernels-only/data
**Data fields:**
date - Date of the sale data. There are no holiday effects or store closures.
store - Store ID
item - Item ID
sales - Number of items sold at a particular store on a particular date.

## Objectives

- To analyze historical sales data and uncover patterns such as seasonality and trends for a specific product.
- To explore and evaluate different time series models to determine the best fit for the sales data of the selected product.

## Methodology

1. **Data Preprocessing**: 
   - Normalize the data to enhance model performance.
   - Conduct exploratory data analysis (EDA) to identify patterns and trends specific to the product.

2. **Modeling**:
   - Train and evaluate multiple models using techniques such as:
     - ARIMA
     - Exponential Smoothing
     - XGBoost
     - RNN Models
     - Prophet
     - Naive Seasonal and Naive Drift

3. **Evaluation**:
   - Assess model performance using metrics such as Mean Absolute Percentage Error (MAPE) and visualizations to ensure alignment with historical trends.
   - Select the best-performing model based on evaluation results.


4. **Model Performance**:


![{6391F2BD-F3AB-4743-A126-F0C4339ECD4C}](https://github.com/user-attachments/assets/75e622e1-8ce8-4fb7-ae60-9a351f4a685e)

