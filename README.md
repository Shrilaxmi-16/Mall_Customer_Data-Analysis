# Customer Segmentation using K-Means Clustering

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white) 
![Pandas](https://img.shields.io/badge/Pandas-1.5-brightgreen) 
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-purple)

## Project Overview
This project applies K-Means Clustering to the Mall Customers dataset to identify distinct groups of customers based on Age, Annual Income, and Spending Score.
The goal is to segment customers for targeted marketing strategies.

## Mall Customer Dataset 

**Dataset Source:** [Mall Customer Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
Mall_Customers.csv contains details of 200 customers, including:

- CustomerID: Unique ID for each customer
- Gender: Male/Female
- Age: Age of the customer
- Annual Income (k$): Customer's yearly income in $1000
- Spending Score (1-100): Score assigned by the mall based on customer behavior

## Analysis Workflow

1. Data Loading & Preprocessing
   - Handled dataset, checked missing values, descriptive stats.
   - Standardized features for clustering.

2. Exploratory Data Analysis (EDA)
   - Feature distributions and correlations.
   - Scatter plots to visualize relationships between age, income, and spending.

3. Dimensionality Reduction
   - Applied PCA for 2D visualization.

4. K-Means Clustering
   - Used Elbow Method to determine the optimal number of clusters.
   - Fitted K-Means and assigned cluster labels.

5. Cluster Evaluation
  - Evaluated using Silhouette Score.

6. Visualizations

   - 2D and 3D scatter plots of clusters.
   - Distribution plots by cluster.
   - Heatmap of correlations.
   - Parallel coordinates for multivariate cluster patterns.
   - Cluster size distribution.

## Results
- Optimal number of clusters (K=5) identified via Elbow Method.
- Clusters show distinct groups such as:
- Low income, low spenders
- High income, high spenders
- Average income, moderate spenders
- Young high spenders

Older low spenders
## Tools & Libraries
- **Python**
- **Pandas** – Data manipulation and preprocessing
- **NumPy** – Numerical computations
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive coding environment

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Shrilaxmi-16/Mall_Customer_Data-Analysis.git

## Conclusion

This project demonstrates how a Logestic Regression and Random Forest Classifier can be effectively used to perform feature importance analysis. Through exploratory data analysis, strong patterns and correlations between features were identified, and categorical variables were encoded for modeling. The Random Forest model ranked features based on their influence on predictions, providing valuable insights for feature selection and dimensionality reduction. Such analysis not only improves model performance but also enhances interpretability, enabling data-driven decision-making. This approach can be applied to a wide range of datasets to uncover the most impactful features and streamline predictive modeling workflows.

## Author
Shrilaxmi Gidd

Email: shrilaxmigidd16@gmail.com

Date: 03-10-2025
