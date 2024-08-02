# Final_Project
#Final Project: Wine Clustering

## Project Overview

The goal of this project is to perform clustering on the Wine dataset to group wines into distinct clusters based on their chemical properties. We use the K-means clustering algorithm to achieve this.

## Steps

### Step 1: Gather Data

Used the Wine dataset from the UCI Machine Learning Repository. The dataset contains chemical analysis results of wines grown in the same region in Italy but derived from three different cultivars.

### Step 2: Identify an Unsupervised Learning Problem

Chosed clustering as our unsupervised learning problem to group wines based on their chemical properties.

### Step 3: Exploratory Data Analysis (EDA)

- **Data Inspection and Visualization**: We performed initial data inspection and visualization using box plots and correlation heatmaps.
- **Data Cleaning**: We checked for missing values and encoded categorical data (if any).
- **Feature Scaling**: We standardized the data to ensure all features contribute equally to the clustering process.

### Step 4: Perform Analysis Using Unsupervised Learning Models

- **K-means Clustering**: We used the K-means clustering algorithm to group the wines into clusters. The optimal number of clusters was determined using the elbow method.
- **Visualization**: We visualized the resulting clusters based on key features (Alcohol and Malic acid).

## Results

The K-means clustering algorithm grouped the wines into three distinct clusters. Each cluster represents wines with similar chemical properties. The clusters were visualized in a scatter plot.

### Cluster Descriptions

- **Cluster 0 (Purple)**: Wines with lower alcohol content (11.0 - 12.5) and variable malic acid content.
- **Cluster 1 (Teal)**: Wines with a broader range of alcohol (12.0 - 14.0) and malic acid content.
- **Cluster 2 (Yellow)**: Wines with higher alcohol content (13.0 - 15.0) and lower malic acid content.

## Conclusion

The project successfully applied K-means clustering to the Wine dataset, grouping wines into distinct clusters based on their chemical properties. This analysis provides insights into the characteristics of different wine types and can be a basis for further investigation.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Acknowledgments

- UCI Machine Learning Repository for the Wine dataset.
- Scikit-learn for the machine learning tools.
- Dataset reference - https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data
