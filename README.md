# Subject : QQQ stock price prediction 

Rachel Kim 300394050
Kimiya eymouri Nik 300384851


# Stock Price Prediction Analysis

This project aims to predict stock prices using QQQ stock dataset. The analysis includes data loading, EDA, feature engineering, and applying machine learning models to predict future stock prices.

## Project Overview
The project includes the following steps:
- Data Loading: Obtaining stock data from yahoo finance API.
- Exploratory Data Analysis (EDA): Visualizing trends, patterns, seasonality in the data.
- Feature Engineering (Technical Indicators) : Adding technical indicators (e.g. MA5, RSI...)
- Modeling (1): Building models to predict future stock prices with existing data and added technical indicators.
- Feature Engineering (Economical Indicators) : Adding economical indicators (e.g. insterest, gold price, CPI) for a more detailed analysis.
- Modeling (2): Building enhanced models to predict future stock prices with added economical indicators.
- Model Evaluation: Evaluating the performance of the models using MAE and accuracy score.

## Requirements

To run the code and replicate the analysis, we used the following Python libraries:
- pandas: Data manipulation and analysis.
- numpy: Numerical operations.
- matplotlib: Plotting and data visualization.
- seaborn: Statistical data visualization.
- scikit-learn: Machine learning models and utilities.
- tensorflow: Deep learning framework (for LSTM models).
- keras: Deep learning framework (for LSTM models).
- datetime: Working with date and time.
- yfinance: Yahoo Finance API (if using stock data).


## Files in the Repository

- `QQQ_stock_marcket_Rachel,_Kimiya (submission).ipynb`: Jupyter Notebook containing the complete analysis.
- 'QQQ Final - Rachel, Kimiya.pptx': Presentation file 
- `datasets`: Folder containing our datasets
  QQQ (200101-241231) : Original Dataset
  QQQ_tech(200101-241231) : Original + tech indicators dataset
  QQQ_tech, macro(200101-241231) : Original + tech + economical dataset
- Read me : Descriptions of our process and summary


## Results
Model 
