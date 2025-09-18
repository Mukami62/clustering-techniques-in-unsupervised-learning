**Customer Segmentation (Mall & Online Retail Datasets)**

This repository explores customer data from both a mall customers dataset and an online retail dataset using unsupervised learning techniques. The project applies data cleaning, exploratory data analysis, feature engineering, dimensionality reduction (PCA & t-SNE), and clustering to identify patterns and segment customers.

***Project Overview***

Loaded datasets into Pandas DataFrames and performed basic EDA: shape, column types, missing values, summary statistics, and unique value counts.

Converted numeric columns  into bins or categories for group analysis.

Detected and handled unrealistic values and removed duplicates.

Applied data cleaning and feature scaling to prepare the datasets for analysis.

Conducted aggregation and feature engineering: computed averages, ratios, flagged high-value customers, and created pivot tables.

Visualized key variables using histograms, bar charts, scatter plots, boxplots, and correlation heatmaps.

Applied PCA to standardized features (income, spending) to reduce dimensionality and analyze explained variance.

Plotted 2D PCA components colored by categories.

Applied t-SNE for non-linear dimensionality reduction and compared cluster separations with PCA.

Performed K-Means clustering with k=2…10, using the elbow method and silhouette scores to identify the optimal k.

Applied hierarchical clustering and visualized dendrograms to compare with K-Means results.

Profiled clusters by average age, income, spending score, and other features.

Checked cluster sizes, consistency across random states, and exported the final dataset with cluster labels.

***Methods Implemented***

Exploratory Data Analysis (EDA) for numeric and categorical variables.

Data cleaning: missing value handling, filtering, feature scaling, duplicates removal.

Feature Engineering & Aggregation: ratios, categorization, pivot tables.

Dimensionality Reduction: PCA and t-SNE.

Clustering: K-Means and Agglomerative/Hierarchical clustering.

Evaluation: Elbow method, silhouette score, cluster profiling.

***Results & Insights***

Customer segmentation revealed distinct groups based on income, spending, and age.

PCA and t-SNE highlighted clearer clusters than raw features alone.

High-value customers and age groups were successfully identified for targeted marketing insights.

Cluster visualizations allowed easy comparison between K-Means and hierarchical clustering.

Future Work

Explore additional features (e.g., online purchase frequency, product categories).

Experiment with other clustering methods such as DBSCAN or Gaussian Mixture Models.

Build an interactive dashboard for dynamic customer segmentation and business insights.
