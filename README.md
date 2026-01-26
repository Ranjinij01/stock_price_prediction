# Stock Price Trend Prediction using Machine Learning

## Project Overview
This project focuses on predicting stock price trends using historical market data and machine learning techniques. The objective is not to predict the exact stock price, but to analyze historical patterns and identify future price trends that can support data-driven decision-making.

Real-world financial data is sourced from Yahoo Finance, and the project follows an end-to-end data analytics and machine learning workflow including data collection, preprocessing, feature engineering, model building, evaluation, and visualization.

---

## Objectives
- Analyze historical stock price data
- Perform feature engineering to capture market trends
- Build machine learning models to predict next-day stock prices
- Evaluate and compare model performance
- Visualize actual versus predicted stock price trends

---

## Dataset
Source: Yahoo Finance  
Stock: Amazon (AMZN)  
Time Period: 2014 to 2024  
Frequency: Daily  

Dataset Features:
- Date
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

---

## Tools and Technologies
Programming Language:
- Python

Libraries Used:
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance

---

## Project Workflow

### 1. Data Collection
Historical stock price data was extracted using the Yahoo Finance API for Amazon (AMZN). The data was loaded into a Pandas DataFrame for further analysis.

### 2. Exploratory Data Analysis (EDA)
- Analyzed long-term stock price trends
- Checked for missing and inconsistent data
- Visualized closing price movement over time

### 3. Feature Engineering
To improve model performance, the following features were created:
- 20-day Moving Average (MA20)
- 50-day Moving Average (MA50)
- Daily Returns

Rows with missing values generated during rolling calculations were removed.

### 4. Data Preprocessing
- Selected relevant features for modeling
- Scaled features using Min-Max scaling
- Converted the problem into a supervised learning task by predicting the next day’s closing price

### 5. Model Building
Two machine learning models were implemented:
- Linear Regression as a baseline model
- Random Forest Regressor to capture non-linear patterns in stock price movement

### 6. Model Evaluation
Models were evaluated using the following metrics:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared (R2) Score

### 7. Visualization
- Plotted actual versus predicted stock prices
- Analyzed how well the model captured overall price trends

---

## Results and Insights
- Random Forest performed better than Linear Regression in capturing stock price trends
- The model performed well during stable market conditions
- High volatility periods were harder to predict due to external market factors

---

## Limitations
- External factors such as news, economic events, and market sentiment were not included
- The model is suitable for trend analysis, not real-time trading or investment decisions

---

## Future Enhancements
- Include macroeconomic indicators and sentiment analysis
- Experiment with deep learning models such as LSTM
- Extend predictions to weekly or monthly trends
- Deploy the model as a simple web application

---

## Conclusion
This project demonstrates an end-to-end machine learning workflow for financial time-series analysis, showcasing skills in data analysis, feature engineering, machine learning, model evaluation, and data visualization.


This project demonstrates an end-to-end machine learning workflow for financial time-series analysis, highlighting skills in data analysis, feature engineering, modeling, evaluation, and storytelling with data.
