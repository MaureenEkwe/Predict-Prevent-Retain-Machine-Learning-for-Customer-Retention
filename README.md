# Predict, Prevent, Retain: Machine Learning for Customer Retention

## Overview
This project aims to predict customer churn for a telecom company using classification models. Churn is a major business concern because losing customers leads to lost revenue. The goal is to flag at-risk customers before they leave and understand what drives churn behavior.

## Dataset
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/563/iranian+churn+dataset )
- Contains data for 3,150 customers over a 12-month period
- Features include: complaints, call failures, usage patterns, account details, and more
- Input data reflects the first 9 months; churn labels reflect the outcome at month 12

## Libraries Used
This project was built using the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`
- `imblearn` (for SMOTE)

### Installation

#### Option 1: Using `pip`

pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn

#### Option 2: Using conda

conda install pandas numpy matplotlib seaborn scikit-learn
conda install -c conda-forge xgboost imbalanced-learn


## Key Steps
- Data Preprocessing (scaling, encoding, cleaning)
- Exploratory Data Analysis (EDA)
- Class Imbalance handled using SMOTE
- Trained and compared four classification models:
  - Logistic Regression
  - Naive Bayes
  - Random Forest
  - XGBoost

##  Results
- **Best Models**: Random Forest & XGBoost (both ~96% accuracy, F1-score ~0.88)
- **Top Features Linked to Churn**:
  - Number of complaints
  - Low monthly usage
  - Short subscription length
  - Call failures

## Files
- `Customer_Churn.csv`:  dataset
- `Customer_Churn_Analysis.ipynb`: Full analysis notebook
- `MaureenEkwebelem_PredictPreventRetain_MLforCustomerRetention.docx`: Final report


## Author
Maureen Ekwebelem
B.S. in Human Development (Minor: Global Health), Cornell University
M.S. Candidate in Data Science (Concentration: Machine Learning & AI), Fordham University
