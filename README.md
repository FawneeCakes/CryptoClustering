# CryptoClustering

Note: The graphs are not showing in Github so I added png files of all 7 graphs to show they did populate in Colab when I was coding.

Resources: In class work and review of class solutions; Stack Overview: How to make the Holoviews show graph on Google Colaboratory notebook?, Future warning skLearn; Youtube: Holoviews in Colab, Python Machine Learning Tutorial (Data Science)

In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Before You Begin
Create a new repository for this project called CryptoClustering. Do not add this homework to an existing repository.

Clone the new repository to your computer.

Push your changes to GitHub.

Answer the following question:

**Question: What is the best value for k? **
**Answer: The best value for k is 4, this means 4 is the optimal number of clusters. **

Question: What is the total explained variance of the three principal components?
Answer: About 88% of the total variance is condensed into the 3 PCA variables. 0.8844285111826465.

Question: What is the best value for k when using the PCA data?
Answer: 4

Question: Does it differ from the best k value found using the original data?
Answer: No, the k value is same as the original data, however it does have a smaller inertia value of 43, while the original had a inertia value of 79.

Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?
Answer: From the analysis, it appears that employing fewer features (specifically, PCA-transformed data) for clustering cryptocurrency data using K-Means has yielded favorable outcomes. The resulting clusters are more distinct and separable compared to using the original data. The reduction in feature dimensions via PCA likely accentuated essential patterns while mitigating noise, ultimately enhancing the accuracy and meaningfulness of the clustering results
