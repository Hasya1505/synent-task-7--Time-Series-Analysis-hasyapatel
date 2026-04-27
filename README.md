#  Stock Price Time Series Analysis

This project focuses on analyzing stock price data using time series techniques.  
The dataset contains historical stock prices of multiple companies.

The main goal is to understand trends, compare companies, analyze risk, and predict future prices.

---

##  Dataset

The dataset includes:

- Date → Trading date  
- Symbol → Company name  
- Close → Closing stock price  
- Volume → Trading volume  

The data ranges from **2000 to 2021** and contains multiple companies.

---

##  Objectives

- Analyze stock price trends over time  
- Compare performance of different companies  
- Detect seasonal patterns  
- Measure volatility (risk)  
- Predict future stock prices  

---

##  Steps Performed

### 1. Understanding the Dataset  
Checked total records, number of companies, and date range.

---

### 2. Selecting Important Columns  
Kept only required columns:
- Date  
- Symbol  
- Close  
- Volume  

---

### 3. Preparing Date for Analysis  
Converted date into datetime format, sorted data, and set it as index.

---

### 4. Handling Missing Data  
Handled missing values using forward fill to maintain continuity.

---

### 5. Finding Top Companies  
Calculated average closing price for each company to rank them.

---

### 6. Selecting High and Medium Companies  
Selected:
- Top companies → High value  
- Next group → Medium value  

---

### 7. Comparing Multiple Companies  
Plotted multiple companies in one graph to compare performance.

---

### 8. Analyzing Each Company Individually  
Plotted individual company graphs for better understanding.

---

### 9. Identifying Trends Using Moving Average  
Used:
- 7-day moving average (short-term)  
- 30-day moving average (long-term)  

---

### 10. Analyzing Risk Using Volatility  
Calculated standard deviation to measure stock risk.  
Used bar chart and box plot for comparison.

---

### 11. Studying Long-Term Trends  
Converted daily data into:
- Monthly average  
- Yearly average  

---

### 12. Detecting Seasonality Patterns  
Used time series decomposition to extract:
- Trend  
- Seasonal component  
- Residual noise  

---

### 13. Comparing High vs Medium Companies  
Compared overall performance of both groups.

---

### 14. Preparing Data for Prediction & Predicting Future Prices 
Converted time into numeric index for modeling. 
Used regression models to forecast future stock prices.

---

### 15. Improving Prediction Model  
Used polynomial regression to capture non-linear trends.

---

### 16. Generating Final Insights  

- Stock prices show overall increasing trend  
- Some companies are more volatile (high risk)  
- High-value companies generally perform better  
- Seasonal patterns are weak but present  
- Forecast shows expected future trend (with limitations)  

---
##  Conclusion

This project demonstrates how time series analysis can be used to understand stock market behavior.  
It helps in identifying trends, comparing companies, analyzing risk, and making basic predictions.

---

**Author:** Hasya Patel  

## Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Statsmodels  
