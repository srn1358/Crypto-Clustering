# Crypto Clustering
I clustered cryptocurrencies by their performance in different time periods. I used K-Means method to do the clustering. Also, I tried to reduce the number of features of the dataset and repeat the clustering to see if it would improve the performance of the K-means method. 
I used hvplot to visualize the results.

## Installation Guide
```python
    import pandas as pd
    import hvplot.pandas
    from path import Path
    from sklearn.cluster import KMeans
    from sklearn.decomposition import PCA
    from sklearn.preprocessing import StandardScaler
```
