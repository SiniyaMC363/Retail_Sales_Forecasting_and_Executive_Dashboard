# 🛒 Retail Sales Forecasting and Business Intelligence Dashboard

## 📌 Project Overview

This project focuses on forecasting future retail sales using **Machine Learning** and visualizing business insights using **Power BI**. Historical sales data was cleaned, transformed, and analyzed to build a forecasting model using **Linear Regression**. The predicted sales results and historical performance were further presented through interactive dashboards.

The project demonstrates an end-to-end data science workflow, including data preprocessing, feature engineering, model training, evaluation, forecasting, and business intelligence reporting.

---

## 🎯 Objectives

* Analyze historical retail sales trends.
* Forecast future sales using machine learning techniques.
* Compare actual sales with predicted sales.
* Evaluate model performance using forecasting metrics.
* Create interactive Power BI dashboards for business insights.

---

## 📂 Dataset Information

The dataset contains monthly retail sales records with the following fields:

| Column | Description                |
| ------ | -------------------------- |
| Date   | Sales month and year       |
| Sales  | Total monthly sales amount |

The dataset was prepared through data cleaning and monthly aggregation before applying machine learning models.

---

## 🛠️ Technologies Used

### Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib

### Machine Learning

* Linear Regression
* Feature Engineering using Lag Variables
* Min-Max Scaling

### Model Evaluation

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* R² Score

### Business Intelligence

* Power BI
* DAX Measures
* Interactive Visualizations

---

## 🔄 Project Workflow

### 1. Data Preprocessing

* Loaded retail sales dataset.
* Converted date columns into proper datetime format.
* Handled missing values.
* Created monthly aggregated sales data.

### 2. Feature Engineering

* Converted the time-series problem into a supervised learning problem.
* Created 12-month lag features.
* Prepared training and testing datasets.

### 3. Data Scaling

* Applied Min-Max scaling to normalize the data before model training.

### 4. Model Development

* Trained a Linear Regression model.
* Generated future sales predictions.
* Converted predictions back to the original sales scale.

### 5. Model Evaluation

The model was evaluated using:

* RMSE
* MAE
* R² Score

### 6. Power BI Dashboard Development

Two interactive dashboards were created:

#### 📈 Sales Forecast Analysis

Features:

* Actual vs Predicted Sales Trend
* Total Actual Sales KPI
* Total Predicted Sales KPI
* Average Sales Analysis
* Forecast Accuracy Percentage
* Prediction Error Analysis
* Interactive Date Filters

#### 📊 Historical Sales Analysis

Features:

* Total Sales Performance
* Monthly Sales Trend
* Highest and Lowest Sales Months
* Average Monthly Sales
* Time-based Sales Filtering

---

## 📁 Project Structure

```
Retail-Sales-Forecasting/
│
├── data/
│   ├── monthly_sales.csv
│   ├── monthly_sales_dashboard.csv
│   └── sales_forecast_results.csv
│
├── notebooks/
│   └── sales_forecast.ipynb
│
├── dashboard/
│   └── Retail_Sales_Forecasting.pbix
│
├── README.md
│
└── requirements.txt
```

---

## 📊 Dashboard Preview

### Sales Forecast Analysis Dashboard

* Actual Sales vs Predicted Sales comparison.
* Forecast accuracy and error analysis.
* Interactive filtering using Power BI slicers.

### Historical Sales Dashboard

* Sales trend analysis.
* Monthly performance comparison.
* Business performance KPIs.

---

## 🚀 Future Improvements

* Implement advanced forecasting models such as:

  * ARIMA
  * Random Forest Regressor
  * XGBoost
  * LSTM Neural Networks

* Deploy an interactive web application for real-time forecasting.

* Integrate automated data pipelines for continuous model updates.

---

## 📈 Key Learning Outcomes

Through this project, I gained practical experience in:

* Data cleaning and preprocessing.
* Time-series feature engineering.
* Building machine learning forecasting models.
* Evaluating regression model performance.
* Designing professional Power BI dashboards.
* Transforming machine learning results into business insights.

---

## 👩‍💻 Author

**Siniya MC**
AI & Data Science Graduate | Machine Learning | Data Analytics | Power BI
