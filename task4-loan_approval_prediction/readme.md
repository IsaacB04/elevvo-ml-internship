**Task 4: Loan Approval Prediction**

This task focuses on building a machine learning model to predict whether a loan application will be approved. The dataset contains demographic, financial, and categorical attributes, requiring careful preprocessing and handling of class imbalance.

**Description**

Dataset used: Loan Approval Prediction Dataset (Kaggle)
Goal: Predict whether a loan application will be approved
Main steps:
- Load, clean, and preprocess the dataset
- Handle missing values and encode categorical variables
- Address class imbalance using techniques such as SMOTE
- Train classification models (Logistic Regression, Decision Tree, etc.)
- Compare model performance across different algorithms
- Evaluate results using precision, recall, accuracy, and F1-score
- Visualize confusion matrices for interpretability

**Tools & Libraries**

- Python
- Pandas
- Scikit-learn

**Covered Topics**

- Binary Classification
- Handling Imbalanced Data
- Evaluation Metrics (Precision, Recall, F1-score)
- Sampling Techniques (SMOTE)
- Model Comparison

**Files in this Folder**

- Elevvo_Task_4_loan_approval_prediction.ipynb — Notebook with preprocessing, modeling, and evaluation
- elevvo_task_4_loan_approval_prediction.py
- loan_approval.csv
  
**How to Run**

- Install required libraries:
pip install pandas scikit-learn imbalanced-learn matplotlib seaborn

- Open the notebook:
jupyter notebook Elevvo_Task_4_loan_approval_prediction.ipynb

- Run all cells to reproduce preprocessing, SMOTE balancing, modeling, and evaluation steps.

**Model Summary**

This task applies classification algorithms to predict loan approval outcomes.
Due to class imbalance, SMOTE is used to generate a balanced dataset, improving model generalization.
Final model performance is assessed using standard evaluation metrics and visualization tools.

**Credits**

Completed as part of the Elevvo Pathways Machine Learning Internship.
