# Credit Card Customer Segmentation using K-Means Clustering

This project demonstrates customer segmentation using K-Means clustering on a credit card dataset. 

## Dataset

The dataset used is "CC GENERAL.csv", which contains information about credit card customers, including their balance, purchases, credit limit, and other financial attributes.

## Steps

1. **Data Loading and Preprocessing:**
   - Import necessary libraries (NumPy, Pandas, Matplotlib).
   - Load the dataset using Pandas.
   - Explore the data using `head()`, `shape`, and `info()`.
   - Handle missing values by dropping rows with missing data using `dropna()`.

2. **Exploratory Data Analysis (EDA):**
   - Visualize the distribution of key features like 'BALANCE', 'PURCHASES', and 'CREDIT_LIMIT' using histograms.
   - Calculate the correlation between these features using `corr()`.

3. **K-Means Clustering:**
   - Import the `KMeans` class from `sklearn.cluster`.
   - Select the features for clustering ('BALANCE', 'PURCHASES', 'CREDIT_LIMIT').
   - Apply K-Means clustering with a specified number of clusters (e.g., 5).
   - Assign cluster labels to the data points using `fit_predict()`.
   - Replace cluster labels with custom names for better understanding.

4. **Cluster Visualization:**
   - Import `Axes3D` from `mpl_toolkits.mplot3d` for 3D visualization.
   - Create a 3D scatter plot to visualize the clusters based on the selected features.
   - Label the axes and add a title to the plot.
   - Display the plot using `show()`.

## Insights

- The project aims to segment credit card customers into distinct groups based on their financial behavior.
- The 3D cluster visualization helps understand the relationships between the selected features and how customers are grouped.
- Further analysis can be performed to understand the characteristics of each cluster and tailor marketing strategies accordingly.
