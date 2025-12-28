 Task 1: Term Deposit Subscription Prediction (Bank Marketing)

 Objective

Predict whether a bank customer will subscribe to a term deposit as part of a marketing campaign using classification and explainable AI.

---

 Dataset

**Bank Marketing Dataset (UCI Repository)**
Contains customer attributes such as age, job, marital status, education, balance, and previous campaign outcomes.
 Approach

1. **Data Loading & Exploration**

   * Imported dataset using pandas.
   * Performed summary statistics and correlation analysis.
2. **Preprocessing**

   * Encoded categorical features using OneHotEncoder.
   * Handled missing and duplicate values.
3. **Modeling**

   * Trained **Logistic Regression** and **Random Forest Classifier** models.
   * Evaluated models using **F1-score**, **Confusion Matrix**, and **ROC Curve**.
4. **Explainable AI**

   * Used **SHAP** to explain top 5 predictions and visualize feature importance.

 Results & Insights

* Random Forest achieved higher F1-score and better ROC performance.
* Top predictors influencing deposit subscription: **duration**, **balance**, and **previous campaign outcome**.
* SHAP interpretation revealed that longer call duration and positive past interactions increase subscription likelihood.
 Skills Gained

* Classification modeling
* Feature encoding and handling categorical data
* Model explainability (SHAP-based XAI)
* Customer behavior analytics
