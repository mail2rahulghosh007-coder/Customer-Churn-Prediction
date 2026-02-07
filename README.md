#  Customer Churn Prediction

##  Project Overview
This project focuses on building an **end-to-end Customer Churn Prediction system** using machine learning techniques. The objective is to identify customers who are likely to discontinue a service, enabling businesses to take proactive retention measures.

---

##  Methodology

- Conducted **extensive Exploratory Data Analysis (EDA)** using multiple visualizations to understand customer behavior and data patterns.
- Performed data preprocessing, including:
  - Handling categorical variables using **Label Encoding**
  - Feature selection and data cleaning
- Split the dataset into training and testing sets for evaluation.
- Also used SMOTE to solve imbalanced data problem.

---

##  Machine Learning Models

The following models were implemented and compared:

- Decision Tree Classifier  
- Random Forest Classifier  
- XGBoost Classifier  

 **Best Performing Model:**  
- Random Forest achieved **77.7% accuracy**, outperforming other models.

---

##  Model Optimization

- Applied **GridSearchCV** for hyperparameter tuning on the Random Forest model.
- Improved model accuracy from **77.7% to 78%**.
- Selected the optimized Random Forest model as the final model.

---

##  Model Saving & Deployment Readiness

- Saved the final optimized model using serialization for future deployment.

---

##  Results Summary

| Model | Accuracy |
|------|----------|
| Decision Tree | Baseline |
| XGBoost | Competitive |
| **Random Forest (Tuned)** | **78%** |

---

##  Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  

---





