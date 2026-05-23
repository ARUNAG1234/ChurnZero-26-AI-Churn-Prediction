# ChurnZero-26-AI-Churn-Prediction
📊 ChurnZero 26 – AI-Driven Banking Customer Churn Prediction

🚀 Project Overview

Machine Learning model to predict bank customer churn and help reduce customer loss using early prediction.

🎯 Problem Statement

Banks lose customers due to low engagement and poor service.

Goal: Predict churn customers in advance and reduce financial loss.

💰 Business Impact
Error  Type	     Cost
False Negative	₹40,000
False Positive	₹500

👉 Focus: Reduce False Negatives (High Recall)

📊 Dataset
Train: 8,101 rows, 98 features
Test: 2,026 rows, 97 features
🧠 Approach
Data Cleaning
Encoding
Feature Engineering
LightGBM Model
Threshold Tuning
🤖 Model

LightGBM Classifier (Final Model)

📈 Performance
ROC-AUC: 0.9999
Precision: 1.0
Recall: 0.9885
F1 Score: 0.9942
📁 Output
predictions.csv (final submission file)
🛠️ Install & Run
pip install -r requirements.txt
python src/model.py
🏁 Conclusion

A machine learning system that predicts churn customers with high accuracy and helps banks improve retention.
