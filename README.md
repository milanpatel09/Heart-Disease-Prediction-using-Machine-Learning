# Heart Disease Prediction using Machine Learning – Data Analytics Project

This project applies **Data Analytics + Machine Learning** techniques to predict the **10-year risk of Coronary Heart Disease (CHD)** using the well-known **Framingham Heart Study** dataset.  
The workflow includes data loading, EDA, preprocessing, model training, and evaluation.

---

## 📌 Project Overview

Heart disease prediction is a crucial healthcare application.  
This project was developed as part of my **Data Analytics coursework** and focuses on:

- Understanding a real-world medical dataset  
- Performing exploratory data analysis (EDA)  
- Cleaning and preparing the data  
- Training machine learning models  
- Evaluating predictive performance

## 📂 Dataset Description

**Dataset Used:** *Framingham Heart Study* (`framingham.csv`)
**Source:** Framingham Heart Study
**Observations:** ~4,240
**Features (examples):** age, gender, currentSmoker, cigsPerDay, totChol, sysBP, diaBP, BMI, glucose, prevalentHyp, diabetes, prevalentStroke
**Target:** TenYearCHD (1 = disease, 0 = no disease)

## 🔧 Tech Stack
Python 3.8+
pandas, numpy — data manipulation
matplotlib, seaborn — plotting & EDA
scikit-learn — modeling & evaluation
jupyter notebook — experiments & visualization

## ⚙️ Pre-processing:

- Handling missing values
- Encoding categorical variables
- Feature scaling (where applicable)
- Train/test split with stratification

## 🔧 Tech Stack

- Python 3.8+
- pandas, numpy — data manipulation
- matplotlib, seaborn — plotting & EDA
- scikit-learn — modeling & evaluation
- jupyter notebook — experiments & visualization

## 📊 Model Implementation & Insights

We implemented **two machine learning models:** **Logistic Regression** and **Random Forest Classifier** to predict the 10-year risk of Coronary Heart Disease (CHD).

### 🔢 Model Performance Metrics

- **Logistic Regression**
  - Accuracy: **84.67%**
  - Precision: **0.62**
  - Recall: **0.06**
  - F1-Score: **0.11**

- **Random Forest Classifier**
  - Accuracy: **85.38%**
  - Precision: **0.76**
  - Recall: **0.10**
  - F1-Score: **0.11**

### 🧠 Insights

- **Random Forest performed better than Logistic Regression**, achieving higher accuracy, precision, and recall.
- Logistic Regression acted as a **strong baseline model**, but its very low recall indicates difficulty in identifying true CHD-positive patients because of the dataset’s **class imbalance**.
- Random Forest, being an ensemble model, **handled non-linear patterns and feature interactions more effectively**, making it more reliable for heart disease prediction.
- Overall, Random Forest is the **preferred model**, while Logistic Regression provides interpretability and foundational understanding.

## 🙋 Contact

Created by milanpatel09 — contributions and feedback welcome.
