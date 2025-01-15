# Beijing Air Pollution Analysis 🌏💨

This project analyzes PM2.5 air pollution levels in Beijing using machine learning and meteorological data. The aim is to develop predictive models and uncover insights to aid in environmental management and public health safety.

---

## 📁 Project Overview

- **Objective:** Predict PM2.5 concentrations using meteorological parameters and explore their relationships.
- **Dataset:** Beijing PM2.5 Data Set (Hourly data from 2010 to 2014).
- **Techniques:** 
  - Data Preprocessing (Outlier Removal, Scaling, PCA)
  - Machine Learning Models (Linear Regression, SVR, ANN)

---

## 🛠️ Features

- **Data Analysis:** Explore the relationship between PM2.5 levels and meteorological factors (temperature, humidity, wind speed, etc.).
- **Predictive Models:**
  - Linear Regression
  - Support Vector Regression (SVR)
  - Artificial Neural Network (ANN) combined with SVR
- **Results:** Achieved an R-squared value of **0.725** for hourly data predictions using ANN with SVR.

---

## 🚀 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YourGitHubUsername/Beijing-Air-Pollution.git
   cd Beijing-Air-Pollution

2.	Install dependencies:
    pip install -r requirements.txt

	3.	Run the project:
        python main.py
---

## 📝 Dataset
-	Source: The dataset includes hourly PM2.5 data recorded by the US Embassy in Beijing and meteorological data from Beijing Capital International Airport (2010–2014).

## 📈 Key Insights
-	Meteorological parameters significantly influence PM2.5 concentrations.
-	ANN with SVR outperformed other models, showcasing its effectiveness for air quality prediction.
-	Data preprocessing and dimensionality reduction were crucial for improving model performance.
