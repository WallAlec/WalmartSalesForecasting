# Walmart Sales Forecasting

Hello! In this project I focus on analyzing and forecasting sales data from Walmart stores. 
I use various machine learning algorithms and techniques to understand and predict sales trends 
for each department within the stores. The goal of this project is to help Walmart improve its 
inventory management and optimize store operations.

## Data

The dataset used in this project consists of historical sales data for 45 Walmart stores located in different regions. Each store contains a number of departments, and we are tasked with predicting the department-wide sales for each store.

Below is a quick description of our data:

- Store: The store number
- Dept: The department number
- Date: The week of sales data
- Weekly_Sales: Sales for the given department in the given store
- IsHoliday: Whether the week is a special holiday week
- Temperature: Average temperature in the region
- Fuel_Price: Cost of fuel in the region
- MarkDown1-5: Anonymized data related to promotional markdowns
- CPI: The consumer price index
- Unemployment: The unemployment rate
- Type: Type of the store
- Size: Size of the store

## If you want to try this on your own

To run the code in this project, your going to need the following installed

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels

## Methodology

We have used various machine learning techniques to analyze and forecast sales data, including:

1. Data preprocessing and exploration
2. Feature selection and engineering
3. K-means clustering
4. K-nearest neighbors
5. Anomaly detection
6. Time series forecasting with ARIMA and SARIMA models

## Results

Our analysis has provided valuable insights into the sales trends for Walmart stores, as well as identified potential anomalies that may require further investigation. The time series forecasting models have also produced reasonable predictions for future sales, which can be used to guide inventory management and store operations.

## Future Work

There is still room for improvement in the models and techniques used in this project. Future work could include:

- Investigating the impact of external factors such as weather, holidays, and economic conditions on sales
- Evaluating and comparing other time series forecasting models, such as LSTM, Prophet, and state space models
- Incorporating additional features or data sources to enhance the predictive performance of the models
