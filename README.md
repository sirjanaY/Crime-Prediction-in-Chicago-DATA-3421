
# Chicago Crime Prediction — DATA3421 Final Project

This project explores the use of machine learning models to **predict whether a reported crime in Chicago will result in an arrest**. Using over five years of public crime data, we identified arrest trends and built classification models to support data-driven decisions in law enforcement.

## 📌 Project Overview

- **Topic:** Crime prediction based on historical crime reports
- **Goal:** Predict arrest likelihood using classification models
- **Team Members:** Melissa Tobias, Natalie Pegues, Malaika Galvan, Daynise Escudero, Sirjana Yadav
- **Course:** DATA 3421 – Data Science for Criminal Justice

## 📊 Methodology

- **Problem Type:** Binary classification (`Arrest`: True/False)
- **Tools & Libraries:**
  - `Pandas`, `NumPy` – data cleaning & manipulation
  - `Matplotlib`, `Seaborn` – data visualization
  - `Scikit-learn`, `XGBoost` – model training and evaluation

- **Models Implemented:**
  - Logistic Regression (baseline)
  - Decision Tree Classifier
  - Random Forest Classifier
  - XGBoost Classifier

- **Data Processing Steps:**
  - Removed rows with missing values
  - One-hot encoded categorical features
  - Normalized numeric features
  - Feature selection to reduce overfitting and improve accuracy

## 📈 Results & Key Findings

- **Best Performing Model:** Logistic Regression (based on F1 Score)
- **Notable Insights:**
  - Theft and battery were the most common crimes
  - Majority of crimes did **not** result in arrests
  - Some community areas consistently reported higher crime rates
  - Arrests were harder to predict due to imbalanced target distribution

## ⚠️ Challenges Faced

- Class imbalance (more non-arrest cases)
- Dataset reduction due to memory limits
- Excluded certain features due to noise and inconsistency

## 🔮 Future Improvements

- Use updated post-2017 crime data for modern trend prediction
- Incorporate demographic/socioeconomic data for deeper insights
- Explore advanced models like neural networks or time-series forecasting

## 🧰 Skills Applied

- Data wrangling and preprocessing
- Feature engineering and encoding
- Model tuning with GridSearchCV
- Confusion matrix and performance metrics analysis
- Real-world application of machine learning in public safety

