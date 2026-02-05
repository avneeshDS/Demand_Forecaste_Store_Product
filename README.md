# Demand_Forecaste_Store_Product
*Demand Forecasting Project*
**Overview**
***This project aims to forecast product demand for different stores using historical sales data. Time series models including ARIMA, and SARIMA are applied, and model performance is evaluated using RMSE and MAPE metrics.***
**Steps**
**Database Setup**
***The first step involved importing the PostgreSQL database and establishing a connection to the server using Python. PgAdmin was used to import the data and create the database tables, which were then used to execute SQL queries to fetch the sales data.***
**Data Import and Exploration**
***The pandas library was used to import tables from the database into DataFrames and perform an initial exploration of the dataset.Basic statistics and visualizations were generated to understand sales trends and seasonal patterns.***
**Feature Definition and Analysis**
***Features were identified and analyzed to prepare the data for time series modeling: Numeric columns (e.g., sunits_sold) were separated from categorical columns (e.g., category, region).Important libraries for demand forecasting were imported, including statsmodels, and scikit-learn.Time series pairs were created for each product-store combination to prepare for model fitting.***
**Model Building**
***Each product-store pair was processed in a loop to fit time series models. AutoARIMA: Automatically selects the best ARIMA and SARIMA parameters. The models were trained on historical sales data, and forecasts were generated for future periods.***
**Model Evaluation**
***The performance of the model was assessed using RMSE (Root Mean Squared Error) and MAPE (Mean Absolute Percentage Error).***
