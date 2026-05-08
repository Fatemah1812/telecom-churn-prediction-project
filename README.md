# Telecom Customer Churn Prediction

## Project Overview

This project focuses on predicting customer churn for a telecom company using machine learning techniques. The objective is to identify customers who are likely to cancel their services based on customer demographics, account information, and service usage behavior.

The project applies data preprocessing, exploratory data analysis, feature engineering, and classification modeling to support customer retention strategies and reduce churn risk.

---

## Business Problem

Customer churn is a major challenge in the telecom industry because losing customers directly impacts company revenue. Predicting churn allows businesses to proactively identify at-risk customers and improve retention efforts through targeted interventions.

---

## Objectives

* Analyze telecom customer behavior and service usage
* Perform exploratory data analysis (EDA)
* Build and evaluate machine learning classification models
* Identify key factors influencing customer churn
* Optimize model performance using evaluation metrics

---

## Dataset

The dataset contains telecom customer information including:

* Demographics
* Contract details
* Internet services
* Monthly charges
* Payment methods
* Customer tenure
* Churn status

Target Variable:

* Churn (Yes/No)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* CatBoost
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Machine Learning Models

The following classification models were trained and evaluated:

* Logistic Regression
* Random Forest Classifier
* CatBoost Classifier

---

## Project Workflow

### 1. Data Preprocessing

* Handled missing values
* Encoded categorical variables
* Cleaned and prepared data for modeling
* Performed feature engineering

### 2. Exploratory Data Analysis (EDA)

* Analyzed churn distribution
* Investigated customer behavior patterns
* Visualized important relationships between features

### 3. Model Training

* Trained multiple classification models
* Compared model performance
* Optimized predictive accuracy

### 4. Model Evaluation

Models were evaluated using:

* ROC-AUC
* Accuracy
* Precision
* Recall
* Confusion Matrix

---

## Results

The CatBoost model achieved the best predictive performance for identifying customers at risk of churn.

Key factors influencing churn included:

* Contract type
* Monthly charges
* Customer tenure
* Internet service usage

The project demonstrated how machine learning can support customer retention strategies and business decision-making.

---

## Business Insights

The analysis showed that customers with shorter contracts and higher monthly charges were more likely to churn.

These findings can help telecom companies:

* Improve customer retention campaigns
* Identify high-risk customers earlier
* Develop personalized customer offers
* Reduce customer turnover

---

## Future Improvements

* Deploy the model using Streamlit or Flask
* Improve hyperparameter tuning
* Build automated prediction pipelines
* Explore deep learning approaches

---

## Repository Structure

```bash
telecom-churn-prediction/
│
├── README.md
├── requirements.txt
├── telecom-churn-prediction.ipynb
```

---

## Author

Fatemah Ayoub

LinkedIn:
https://linkedin.com/in/fatemahayoub

GitHub:
https://github.com/Fatemah1812

