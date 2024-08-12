# 19-Unsupervised-Learning

This repo demonstrates the use of unsupervised learning (SciKitLearn) to perform an analysis of cyptocurrency data. The price changes of cryptocurrencies were analyzed over various time intervals using K-means clustering. First, data was normalized using StandardScaler, and an elbow chart was produced to determine the appropriate number of clusters (k) for the data set. The data was then clustered using K-means. This can be used to identify groups of cryptocurrencies with similar price change behavior patterns, which can be used to inform investments and pick out outliers.

Then a PCA was performed with 3 principle components, which accounted for 88.9% of the original variance. The elbow chart and K-means clustering were then repeated using the PCA-transformed data. The value of k remained at 4, although the inflection point in the elbow chart was more defined. Likewise, the clusters dervied from the PCA values were tighter and more cleanly separated, reflecting the reduced dimensionality from the original data.
