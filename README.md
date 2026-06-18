# Credit-Card-Fraud-Detection
Developed a machine learning-based credit card fraud detection system using Logistic Regression, Random Forest, and XGBoost. Performed exploratory data analysis, handled class imbalance with SMOTE, evaluated models using ROC-AUC and cross-validation and applied SHAP for model interpretability. Saved trained models using Joblib for future deployment

## 🎯 Objectives

* Detect fraudulent credit card transactions accurately.
* Handle class imbalance using SMOTE.
* Compare multiple machine learning models.
* Evaluate performance using various metrics.
* Interpret model predictions using SHAP.
* Save trained models for future deployment.

---

## 📂 Dataset

The dataset contains anonymized credit card transactions with:

* **Features:** V1–V28 (PCA transformed variables)
* **Additional Features:** Time, Amount
* **Target Variable:**

  * 0 → Legitimate Transaction
  * 1 → Fraudulent Transaction

---

## 🛠 Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* XGBoost
* SHAP
* Joblib

---

## 📊 Exploratory Data Analysis (EDA)

Performed:

* Class distribution analysis
* Correlation heatmap
* Feature visualization
* Transaction amount analysis
* Fraud vs Non-fraud comparison

---

## ⚙ Data Preprocessing

* Data cleaning
* Train-Test Split
* Feature Scaling
* Handling class imbalance using **SMOTE**
* Data preparation for model training

---

## 🤖 Machine Learning Models

### 1. Logistic Regression

Used as a baseline model.

### 2. Random Forest Classifier

Captures non-linear relationships and feature interactions.

### 3. XGBoost Classifier

Gradient boosting model used for improved predictive performance.

---

## 📈 Model Evaluation

Models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix
* Cross Validation
* ROC Curve

---

## 🔍 Model Explainability

SHAP (SHapley Additive exPlanations) was used to:

* Understand feature importance.
* Explain individual predictions.
* Improve model transparency.

---

## 💾 Model Persistence

Trained models and preprocessing objects were saved using **Joblib**, enabling future deployment and reuse.

---

## 📁 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── P1_Credit_Cd_fraud.ipynb
├── model.pkl
├── scaler.pkl
├── requirements.txt
├── README.md
└── dataset/
```

---

## 🚀 Future Improvements

* Hyperparameter tuning with GridSearchCV
* Precision-Recall curve analysis
* Threshold optimization
* Streamlit web application deployment
* Real-time fraud detection
* Experiment tracking using MLflow

---

## 📌 Key Learnings

* Handling imbalanced datasets using SMOTE.
* Comparing multiple classification algorithms.
* Model evaluation beyond accuracy.
* Understanding feature importance with SHAP.
* Saving and deploying machine learning models.

---

## 📜 Conclusion

This project demonstrates an end-to-end machine learning workflow for fraud detection, from data preprocessing and exploratory analysis to model development, evaluation, explainability, and deployment readiness. The techniques used are applicable to real-world anomaly detection and financial risk management problems.

---

**Author:** Bryan Menezes
