# netflix-subscription-forecasting

---

# 📈 Netflix Subscriptions Forecasting

This project focuses on analyzing and forecasting Netflix subscription trends using time series analysis. It utilizes a dataset of daily subscription counts and performs decomposition, visualization, and forecasting to understand growth patterns and seasonal effects.

---

## Project Overview
To analyze the historical Netflix subscription data and build a forecasting model that can predict future subscriptions using statistical and machine learning techniques.

---

## 📁 Files in This Repository

* `Netflix_Subscriptions_Forecasting.ipynb` – Main Jupyter Notebook containing the entire workflow:

  * Data loading and preprocessing
  * Time series decomposition (Trend, Seasonality, Residuals)
  * Visualization of subscription trends
  * Forecasting using models such as ARIMA, SARIMA, etc. (based on implementation)
  * Model evaluation and insights

* `Netflix-Subscriptions.csv` – Dataset with the following columns:

  * **Time Period** (e.g., `01-04-2013`)
  * **Subscribers** (number of Netflix subscribers on that day)

---

## 📊 Key Features

* Time Series Decomposition (Trend, Seasonality, Residuals)
* Visual Exploration of Netflix Subscription Patterns
* Forecasting Techniques (e.g., ARIMA/SARIMA)
* Residual Analysis for Model Diagnostics
* Plotting Forecasts with Confidence Intervals

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* Matplotlib / Seaborn
* Statsmodels
* Scikit-learn (if applicable)

---

## 🚀 How to Run the Project

1. Clone this repository or download the `.ipynb` file.
2. Make sure you have Python 3.x and Jupyter Notebook installed.
3. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn statsmodels scikit-learn
   ```
4. Open the notebook:

   ```bash
   jupyter notebook Netflix_Subscriptions_Forecasting.ipynb
   ```
5. Run all cells step by step to explore and forecast Netflix subscriptions.

---

## 📌 Insights & Conclusions

* The decomposition plots reveal clear seasonal patterns and an upward/downward trend in subscriber counts.
* Forecasts help predict future growth and allow for strategic planning.
* Residual analysis helps verify model assumptions and stability.

---


