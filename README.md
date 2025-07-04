Mall Customer Segmentation using K-Means Clustering

This project applies K-Means Clustering and PCA (Principal Component Analysis) to segment mall customers based on their demographics and purchasing behavior. The goal is to identify distinct groups of customers for targeted marketing strategies.

Dataset

* Gender
* Age
* Annual Income (k\$)
* Spending Score (1–100)

Key Steps

1. Load and Explore the Dataset

* Handled basic preprocessing and feature scaling.
* Categorical gender values encoded using pd.get_dummies().
* Standardized features using StandardScaler.

2. Visualize with PCA

* Reduced high-dimensional data into 2 principal components for easy visualization.
* Used seaborn to plot a gender-colored scatterplot of the data.

3. Apply K-Means Clustering

* Fit a KMeans model with an initial assumption of K=5 clusters.
* Visualized the clusters in PCA-reduced space with clear color-coded groupings.

4. Optimal Cluster Selection: Elbow Method

* Applied the Elbow Method to determine the ideal number of clusters (K).
* Plotted inertia values across K = 1 to 10 to find the “elbow point”.

5. Final Visualization

* Plotted the final clusters with color-coding using PCA components for interpretation.

Tech Stack

* Python, Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn (PCA, KMeans)

Outcome

Using unsupervised learning, customer segments were identified visually and analytically. This segmentation can aid businesses in creating tailored marketing strategies based on behavioral clusters.
