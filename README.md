# 🎇 Diwali Sales Analysis & Customer Segmentation

## 📌 Project Overview

This project focuses on analyzing Diwali sales data to extract meaningful business insights and build machine learning models to predict high-value customers.

The goal is to help businesses understand customer behavior and improve marketing strategies during festive seasons.

---

## 📂 Dataset Description

The dataset contains customer purchase data with the following features:

- User_ID
- Customer Name
- Product ID
- Gender
- Age / Age Group
- Marital Status
- State / Zone
- Occupation
- Product Category
- Orders
- Amount

---

## 🧹 Data Preprocessing

- Removed unnecessary columns (e.g., unnamed columns)
- Handled missing values
- Converted data types
- Created new features:
   - Total_Spend = Orders × Amount
   - Spender_Type (High / Low)
   - High_Spender (0 / 1)

---

## 📊 Exploratory Data Analysis (EDA)

Key analysis performed:

- Gender vs Spending
- Age Group vs Spending
- State-wise sales distribution
- Occupation-based purchasing trends
- Product category performance

---

## 🤖 Machine Learning Models

Goal: Predict whether a customer is a High Spender

Models used:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📈 Model Performance

Model| Accuracy
Logistic Regression| ~91%
Decision Tree| ~89%
Random Forest| ~91%

- Random Forest performed best due to handling non-linear relationships effectively.

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 🔍 Key Insights

- Married women aged 26–35 are the highest spenders
- States like Uttar Pradesh, Maharashtra, Karnataka generate maximum revenue
- Occupations like IT, Healthcare, Aviation show higher spending patterns

---

## 🧠 Customer Segmentation

Using KMeans clustering:

- Cluster 0 → Low Spenders
- Cluster 1 → Medium Spenders
- Cluster 2 → High Spenders

---

## 💡 Business Recommendations

- Target high-value customer segments with personalized offers
- Focus marketing on top-performing regions
- Promote high-demand product categories
- Use ML model to identify potential high spenders

---

## 🚀 Future Improvements

- Build a Streamlit dashboard
- Add recommendation system
- Use advanced models (XGBoost, LightGBM)
- Deploy as a web application

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## 📌 Conclusion

This project demonstrates how data analysis and machine learning can be used to understand customer behavior and improve business decision-making during high-sales events like Diwali.

---

# ⭐ If you like this project, give it a star!
