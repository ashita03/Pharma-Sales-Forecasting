# Pharmaceutical Drug Sales Forecasting
The goal of this project is to build and evaluate time series models to forecast pharmaceutical sales. The project includes data preprocessing, exploratory data analysis, model building, and evaluation of forecast accuracy.

Data Source: [Kaggle](https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data)

## Modeling Approach

### Data Preprocessing
* Parsing dates and setting the date column as the index.
* Handling missing values and outliers.
* Aggregating sales data.
  
### Exploratory Data Analysis (EDA)
* Visualizing the sales trend over time.
* Checking for seasonality, trends, and cyclic behavior.
* Analyzing the distribution of sales.
  
### Model Building
We employ the following time series models:
* ARIMA (AutoRegressive Integrated Moving Average)
  * ARIMA(1, 0, 1)
* AutoRegressive (AutoReg)
  * AutoReg(1)
    
### Evaluation
The models are evaluated using:
* AIC and BIC
  
## Results
The AutoReg model provided a better fit with a lower AIC and BIC compared to the ARIMA model.
The RMSE of the AutoReg model was 747.28, indicating the average prediction error in units of sales.
