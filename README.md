# Customer_Segmentation
This repo contains a notebook which clusters customes based on their characteristics<br>
The notebook is written in Python 3 and performs the following functions:
1. Data Cleaning: It tries to make the data fit for clustering. It first removes columns with lagre amount of missing data, then it tries to exclude tuples who do not contribute a lot of information and then it fills the missing data in each column with the most frequently occuring value for that column.
2. Dimensionality Reduction: Analysis using PCA is performed and the appropriate number of components are selected such that most of the variance is retained and then the new dataset is produced with the new features.
3. K-Means Clustering: The customers are then clustered using k-means and the optimal value of k is selected using the elbow curve
   
