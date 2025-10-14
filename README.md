# Group-6.Predicting-Customer-Churn-utilising-Machine-Learning.
# Customer Churn Prediction Project  
**University of Bristol | MGRC20007 - Machine Learning for Data-Driven Business Decision Making**

---

## 1. Overview  

This project aims to predict **customer churn** for a retail banking dataset using multiple supervised learning algorithms.  
The focus is on building a **reproducible machine learning pipeline** that combines feature engineering, cross-validation, and explainability methods to generate both predictive and actionable business insights.  

Our models are benchmarked on multiple metrics (Accuracy, Precision, Recall, F1, ROC-AUC, and Lift@10%) and interpreted through SHAP feature explainability and fairness evaluation across gender and geography.  

---

## 2. Project Objectives  

1. Develop a unified pipeline for data preprocessing, feature engineering, and model training.  
2. Compare three models from different algorithmic families:  
   - Logistic Regression (baseline linear model)  
   - Random Forest (bagging ensemble)  
   - XGBoost (boosting ensemble)  
3. Apply **SMOTE** to address class imbalance (Exited = 1 minority).  
4. Evaluate and compare model performance using **5-fold cross-validation** and an external holdout test.  
5. Interpret the model using **Feature Importance** and **SHAP**.  
6. Conduct **fairness checks** (Gender and Geography) to ensure responsible banking applications.  
7. Translate analytical findings into **business actions** — customer retention targeting and expected revenue estimation.  

---

## 3. Team Members  

| Name | Role | Responsibilities |
|------|------|------------------|
| **Parker** | Lead Analyst | Feature engineering, model development (LR, RF, XGB), SMOTE balancing, pipeline integration, explainability |
| **Karolina** | Data Analyst | Data exploration, EDA visualisation, feature summary |
| **Yiqi Cheng** | Fairness & SHAP Analyst | Explainability analysis (SHAP), fairness check by gender and geography |
| **Shuaibo Wang** | Business Analyst | Business insight translation, retention KPI design, responsible banking |
| **Guangyuan An** | Report Editor | Conclusion, report formatting, final integration |

---

## 4. Repository Structure  
