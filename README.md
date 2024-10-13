# CryptoClustering
module 19

# Overview of Analysis
Used unsupervised learning techniques to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.
 - **Prepare the data** using StandardScaler() from scikit-learn to normalize the data.
 - **Find the best value for k** using the elbow method.
 - **Create clusters with K-means** using the scaled dataframe.
 - **Optimize clusters with PCA**.
 - **Find the best values for k** using the elbow method for the PCA DataFrame.
 - **Create clusters with K-means** using the PCA DataFrame.
# Results
## Best Value for k
The best k value for both DataFrames, scaled and PCA, appeared to be 4, as seen in the below plots.
![elbow_plots](https://github.com/megan-oconnor/CryptoClustering/blob/main/Images/elbow_comparison.png)
</br>
In the plots below of the classified data, it appears that using fewer features creates more distinct clusters.
![cluster_plots](https://github.com/megan-oconnor/CryptoClustering/blob/main/Images/cluser_comparisons.png)

