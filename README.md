# 📊 Clustering Analysis and Association Rule Mining

This project is a Machine Learning lab task that performs an end-to-end analysis of multiple unsupervised learning techniques. It includes dimensionality reduction using **PCA**, application of **clustering algorithms** (K-Means, Hierarchical Clustering, DBSCAN), and **association rule mining** using the Apriori algorithm.

## 🎯 Objectives
- Apply **Principal Component Analysis (PCA)** before clustering to reduce feature space while preserving variance.
- Analyze and compare:
  - K-Means Clustering
  - Hierarchical Clustering (Agglomerative)
  - DBSCAN
- Perform **Association Rule Mining** on transactional data using the **Apriori algorithm**.

---

## 🔬 Methods Used
### 🧪 PCA for Feature Reduction
- Standardize features
- Plot cumulative explained variance
- Retain components that explain ~80–90% of the variance

### 📌 Clustering Algorithms
####  K-Means
- Use **Elbow Method** to determine optimal `K`
- Visualize clusters post-PCA

####  Hierarchical Clustering
- Use **Dendrograms** to understand cluster formation

####  DBSCAN
- Density-based clustering
- Identifies noise and arbitrarily shaped clusters

### 🛍️ Association Rule Mining
- Use **Apriori Algorithm** to extract strong association rules.

---

## 📈 Visualizations
The notebook includes:

-Correlation heatmaps
-PCA component plots
-Cluster visualizations (scatter plots, dendrograms)
-Rule mining tables (support, lift)
