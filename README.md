
# 📊 Customer Churn Prediction using Machine Learning

## 📖 Overview

This project uses Machine Learning to predict customer churn based on customer information such as age, gender, tenure, monthly charges, contract type, and internet service. Multiple classification models were trained and evaluated to identify the best-performing model for predicting customer churn and supporting customer retention strategies.

## 🎯 Objectives

* Clean and preprocess the dataset
* Perform data exploration and analysis
* Train multiple classification models
* Compare model performance
* Optimize models using hyperparameter tuning
* Predict customer churn accurately

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Jupyter Notebook

## 🤖 Machine Learning Models

* Logistic Regression
* Random Forest Classifier
* Support Vector Machine (SVM)
* XGBoost Classifier

## 📊 Model Evaluation

The models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report
* 5-Fold Cross-Validation
* GridSearchCV

## 📁 Dataset

* **Target Variable:** `Churn`
* **Total Records:** 1,000
* **Features:**

  * Age
  * Gender
  * Tenure
  * MonthlyCharges
  * ContractType
  * InternetService
  * TotalCharges
  * TechSupport

## 🔄 Workflow
```
Data Collection
      ↓
Data Cleaning
      ↓
Data Preprocessing
      ↓
Categorical Encoding
      ↓
Train-Test Split
      ↓
Feature Scaling
      ↓
Model Training
      ↓
Cross-Validation
      ↓
Hyperparameter Tuning
      ↓
Model Evaluation
      ↓
Customer Churn Prediction
```

## 📈 Model Performance

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 91.00% |
| Random Forest | 100.00% |
| SVM | 97.50% |
| XGBoost | 100.00% |

## 📌 Results

The classification models were compared using accuracy, precision, recall, F1-score, and cross-validation.

Random Forest and XGBoost achieved the highest test accuracy of **100%**, while SVM achieved **97.50%**.

Hyperparameter tuning improved Logistic Regression accuracy from **91.00% to 92.50%**.

The results demonstrate the potential of machine learning for customer churn prediction. Further independent validation is recommended to confirm model generalization and investigate the unusually high accuracy scores.

## 🚀 Future Improvements

* Perform feature importance analysis
* Investigate potential data leakage and overfitting
* Improve model generalization
* Deploy the model using Streamlit
* Develop a real-time customer churn prediction system

## 📌 Conclusion

This project demonstrates the application of supervised machine learning techniques for customer churn prediction. By implementing multiple classification algorithms, data preprocessing, cross-validation, and hyperparameter tuning, the project provides a structured approach to identifying potential customer churn and supporting data-driven retention strategies.
