# Group-6.Predicting-Customer-Churn-utilising-Machine-Learning.
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

## 3. Repository Structure  
├── Assessment1.ipynb          # Main Jupyter Notebook with all models and outputs
├── Assessmnet1.html            # Exported HTML (for reproducibility)
├── requirements.txt                  # Dependency list
├── README.md                         # Project documentation (this file)

---

## 4. Reproducibility Notes
	•	All random processes were seeded using random_state=42.
	•	All models were trained using the same preprocessing pipeline (ColumnTransformer + StandardScaler + OneHotEncoder).
	•	Dataset splitting was fixed at 80% training and 20% testing for consistent evaluation.
	•	SMOTE oversampling was applied only to the training set to prevent data leakage.

---
## 5. Responsible AI Declaration

Generative AI tools (e.g., ChatGPT) were used only for:
	•	Debugging code
All outputs were manually verified for accuracy and correctness.
No confidential or proprietary data was uploaded to any external system.
---

## 6. License
© 2025 University of Bristol – For academic use only.
Unauthorized reproduction or redistribution of this repository is prohibited under University regulations.


