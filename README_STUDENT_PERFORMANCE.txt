# Student Performance Prediction using Machine Learning

## Project Overview

This project aims to predict a student's academic performance based on study habits, previous academic records, extracurricular activities, sleep patterns, and practice test participation.

Using machine learning regression techniques, the model analyzes various factors affecting student performance and predicts the Performance Index.

---

## Problem Statement

Educational institutions can use predictive analytics to identify factors influencing student performance and support data-driven academic improvement strategies.

### Target Variable

- Performance Index

---

## Dataset Information

Dataset Size:
- Rows: 10,000
- Columns: 6

### Features

| Feature | Description |
|----------|-------------|
| Hours Studied | Number of study hours per day |
| Previous Scores | Previous academic scores |
| Extracurricular Activities | Participation in extracurricular activities (Yes/No) |
| Sleep Hours | Average sleep hours |
| Sample Question Papers Practiced | Number of sample papers solved |
| Performance Index | Student performance score (Target Variable) |

---

## Project Workflow

### 1. Data Collection
- Load dataset using Pandas.

### 2. Data Preprocessing
- Check missing values.
- Encode categorical variables.
- Feature selection.

### 3. Exploratory Data Analysis (EDA)
- Distribution analysis.
- Correlation analysis.
- Feature impact on performance.

### 4. Model Building

Regression Algorithms:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

### 5. Model Evaluation

Evaluation Metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure
