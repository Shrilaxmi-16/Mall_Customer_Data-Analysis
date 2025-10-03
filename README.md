# Customer Segmentation using K-Means Clustering

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white) 
![Pandas](https://img.shields.io/badge/Pandas-1.5-brightgreen) 
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-purple)

## Project Overview
This project applies K-Means Clustering on the Mall Customers dataset to segment customers based on Age, Annual Income, and Spending Score. The goal is to uncover distinct customer groups to enable data-driven targeted marketing strategies. Visualizations and clustering evaluation methods are used to interpret and validate the results.

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

K-Means clustering effectively segmented mall customers into five distinct groups based on Age, Annual Income, and Spending Score. The analysis uncovered meaningful patterns, enabling targeted marketing strategies for each group. This demonstrates the power of unsupervised learning in deriving actionable business insights from customer data.

## Author
Shrilaxmi Gidd

Email: shrilaxmigidd16@gmail.com

Date: 03-10-2025
