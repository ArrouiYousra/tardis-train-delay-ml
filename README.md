# 🚆 TARDIS — Train Delay Prediction

> Predicting train delays using data analysis, machine learning, and an interactive dashboard.

---

## 📌 Project Overview

TARDIS is a data science project focused on analyzing historical train delay data and building a predictive model to estimate future delays.

The project includes:

* Data cleaning and preprocessing
* Exploratory data analysis (EDA)
* Machine learning model for delay prediction
* Interactive dashboard using Streamlit

---

## 🎯 Objectives

* Understand delay patterns in railway data
* Identify key factors influencing delays
* Build a regression model to predict delay duration (in minutes)
* Provide an interactive interface for users to explore insights

---

## 📁 Project Structure

```
.
├── tardis_eda.ipynb        # Data cleaning, exploration, feature engineering
├── cleaned_dataset.csv     # Cleaned dataset
├── tardis_model.ipynb      # Model training and evaluation
├── model.joblib            # Trained model
├── tardis_dashboard.py     # Streamlit dashboard
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/tardis-train-delay-ml.git
cd tardis-train-delay-ml
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### 1. Run the dashboard

```bash
streamlit run tardis_dashboard.py
```

### 2. Open in browser

```
http://localhost:8501
```

---

## 📊 Features

### 🔍 Data Analysis

* Missing values handling
* Duplicate removal
* Feature engineering (e.g. month, day of week)

### 📈 Visualization

* Delay distribution
* Delay comparison (stations, time periods)
* Correlation insights

### 🤖 Machine Learning

* Regression model to predict delays
* Feature encoding
* Model evaluation (MAE, RMSE, R²)

### 📺 Dashboard

* Interactive charts
* Summary statistics
* Delay prediction interface
* User inputs (station, time, etc.)

---

## 🧠 Technologies Used

* Python
* pandas / numpy
* matplotlib / seaborn
* scikit-learn
* streamlit

---

## 📌 Example Prediction

The model predicts the expected delay (in minutes) based on:

* Departure station
* Arrival station
* Time of departure
* Day of the week
* Train type

---

## 📈 Possible Improvements

* Hyperparameter tuning
* Multiple model comparison
* Feature importance visualization
* Geospatial visualization of delays
* Explainable AI (SHAP / LIME)

---

## 👥 Authors

* Yousra Arroui
* Mathieu Vergez

---

## 📝 License

This project is part of an academic assignment at EPITECH.
