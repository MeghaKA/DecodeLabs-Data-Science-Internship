# E-Commerce Customer Value Prediction Using Machine Learning

## Project Overview

This project presents an end-to-end machine learning workflow for analyzing e-commerce transaction data and predicting high-value customer orders.

The project combines exploratory data analysis, data preprocessing, feature engineering, machine learning modelling, and model interpretation to identify customer purchasing patterns and support data-driven business decisions.

The objective is to understand transaction behaviour and build a predictive model that can classify high-value orders based on customer purchasing characteristics.


---

# Dataset

The dataset contains:

* 1,200 e-commerce transactions
* Customer transaction details
* Product information
* Payment methods
* Referral sources
* Coupon usage
* Order-related information
* Revenue metrics


Key numerical features:

* Quantity
* Unit Price
* Items in Cart
* Total Price


Key categorical features:

* Product
* Payment Method
* Referral Source
* Coupon Code


---

# Technologies Used

Programming:

* Python

Data Analysis:

* Pandas
* NumPy

Visualization:

* Matplotlib
* Seaborn

Machine Learning:

* Scikit-learn
* Logistic Regression
* Decision Tree
* Random Forest

Machine Learning Concepts:

* Classification
* Feature Engineering
* Model Evaluation
* Feature Importance Analysis


Tools:

* Jupyter Notebook
* Google Colab
* GitHub


---

# Project Workflow


## Phase 1: Exploratory Data Analysis (EDA)

Performed:

* Dataset structure analysis
* Missing value identification
* Statistical analysis
* Distribution analysis
* Outlier detection using IQR method
* Correlation analysis


Key observations:

* CouponCode contained missing values (25.75%)
* TotalPrice showed high-value transaction variations
* Transaction features showed relationships affecting revenue


---


## Phase 2: Data Cleaning and Feature Engineering

Performed:

* Missing value treatment
* Date conversion
* Date-based feature creation

Created new features:

* Year
* Month
* Day
* Revenue-related behavioural features


---


## Phase 3: Business Analysis

Analysed:

* Revenue contribution by product
* Revenue patterns by payment methods
* Referral source performance
* Monthly revenue trends
* Order behaviour patterns


Business insights:

* Certain products contributed significantly higher revenue
* Customer purchasing behaviour varied across transaction patterns
* Revenue trends showed fluctuations across months


---


# Machine Learning Development


## Problem Definition

Task:

Binary Classification


Target:

High Value Order Prediction


The target was created based on transaction value patterns while avoiding direct revenue leakage during modelling.


Features used:

* Quantity
* Unit Price
* Items in Cart
* Month
* Product
* Payment Method
* Referral Source
* Coupon Code


---


# Models Developed


## Logistic Regression

Accuracy:

88.75%


## Decision Tree

Accuracy:

99.17%


## Random Forest

Accuracy:

97.50%



Random Forest was selected for interpretation because of its strong predictive performance and ability to provide feature importance insights.


---


# Model Interpretation


Feature importance analysis showed:

1. Unit Price was the strongest predictor of high-value orders.

2. Quantity was another major factor influencing customer transaction value.

3. Items in Cart contributed additional predictive information.

4. Marketing-related variables such as referral source and coupon usage had lower influence.


This improved transparency and understanding of model decision-making.


---


# Key Findings

* Transaction-level features strongly influenced customer value prediction.
* Tree-based models captured nonlinear relationships effectively.
* Feature engineering improved machine learning performance.
* Model interpretation provided insights into customer purchasing behaviour.


---


# Future Improvements

Future extensions:

* Customer segmentation using clustering methods
* Customer lifetime value prediction
* Time-series sales forecasting
* Explainable AI integration using SHAP
* Interactive dashboards using Power BI/Tableau
* Deployment using Streamlit or Flask


---


# Project Structure
