

---
## Project Outcomes
- Unsupervised Learning: perform unsupervised learning techniques on a wholesale data dataset. The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.
### Duration:
Approximately 1 hour and 40 minutes
### Project Description:
In this project, we will apply unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project will involve the following tasks:

-	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
-	Unsupervised learning: We will use the Wholesale Data dataset to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together. We will determine the optimal number of clusters and communicate the insights gained through data visualization.

The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

# machine_learning_project-unsupervised-learning
# Unsupervised Learning: Wholesale Customer Segmentation

This project applies unsupervised learning techniques to identify distinct customer segments based on their product purchasing behavior. Using the **Wholesale Customers Dataset**, the analysis includes exploratory data analysis (EDA), **KMeans Clustering**, **Hierarchical Clustering**, and **Principal Component Analysis (PCA)** for dimensionality reduction and visualization.

---

## Objectives

- Explore and clean the wholesale customer dataset
- Apply clustering techniques (KMeans and Hierarchical) to identify customer segments
- Reduce data dimensionality with PCA to simplify and visualize customer behavior
- Gain business insights by interpreting customer segments based on product category spending

---

## Techniques Used

- **Data Preprocessing**: Log transformation and feature scaling
- **EDA**: Distribution analysis, boxplots, correlation heatmap
- **KMeans Clustering**: Elbow method and silhouette score to select optimal `k`
- **Hierarchical Clustering**: Dendrogram and distance-based cut for group identification
- **PCA**: Dimensionality reduction and cluster visualization

---

## Key Findings

- **Customer segmentation revealed 2 distinct groups**, as identified through both KMeans and Hierarchical Clustering. While KMeans suggested 3 clusters as optimal, adjusting the dendrogram cut height to 12 resulted in 2 broader and more meaningful customer segments. These groups primarily differ in their purchasing volume across key product categories like Grocery, Milk, and Detergents_Paper.

- **Detergents_Paper, Grocery, and Milk were highly correlated**, indicating a common buying behavior among general merchandise customers. These features had the highest influence in the first principal component (PC1), showing they play a central role in explaining customer differences.

- **Log transformation was essential** to reduce the impact of skewed data and extreme outliers. This helped clustering algorithms and PCA focus on meaningful patterns instead of being dominated by large numeric values.

- **PCA showed that the first two principal components captured most of the variance** in the dataset, allowing customer behavior to be visualized in 2D. This made it easier to interpret clusters and uncover differences between customer groups.