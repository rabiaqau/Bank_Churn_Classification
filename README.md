# Bank_Churn_Classification
Build a complete machine learning pipeline for binary classification (customer churn prediction) using Logistic Regression and K-Nearest Neighbors (KNN). The assignment covers data loading, preprocessing, EDA, scaling, model training, evaluation, inspection, and hyperparameter tuning.
# 🚀 Customer Churn Prediction Pipeline

## 🌍 Overview

Customer churn is one of the most critical business challenges in subscription-based and service-driven industries. **Churn rate** refers to the percentage of customers who stop using a company’s product or service over a specific period.

### 📉 What is Churn Rate?

Churn rate measures customer attrition and is calculated as:

[
\text{Churn Rate} = \frac{\text{Customers Lost During Period}}{\text{Total Customers at Start of Period}} \times 100
]

### Why does churn matter?

Losing customers directly impacts:

* 💰 Revenue growth
* 📊 Customer lifetime value (CLV)
* 📉 Business stability
* 🎯 Marketing efficiency

Acquiring a new customer often costs significantly more than retaining an existing one. This makes **customer churn prediction** a high-value machine learning problem.

---

# 🎯 Project Goal

Build a **complete end-to-end machine learning pipeline** for **binary classification** to predict whether a customer will churn or stay.

The project uses two classification algorithms:

* 🔹 **Logistic Regression** → A statistical baseline model for binary classification
* 🔹 **K-Nearest Neighbors (KNN)** → A distance-based learning algorithm

The goal is to compare both models and identify the most effective approach for predicting customer churn.

---

# 🧠 Project Objectives

## 1️⃣ Data Loading & Understanding

The first step is importing and understanding the dataset.

### Tasks:

* Load dataset using Pandas
* Explore rows and columns
* Check data types
* Understand target variable (`Churn`)
* Identify missing values

### Objective:

Gain a strong understanding of the dataset structure before modeling.

---

# 🔍 Exploratory Data Analysis (EDA)

Understand customer behavior patterns through visual and statistical exploration.

### Tasks:

* Analyze churn distribution
* Visualize categorical features
* Analyze numerical features
* Check feature correlations
* Identify trends related to churn

### Objective:

Discover hidden patterns that influence customer retention.

### Example Questions:

* Are long-term customers less likely to churn?
* Does monthly billing affect churn?
* Which services increase churn probability?

---

# 🧹 Data Preprocessing

Prepare raw data for machine learning algorithms.

### Tasks:

* Handle missing values
* Remove duplicates
* Encode categorical variables
* Convert target labels into binary format
* Feature selection

### Objective:

Transform messy raw data into clean, model-ready input.

---

# ⚖️ Feature Scaling

Scaling ensures fair distance calculations and stable optimization.

### Why Scaling?

* Logistic Regression performs better with normalized features
* KNN heavily depends on distance calculations

### Tasks:

* Apply `StandardScaler` or `MinMaxScaler`
* Scale training and testing datasets

### Objective:

Improve model performance and consistency.

---

# 🤖 Model Training

Train classification models on prepared data.

## Logistic Regression

A linear model that estimates churn probability.

#
