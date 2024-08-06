# Overview
This project involves analyzing a dataset of Amazon's top 50 bestselling books from 2009 to 2019. The dataset includes various attributes such as book name, author, user rating, reviews, price, and genre (fiction/non-fiction). The analysis covers statistical summaries, correlations, and clustering to uncover insights and segment the data.

Data Description
The dataset contains the following variables:

Name: Book title
Author: Author of the book
User Rating: Average user rating (1-5)
Reviews: Number of reviews
Price: Book price
Year: Year of publication
Genre: Literary genre (fiction/non-fiction)
Analysis
Statistical Analysis

Data Overview:
df.info()
df.describe()

Descriptive Statistics:
  Mean, median, variance, and standard deviation for price, reviews, and user ratings.
  Correlation analysis between user ratings, reviews, and price.

Correlation:
  Calculate Pearson, Spearman, and Kendall correlations for selected variables.

Graphical Analysis
Boxplot:
  Analyze user ratings by genre.
Heatmap:
  Visualize correlations between variables.
Scatterplot:
  Explore the relationship between reviews and price.

Clustering
Preprocessing:
  Normalize data and prepare for clustering.
K-Means Clustering:
  Determine the optimal number of clusters using the elbow method and silhouette score.
  Perform clustering and visualize results.
Cluster Analysis:
  Analyze and describe the characteristics of each cluster.

# Conclusion
  Key Findings: Summarize insights from statistical analysis and clustering.
  Cluster Characteristics: Describe each segment based on the cluster analysis.

# Requirements
Libraries: Ensure the following libraries are installed:
  matplotlib
  seaborn
  numpy
  pandas
  scipy
  scikit-learn
  plotly

# Getting Started
Upload the dataset to your environment.
Run the provided Python script to perform the analysis and clustering.
Review the generated plots and clustering results.
