# Wholesale Customer Segmentation Project

### Overview
This project uses unsupervised learning to group wholesale customers by their yearly spending in different product categories. The repository contains the process of data cleaning to detailed customer segmentation, using techniques like PCA and clustering algorithms to derive insights.

### Dataset 
The 'Wholesale_Data.csv' dataset encompasses a snapshot of the client base of a wholesale distributor. It contains six product categories that tracks the clients' spendings: Fresh, Milk, Grocery, Frozen, Detergents_Paper, and Delicatessen.

### Navigating the Project
In the Data Preprocessing stage, we standardized the data and removed the outliers to prepare for analysis. During the Exploratory Data Analysis phase, we analyzed the distributions and relationships between features, identifying skewness in various categories. For Dimensionality Reduction with PCA, Principal Component Analysis (PCA) was used to simplify the dataset to its most significant components, capturing the core of customer spending patterns. In Clustering Dynamics, we applied KMeans and Hierarchical clustering to divide our customer base into clear segments. Finally, we interpreted our analysis into distinct customer profiles and highlight their spending patterns.

### Summary of findings
Our EDA highlighted skewed distributions hinting at diverse purchasing amounts. The PCA underscored that over 90% of customer behavior variance was encapsulated within the first four principal components, with the primary component being significantly loaded on staple goods and the second on perishables. The clustering process carved out 4 principal segments from our customer base: smaller markets with higher spending on fresh products, convenience stores with diverse grocery and household goods selections, restaurants focusing on fresh and frozen ingredients, and establishments with a moderate, balanced expenditure across most categories except frozen goods.

