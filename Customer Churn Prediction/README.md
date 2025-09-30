# Customer Churn Prediction

This project predicts customer churn using the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn).  
The workflow includes data cleaning, exploratory data analysis (EDA), feature encoding, handling class imbalance with SMOTE, model training with multiple classifiers, and saving the trained model for inference.

---

## 🚀 Features
- Exploratory Data Analysis (EDA) with histograms, boxplots, and correlation heatmaps.
- Data preprocessing:
  - Handle missing values in `TotalCharges`.
  - Label encoding of categorical variables.
  - Train/test split and SMOTE for class balancing.
- Model training with:
  - Decision Tree
  - Random Forest
  - XGBoost
- Cross-validation for model performance evaluation.
- Model saving and loading with `pickle`.
- Example inference pipeline to predict churn for a single customer.

---

## 🛠 Requirements
Install dependencies with:

```bash
pip install -r requirements.txt
