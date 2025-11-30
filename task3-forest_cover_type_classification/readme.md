**Task 3: Forest Cover Type Classification**

This task focuses on predicting forest cover type using multiclass classification models. The dataset contains cartographic and environmental features describing forested areas, and the goal is to classify each observation into one of several forest cover categories.

**Description**

Dataset used: Covertype Dataset (UCI Machine Learning Repository)
Goal: Predict forest cover type using environmental and geographic features
Main steps:
- Load and clean the dataset
- Handle categorical variables appropriately
- Perform feature scaling (if required)
- Train and evaluate multi-class classification models
- Generate a confusion matrix
- Visualize feature importance for model interpretation

**Tools & Libraries**

- Python
- Pandas
- Scikit-learn
- XGBoost

**Covered Topics**

- Multi-class Classification
- Tree-based Modeling
- Categorical Handling
- Model Evaluation

**Files in this Folder**
- Elevvo_Task_3_Forest_Cover_Type_Classification.ipynb — Full notebook with preprocessing, modeling, and evaluation
- elevvo_task_3_forest_cover_type_classification.py
- covtype.csv — Covertype dataset used for training

**How to Run**

- Install required libraries:
pip install pandas scikit-learn xgboost matplotlib seaborn

- Open the notebook:
jupyter notebook Elevvo_Task_3_Forest_Cover_Type_Classification.ipynb

- Run all cells to reproduce the classification results.

**Model Summary**

This task uses tree-based classifiers (e.g., Random Forest, XGBoost) to predict forest cover type.
Performance is evaluated using classification metrics and insights from feature importance and confusion matrices.

**Credits**

Completed as part of the Elevvo Pathways Machine Learning Internship.
