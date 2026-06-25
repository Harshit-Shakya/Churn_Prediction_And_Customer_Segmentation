# Customer Churn Prediction and Customer Segmentation

## Project Overview

This project focuses on predicting customer churn using Machine Learning and identifying meaningful customer segments using clustering techniques.

The objective is to help businesses understand customer behavior, identify customers at risk of leaving, and develop targeted retention strategies based on customer profiles.

The project was developed using Python and Google Colab on the Telco Customer Churn dataset.

---

## Problem Statement

Customer churn is one of the biggest challenges faced by subscription-based businesses. Acquiring a new customer is often more expensive than retaining an existing one.

This project aims to:

* Predict whether a customer is likely to churn.
* Analyze the factors influencing customer churn.
* Segment customers into different groups based on their characteristics and behavior.
* Provide business insights for customer retention and marketing strategies.

---

## Dataset

The project uses the Telco Customer Churn Dataset containing customer demographic information, service subscriptions, billing details, and churn status.

Key features include:

* Tenure Months
* Monthly Charges
* Total Charges
* Contract Type
* Internet Service
* Payment Method
* Customer Demographics
* Churn Label

Target Variable:

* Churn Label (Yes / No)

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

Performed data exploration and visualization to understand customer behavior and churn patterns.

Analysis included:

* Customer tenure distribution
* Monthly charges distribution
* Churn rate analysis
* Contract type comparison
* Internet service analysis
* Payment method analysis

---

### 2. Data Preprocessing

The following preprocessing steps were performed:

* Handling categorical variables
* One-hot encoding
* Feature selection
* Train-test split
* Data preparation for machine learning models

---

### 3. Customer Churn Prediction

A Random Forest Classifier was used to predict customer churn.

Model evaluation was performed using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix
* Cross Validation

Class imbalance was handled using balanced class weights.

---

### 4. Customer Segmentation

Customer segmentation was performed using K-Means Clustering.

Features used for segmentation:

* Tenure Months
* Monthly Charges
* Total Charges
* Churn Probability

Before clustering:

* Features were standardized using StandardScaler.
* The Elbow Method was used to determine the optimal number of clusters.

---

## Customer Segments Identified

### Budget Loyal Customers

Characteristics:

* Long customer tenure
* Lower spending
* Low churn probability

Business Strategy:

* Loyalty programs
* Cross-selling opportunities

### High Risk Customers

Characteristics:

* Higher churn probability
* Lower customer retention

Business Strategy:

* Personalized retention campaigns
* Special offers and discounts

### Loyal Premium Customers

Characteristics:

* High spending customers
* Long-term relationship with the company

Business Strategy:

* Premium services
* Exclusive benefits and rewards

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab


---

## Key Learnings

Through this project, I gained hands-on experience in:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis
* Machine Learning Classification
* Random Forest Modeling
* Model Evaluation Techniques
* Customer Segmentation using K-Means
* Business-Oriented Data Analysis

---
## Results

The project successfully combines customer churn prediction and customer segmentation to generate actionable business insights.

### Churn Prediction

* Built a Random Forest Classifier to predict customer churn.
* Evaluated the model using Accuracy, Precision, Recall, F1-Score, ROC Curve, and ROC-AUC.
* Generated churn probabilities for each customer to identify customers at risk of leaving.

### Customer Segmentation

Using K-Means Clustering, customers were grouped into three meaningful segments:

#### 1. High Risk New Customers

* High churn probability
* Relatively low customer tenure
* Require immediate retention efforts

#### 2. Budget Loyal Customers

* Low churn probability
* Long-term customers with stable behavior
* Suitable for loyalty and engagement programs

#### 3. Loyal Premium Customers

* High-value customers with longer tenure
* Important for revenue retention
* Suitable for premium offers and personalized services

### Business Impact

* Helps identify customers likely to churn.
* Supports targeted marketing campaigns.
* Improves customer retention strategies.
* Enables data-driven business decision making.


## Future Improvements

* Compare multiple machine learning models
* Build an interactive dashboard
* Deploy the model as a web application
* Implement real-time customer churn prediction

---

## Author

**Harshit Shakya**

B.Tech Information Technology
Delhi Technological University (DTU)
