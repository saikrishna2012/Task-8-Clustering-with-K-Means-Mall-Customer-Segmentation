# Task 8: Clustering with K-Means – Mall Customer Segmentation

## Objective
This task focuses on unsupervised learning using the K-Means clustering algorithm. The goal is to segment customers based on annual income and spending score and evaluate the clustering performance.

## Dataset
- Source: [Mall Customer Segmentation Dataset – Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- A preprocessed version was loaded directly via a public link.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## What Was Done
- Loaded customer data and selected relevant features
- Scaled the features using `StandardScaler`
- Applied the Elbow Method to determine optimal number of clusters
- Performed clustering using KMeans with k=5
- Visualized the clusters with color coding
- Evaluated cluster quality using the Silhouette Score

## Output
- `kmeans_customer_segmentation.ipynb` – notebook with code, plots, and silhouette score
- Visual interpretation of customer clusters based on behavior
