# 🎵 Predicting GenZ Music Energy Via Psychographic And Behavioural Indicator Analysis Using Machine Learning

A machine learning project that predicts a user's ideal music energy by analyzing psychographic traits and daily behavioural habits. This research shifts the focus from traditional historical listening patterns to psychological indicators, providing a data-driven foundation for personalized "cold-start" recommendations on music streaming platforms.

## 📖 Overview

New streaming platforms often struggle to recommend the right music to GenZ users without prior listening history, which frequently leads to poor recommendations, user frustration, and app abandonment. Traditional recommendation algorithms heavily prioritize physical listening history, frequently neglecting the psychographic traits and current moods that dictate immediate music choices. 

This project leverages machine learning to analyze a primary dataset of daily habits, personality traits, and moods such as lifestyle pace, empathy level, listening context, etc. to predict a user's preferred music energy. By identifying the psychological factors that drive music preferences, this project provides a robust solution to the recommendation "cold-start" problem applicable to modern digital platforms.

## ✨ Key Features

* **Primary Data Collection & EDA:** Analyzed a structured survey dataset with a specific demographic emphasis on GenZ (ages 14 to 29) to capture modern metrics like lifestyle pace, listening mood, empathy level, etc.
* **Extensive Model Comparison:** Evaluated and optimized six machine learning classifiers (Random Forest, Support Vector Machine, Logistic Regression, Gaussian Naive Bayes, K-Nearest Neighbors, Decision Tree) using `GridSearchCV`.
* **Custom "Overfitting Gap" Validation:** Implemented a rigorous validation framework that mathematically defined an overfitting threshold to guarantee model reliability and real-world generalizability.

## 📊 Key Findings & Results

* **Best Model:** The Random Forest classifier achieved superior performance, proving highly effective at handling complex, non-linear lifestyle and psychographic data.
* **Accuracy:** 82.14% with an ROC-AUC score of 0.85. The model achieved an exact Overfitting Gap of 0.0000, confirming exceptional generalizability without data memorization.
* **Feature Importance:** The model identified *Music Focus Element*, *Empathy Level*, and *Lifestyle Pace* as the strongest predictors. This successfully highlights that deep psychological and behavioral patterns are as critical as historical listening data in determining music preferences.

## 🛠️ Technologies

* **Language:** Python
* **Environment:** Jupyter Notebook
* **Data Manipulation & Analysis:** NumPy & Pandas
* **Machine Learning:** Scikit-Learn (Model implementations, `GridSearchCV`, `LabelEncoder`, `StandardScaler`)
* **Data Visualization:** Matplotlib & Seaborn
