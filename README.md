# 📺 Netflix Customer Churn Analysis

A machine learning project that predicts customer churn in an OTT platform and uncovers the key factors driving
user attrition. This project blends data exploration, predictive modeling, and interpretability to turn
raw user behavior into actionable retention insights.

---

## 🎯 Objective

The goal of this project is to:

- Predict whether a customer will churn  
- Identify key factors influencing churn behavior  
- Compare performance across multiple machine learning models  
- Provide insights to improve customer retention strategies  

---

## 🚀 Project Workflow

1. **Data Loading & Inspection**
2. **Data Preprocessing & Feature Engineering**
3. **Exploratory Data Analysis (EDA)**
4. **Model Building & Evaluation**
5. **Model Interpretation (Logistic Regression)**
6. **Comparison of Tree-Based Models**

---

## 🗂️ Dataset Overview

The dataset contains customer-level information such as:

- Subscription type  
- Payment method  
- Login activity  
- Usage patterns  
- Churn status (target variable)  

---

## 🧹 Data Preprocessing

- Removed unnecessary columns (`customer_id`)
- Separated numerical and categorical features  
- Applied **one-hot encoding** to categorical variables  
- Standardized numerical features using **StandardScaler**  
- Combined processed features into final dataset  

---

## 📊 Exploratory Data Analysis (EDA)

Key visualizations performed:

- Churn distribution  
- Subscription type vs churn  
- Login inactivity vs churn  
- Payment method vs churn  

### 🔍 Key Insights

- Users with **higher inactivity** are more likely to churn  
- **Subscription type** significantly impacts churn  
- **Payment methods** influence customer retention behavior  

---

## 🔗 Correlation Analysis

- Heatmap used to identify relationships between numerical features  
- Helped detect patterns and potential multicollinearity  

---

## 🤖 Model Building

### 1. Logistic Regression (Interpretability Focus)

- Used to understand **feature impact on churn**
- Outputs coefficients and odds ratios  

**Metrics Evaluated:**
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

---

### 📌 Key Churn Drivers

- Features with high coefficients indicate strong influence on churn  
- Odds ratio helps interpret likelihood of churn change  

---

### 📈 ROC Curve

- Evaluated model performance using ROC-AUC  
- Visualized trade-off between true positive rate and false positive rate  

---

### 🌳 Decision Tree

- Captures non-linear relationships  
- Easy to interpret decision paths  

---

### 🌲 Random Forest

- Ensemble model for improved accuracy  
- Reduces overfitting compared to single decision tree  

---

## 📊 Model Comparison

| Model               | Strength                          |
|--------------------|----------------------------------|
| Logistic Regression| Interpretability                 |
| Decision Tree      | Simplicity & rule-based logic    |
| Random Forest      | Higher accuracy & robustness     |

---

## 🏁 Conclusion

- Logistic Regression provided **clear insights into churn drivers**  
- Tree-based models delivered **better predictive performance**  
- Combining both approaches gives:
  - 📌 Interpretability (why customers churn)  
  - 📈 Accuracy (who will churn)  

These insights can help OTT platforms design **targeted retention strategies**, reduce churn, and improve customer lifetime value.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn** – Machine Learning models  
- **Joblib** – Model persistence  

---


