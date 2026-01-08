# Yes Bank Stock Price Forecasting using Time Series Analysis (ADF & ARIMA)

📊 Domain: Financial Time Series Forecasting  
📈 Techniques: ADF Test, Stationarity, ARIMA  
🧠 Skills: Python, Pandas, Statsmodels, Data Visualization

Analyzing Yes Bank historical stock data, performing stationarity checks, and forecasting future prices using Time Series methods such as ADF test and ARIMA modeling.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Project Structure](#project-structure)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Stationarity Check](#stationarity-check)
- [Time Series Modeling](#time-series-modeling)
- [Forecasting](#forecasting)
- [Key Insights](#key-insights)
- [How to Run This Project](#how-to-run-this-project)
- [Final Conclusion](#final-conclusion)
- [Author & Contact](#author--contact)

---

## Overview
This project analyzes Yes Bank’s historical stock price data to extract meaningful trends and forecast future prices using statistical time series techniques.

---

## Business Problem
Stock market analysts and investors want insights into:
- Trends in stock prices over time
- Whether the stock series is stationary
- How to forecast future stock prices using historical data  

This project addresses these using time series modeling.

---

## Dataset
The dataset consists of historical prices for Yes Bank stock including:
- Date
- Open
- High
- Low
- Close prices

This time-indexed dataset allows statistical analysis and forecasting.

---

## Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Statsmodels (ADF Test & ARIMA)
- Jupyter Notebook
- Git & GitHub

---

## Project Structure
├── data
│ └── yes_bank_stock.csv
├── notebooks
│ └── yes_bank_time_series_analysis.ipynb
├── README.md


---

## Data Cleaning & Preparation
- Converted the date column to datetime format  
- Set the date column as index  
- Checked missing values and duplicates  
- Ensured chronological order of data  

---

## Exploratory Data Analysis (EDA)
- Plotted stock close prices over time  
- Observed trend and seasonal behavior  
- Visualized distribution of price movements  

---

## Stationarity Check
To use ARIMA, the series must be stationary.

### ✔ Augmented Dickey-Fuller (ADF) Test  
Stationarity is tested and differencing is applied to make the series stationary when required.

---

## Time Series Modeling
The ARIMA model (AutoRegressive Integrated Moving Average) is trained on past price data to capture underlying patterns.

---

## Forecasting
Using the trained ARIMA model, future stock prices are forecasted for a defined period.  
Visualizations show actual vs predicted values.

---

## Key Insights
- The time series exhibited non-stationary behavior initially
- Differencing was required to achieve stationarity
- ARIMA produced reasonable short-term forecast predictions

---

## How to Run This Project
1. Clone the repository  
   ```bash
   git clone https://github.com/abh1903/-Yes-Bank-Stock-Price-Forecasting-using-Time-Series-Analysis-ADF-ARIMA-

Install dependencies:

pip install pandas numpy matplotlib seaborn statsmodels


Open the Jupyter Notebook and run all cells

Final Conclusion

This project demonstrates how time series analysis and ARIMA modelling can be used to understand and forecast stock price trends — valuable for financial analysis and decision-making.

Author & Contact

Your Name
📧 Email: your_email@example.com

🔗 LinkedIn: https://linkedin.com/in/yourprofile

💻 GitHub: https://github.com/abh1903


---

✅ **All Anchor Links Work**  
Clicking any link in the Table of Contents (like Overview, Dataset, etc.) will take the user directly to that section.

---

### 📌 Next Step (Optional but powerful)

📸 **Add screenshots of your plots** (forecast plot, ADF test output, EDA charts) below each section (Visuals help recruiters instantly understand your work).

Example:
```md
## Forecasting

![Forecast Plot](images/forecast_plot.png)


If you want, I can also:
✔ Add badges (Python version, notebook status)
✔ Add live preview GIF of your forecast
✔ Make it look even more professional for recruiters

Just tell me 👍
