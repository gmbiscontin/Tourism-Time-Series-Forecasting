# Tourism-Time-Series-Forecasting

## Project Description

This project focused on analyzing and forecasting tourism time demand a dataset of 518 annual time series. Each series represents different aspects of tourism activities, such as inbound tourism numbers, visitor nights, and tourism expenditure across various countries. The series vary in length (from 7 to 43 years) and magnitude, making the forecasting task complex in terms of accuracy and model generalization.


![000012](https://github.com/user-attachments/assets/8892d3f3-ee06-4853-9fa8-fc7a843b64e6)


The main objective of the project was to develop and apply various **time series forecasting techniques** to predict future values, while addressing practical challenges related to handling a large number of heterogeneous series.

## Key Activities & Skills Applied

### 1. **Data Preprocessing and Exploration**
   - **Exploratory Data Analysis (EDA)**: Conducted EDA to understand the characteristics of the time series, such as trends, seasonality, and irregular fluctuations.
   - **Data Cleaning**: Handled missing values, detected and managed outliers, and normalized the data to ensure consistency and prepare the dataset for forecasting models.
   - **Data Visualization**: Created visualization tools to effectively explore and compare multiple time series, enabling quick identification of trends, seasonality, and other key features.
   - **Data Partitioning**: Given that the time series have varying lengths and some contain limited observations, each time series has been split into training and validation sets, with the last 4 years designated as the validation period.

### 2. **Time Series Forecasting**
   - **Forecasting Models**: Applied various time series forecasting models, such as **Naive Forecast**, **ARIMA** (AutoRegressive Integrated Moving Average), **Exponential Smoothing**

### 3. **Model Evaluation and Accuracy Metrics**
   - **Evaluation Metrics**: Assessed model performance using various **forecasting accuracy metrics**,
       - Mean Absolute Error (MAE)
       - Average Error (AE)
       - Mean Absolute Percentage Error (MAPE)
       - Root Mean Squared Error (RMSE)
       - Mean Absolute Scaled Error (MASE)

   - **Summary of Results**: Aggregated forecast accuracy across all series to identify the best-performing models for different types of series
     

### 5. **Code**
   - **Workflows**: Developed the project using **RStudio**, leveraging libraries like **tidyverse**, **forecast**, **fpp3**, **seasonal** and **tsibble** to handle the large dataset and forecast tool.
