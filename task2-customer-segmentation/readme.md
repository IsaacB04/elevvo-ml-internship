**Task 2: Customer Segmentation**

This task focuses on using unsupervised learning techniques to cluster customers based on their income and spending behavior. The objective is to identify meaningful customer groups that can support targeted marketing strategies.

**Description**

Dataset used: Mall Customer Dataset (Kaggle)
Goal: Segment customers into meaningful groups based on behavior

Main steps:
- Load and clean customer data
- Scale features using standardization
- Explore data visually using scatter plots and distributions
- Apply K-Means clustering
- Determine the optimal number of clusters using the Elbow Method
- Visualize final clusters in 2D

**🛠️ Tools & Libraries**

- Python
- Pandas
- Matplotlib
- Scikit-learn

**Covered Topics**

- Clustering
- Unsupervised Learning
- Feature Scaling
- K-Means Algorithm

**Files in this Folder**

- Elevvo_Task_2_customer_segmentation.ipynb — Complete notebook with clustering workflow
- Mall_Customers.csv — Dataset used for customer segmentation
- elevvo_Task_2_customer_segmentation.py

**How to Run**

- Install required libraries:
pip install pandas matplotlib scikit-learn

- Open the notebook:
jupyter notebook Elevvo_Task_2_customer_segmentation.ipynb

- Run all cells to generate the clusters and visualizations.

**Model Summary**

This task implements K-Means clustering to group customers based on annual income and spending score. Visualization helps interpret the generated clusters and understand customer behavior patterns.

**Credits**

Completed as part of the Elevvo Pathways Machine Learning Internship.
