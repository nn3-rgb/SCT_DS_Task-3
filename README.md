**📄 Description**

This project focuses on building a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data.

The dataset used is the Bank Marketing Dataset, which contains information collected from direct marketing campaigns of a banking institution.

**🎯 Objective**

To develop a machine learning model that:

Predicts customer subscription behavior

Uses a Decision Tree algorithm

Applies data preprocessing and feature engineering

Evaluates performance using classification metrics

**📊 Dataset Information**

Dataset Name: Bank Marketing Dataset

Source: UCI Machine Learning Repository / Kaggle

Target Variable: deposit (Yes / No)

Total Records: 11,162

Total Features: 17

Feature Types:

Numerical: age, balance, duration, campaign, pdays, previous

Categorical: job, marital, education, housing, loan, contact, month, poutcome

**🧠 Machine Learning Model**

Algorithm: Decision Tree Classifier

Library: scikit-learn

Max Depth: 5

Train-Test Split: 80% / 20%

Evaluation Metrics:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

**⚙️ Workflow**

Load dataset

Data cleaning & preprocessing

Feature encoding (One-Hot Encoding)

Feature scaling (StandardScaler)

Train Decision Tree model

Evaluate performance

Visualize:

Confusion Matrix

Feature Importance

Decision Tree structure

**📈 Model Performance**

Accuracy: ~81%

Balanced precision and recall

Good interpretability using decision tree visualization

**📂 Project Structure**
Task_03_Decision_Tree/
│
├── bank.csv
├── SCT_DS_3.ipynb
├── README.md
└── requirements.txt

**🛠 Technologies Used**

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Google Colab / Jupyter Notebook

**📌 Conclusion**

The Decision Tree model successfully predicts customer subscription behavior with good accuracy. Feature importance analysis shows that duration, balance, and previous contact outcomes play a significant role in customer decision-making.
