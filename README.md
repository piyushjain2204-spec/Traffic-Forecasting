# Traffic Forecasting using Machine Learning Algorithms

## 📌 Project Overview
This project focuses on **Traffic Flow Forecasting** using Machine Learning algorithms to predict vehicle traffic volume based on time-related features such as hour, day, week, month, and year.

The dataset records hourly traffic flow at the **Bogishamol Street intersection in Tashkent**, focusing on vehicles moving west to east.

This project compares multiple regression models and evaluates their prediction performance.

---

### Features:
- Datetime  
- Vehicles (Target Variable)  
- Day  
- Week  
- Month  
- Year  
- Hour  

---

## 📊 Key Traffic Trends

- Peak traffic during **8:00 AM – 10:00 AM**
- Evening rush during **5:00 PM – 6:00 PM**
- Lower and stable traffic on weekends

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  

---

## 🔍 Data Preprocessing

- Converted Datetime into structured features:
  - Hour
  - Day
  - Week
  - Month
  - Year

- Checked and handled missing values
- Feature selection using time-based variables
- Train-Test Split (80%-20%)
- Correlation Analysis

---

## 📈 Exploratory Data Analysis (EDA)

### Visualizations Performed:

- Vehicles Count by Day  
- Vehicles Count by Month  
- Traffic Flow Distribution  
- Average Vehicles by Hour  
- Vehicles by Day of Week  
- Average Vehicles by Month  
- Correlation Heatmap  

---

## 🤖 Machine Learning Models Used

### 1️⃣ KNN Regressor
- Different values of neighbors tested
- Performance compared using:
  - MAE
  - RMSE
  - R² Score

### 2️⃣ Support Vector Regression (SVR)
- Kernel-based nonlinear regression
- Hyperparameters tuned:
  - C
  - Gamma
  - Epsilon

### 3️⃣ XGBoost Regressor
- 1000 Trees
- High accuracy
- Handles nonlinear patterns efficiently

---

## 📉 Evaluation Metrics

- **MAE** – Mean Absolute Error  
- **MSE** – Mean Squared Error  
- **RMSE** – Root Mean Squared Error  
- **R² Score** – Goodness of Fit  

---

## 📊 Model Comparison

The models were compared visually and numerically based on prediction accuracy.

XGBoost showed the best performance among all tested models.

---

## 📷 Output Graphs

- Actual vs Predicted Graphs
- Model Comparison Graphs
- Heatmaps
- Traffic Trend Charts

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
python main.py
