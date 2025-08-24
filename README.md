# Customer-Churn-Prediction
Customer churn prediction using Logistic Regression, Random Forest, KNN, and XGBoost. Includes SMOTE for imbalance handling, K-Means for segmentation, and model explainability with Feature Importance and SHAP to generate insights for customer retention
##  Project Overview
This project predicts customer churn using machine learning and provides business insights for retention strategies.  
It combines predictive modeling, segmentation, and explainability to not only identify customers at risk of leaving but also understand **why** they might churn.


##  Features
- **Classification Models:** Logistic Regression, Random Forest, KNN, XGBoost  
- **Data Balancing:** SMOTE to handle class imbalance  
- **Customer Segmentation:** K-Means clustering for grouping customers  
- **Explainability:** Feature Importance & SHAP for interpretability  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, ROC-AUC  
## 🗂 Dataset
- The dataset contains customer information such as demographics, usage patterns, and account details.  
- **Target variable:** `Churn` (Yes/No).  
- Preprocessing steps include handling missing values, encoding categorical variables, scaling features, and balancing classes.

##  Methodology
1. **Data Preprocessing**  
   - Missing value handling  
   - Label encoding & feature scaling  
   - SMOTE for class imbalance  

2. **Model Training**  
   - Logistic Regression (baseline)  
   - Random Forest (bagging)  
   - K-Nearest Neighbors (distance-based)  
   - XGBoost (boosting)  

3. **Customer Segmentation**  
   - Applied K-Means to identify customer clusters (loyal, at-risk, new, etc.)  

4. **Model Explainability**  
   - Feature Importance (RF)  
   - SHAP values for local & global interpretability  


## Results
- XGBoost delivered the best performance in terms of ROC-AUC and F1-score.  
- SHAP revealed that factors like **tenure, monthly charges, and contract type** were key drivers of churn.  
- K-Means segmentation helped identify customer groups for targeted retention strategies.  


##  Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, imbalanced-learn (SMOTE), SHAP, Matplotlib/Seaborn  


## ▶️ How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/25pravin/customer-churn-prediction.git
   cd customer-churn-prediction
