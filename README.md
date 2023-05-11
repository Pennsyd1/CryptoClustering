# CryptoClustering

First the crypto_market_data.csv is read into a dataframe using pandas then it is plotted on a line graph using hvplot.  From there the data is transformed using StandardScaler().  Then an elbow Curve is created after computed the inertia via k values and the transformed data.

It is determined that the best value for K is 4 so that is what is used to initialize the K-means. Then the K-means is used to predict  the clusters and plotted on a scatter plot.

Afterwards I repeated the process with principal component analysis model.
