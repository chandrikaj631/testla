# ⚡ Tesla Stock Price Prediction & Analysis

A machine learning and data analytics project that analyzes historical Tesla stock data, identifies trends, visualizes market behavior, and predicts future stock prices using predictive modeling techniques.

![Dashboard](.dashboard.png)

---

## 📌 Project Overview

This project focuses on analyzing Tesla stock market data to uncover patterns, trends, and insights that can help investors make informed decisions. The application combines exploratory data analysis, data visualization, and machine learning techniques to forecast stock prices.

The project demonstrates a complete data science workflow from data collection and preprocessing to model building and deployment.

---

## 🎯 Problem Statement

Stock prices are highly dynamic and influenced by multiple market factors. Predicting future stock prices accurately can help investors reduce risk and make better investment decisions.

**Goal:** Build a machine learning model capable of predicting Tesla stock prices using historical market data and visualize key stock market trends through an interactive dashboard.

---

## 🚀 Approach

The project follows a complete end-to-end data science lifecycle:

**Data Collection → Data Cleaning → EDA → Feature Engineering → Model Training → Model Evaluation → Prediction → Dashboard Visualization**

---

## 📊 Step 1 — Data Collection

* Collected Tesla stock market data.
* Historical records include:

  * Date
  * Open Price
  * High Price
  * Low Price
  * Close Price
  * Volume

---

## 🔍 Step 2 — Exploratory Data Analysis (EDA)

Performed comprehensive analysis to understand stock behavior:

### Univariate Analysis

* Distribution of stock prices
* Trading volume analysis

### Time-Series Analysis

* Daily stock movement trends
* Monthly and yearly growth patterns

### Correlation Analysis

* Relationship between Open, High, Low, Close, and Volume

### Business Insights

* Highest stock price periods
* Market volatility trends
* Growth performance over time

---

## ⚙️ Step 3 — Data Preprocessing

* Handled missing values
* Converted date columns into datetime format
* Created time-based features
* Scaled numerical variables where required

---

## 🤖 Step 4 — Model Training

Multiple machine learning models were tested and compared:

| Model                   | Performance      |
| ----------------------- | ---------------- |
| Linear Regression       | Baseline Model   |
| Decision Tree Regressor | Moderate         |
| Random Forest Regressor | Good             |
| XGBoost Regressor       | Best Performance |

---

## 📈 Step 5 — Model Evaluation

Evaluation Metrics:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

The best-performing model was selected based on prediction accuracy and generalization capability.

---

## 🖥️ Dashboard Features

### 📊 Interactive Visualizations

* Tesla stock trend analysis
* Daily closing price visualization
* Volume traded analysis
* Moving average charts
* Correlation heatmaps

### 🔮 Price Prediction

Users can:

* Input stock-related values
* Generate future price predictions
* View prediction outputs instantly

---

## 🛠️ Tech Stack

| Technology           | Purpose                |
| -------------------- | ---------------------- |
| Python               | Core Programming       |
| Pandas               | Data Processing        |
| NumPy                | Numerical Operations   |
| Matplotlib           | Data Visualization     |
| Seaborn              | Statistical Charts     |
| Plotly               | Interactive Dashboards |
| Scikit-learn         | Machine Learning       |
| Streamlit / Power BI | Dashboard Development  |

---

## 📂 Project Structure

tesla-stock-prediction/

├── tesla_stock_prediction.ipynb

├── app.py

├── dataset/

│ └── tesla_stock.csv

├── images/

│ ├── dashboard.png

│ └── prediction.png

├── requirements.txt

└── README.md

---

## ▶️ Run Locally

### Clone Repository

```bash
git clone https://github.com/chandrikaj631/tesla-stock-prediction.git
cd tesla-stock-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## 📌 Future Improvements

* Real-time stock market integration
* Advanced forecasting models (LSTM)
* News sentiment analysis
* Portfolio recommendation system
* Live dashboard deployment

---

