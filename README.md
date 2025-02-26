# Yes Bank Stock Closing Price Prediction

## Project Overview
This project aims to predict the closing stock price of Yes Bank using regression models. The dataset contains monthly stock prices, including opening, highest, lowest, and closing prices since the bank's inception. The study explores various machine learning techniques to build an accurate predictive model.

## Project Type
- **Regression**
- **Individual Contribution**

## Problem Statement
Yes Bank, a well-known financial institution in India, has faced significant fluctuations in stock prices due to various factors, including a fraud case involving Rana Kapoor in 2018. The project analyzes historical stock data to understand these fluctuations and predict future closing prices.

## Features Used
- **Open Price**: The price at which the stock opened for the day.
- **High Price**: The highest price reached during the trading session.
- **Low Price**: The lowest price recorded in the session.
- **Close Price**: The price at which the stock closed for the day.

## Data Analysis & Preprocessing
- **Handling Missing Values**: Imputation techniques were used to fill missing data.
- **Feature Engineering**: Derived new features such as the mean of Open, High, and Low prices to improve prediction accuracy.
- **Data Visualization**: Performed univariate, bivariate, and multivariate analysis to explore patterns in the dataset.

## Machine Learning Models Used
1. **Linear Regression**
2. **Random Forest Regressor**
3. **XGBoost Regressor**

### Model Evaluation Metrics:
- **Root Mean Squared Error (RMSE)**
- **R-Squared Score (R²)**
- **Adjusted R² Score**

### Best Performing Model:
The **XGBoost Regressor** showed the highest R² score and adjusted R², making it the most suitable model for predicting the closing price.

## Results & Insights
- Stock prices showed volatility after 2018 due to financial scandals.
- The mean of Open, High, and Low prices improved prediction accuracy.
- **XGBoost** performed best in capturing stock price trends.

## Conclusion
This project successfully demonstrated the ability to predict Yes Bank's closing stock price using machine learning models. The key takeaways from this study are:

- **Financial events significantly impact stock price movements.**
- The **XGBoost Regressor** provided the most accurate predictions among all models tested.
- **Feature engineering**, such as taking the mean of Open, High, and Low prices, improved model performance.
- Historical stock data alone may not be sufficient for accurate predictions; incorporating **external factors** like economic indicators and news sentiment can enhance prediction accuracy.

Future work can focus on:
- **Integrating external data sources** like macroeconomic indicators and market sentiment analysis.
- **Exploring deep learning models** such as LSTMs for time-series forecasting.
- **Deploying a real-time prediction system** via a web application or API.

## Future Enhancements
- Collect more granular (daily) stock price data for improved accuracy.
- Experiment with deep learning models like LSTMs for time-series forecasting.
- Deploy a web-based dashboard for real-time stock predictions.

