# Module10 : Crypto Clustering

Cluster the performance of all the cryptocurrences provided in the .CSV file and plotting hvplots to compare the results.

## Plotting DataFrame Data:
![DataFrame_Data](https://user-images.githubusercontent.com/118318397/217381624-b5799476-7295-4b1f-86c3-dd2652f0bf54.PNG)

# Original data Analyzation using K-Means:

### Elbow Curve Using original data:

![ElbowCurve_OriginalData](https://user-images.githubusercontent.com/118318397/217382230-94de0da6-e460-433a-bc0c-785137edd4b1.PNG)

Question: What is the best value for k?

Answer: Based on elbow_original_plot, k=4. Inertia drops considerably as k>4. 


# Optimizing Clusters with Principal Component Analysis Data:

### Elbow curve using PCA data:

![ElbowCurve_PCAData](https://user-images.githubusercontent.com/118318397/217382634-f3182f28-0b2a-450d-a72b-61719a8b5266.PNG)


Question: What is the total explained variance of the three principal components?

Answer: The total explained variance of the three principal components is approximately 89%.

Question: What is the best value for k when using the PCA data?

Answer: Based on the elbow curve above, it looks like k=4 is still the best value using the PCA data.

Question: Does it differ from the best k value found using the original data?

Answer: The best value of k is the same across both, the PCA data and the orginal data. 

# Comparing Clusters using original data and PCA data

![CryptoClusters_PCAData](https://user-images.githubusercontent.com/118318397/217383596-bcf797e6-6ec7-4221-ad7d-e728b99b6f77.PNG)
![CryptoClusters_KMeans](https://user-images.githubusercontent.com/118318397/217383601-33805cc4-aff9-4bab-a470-525aa2bf3a83.PNG)


Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

Answer: After visually analyzing the cluster analysis results and using fewer features to cluster the data using K-Means, we can get a more condensed scatter plot. The data is grouped in customer segments. 
