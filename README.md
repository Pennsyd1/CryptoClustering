# CryptoClustering

First the crypto_market_data.csv is read into a dataframe using pandas then it is plotted on a line graph using hvplot.  From there the data is transformed using StandardScaler().  Then an elbow Curve is created after computed the inertia via k values and the transformed data.

It is determined that the best value for K is 4 so that is what is used to initialize the K-means. Then the K-means is used to predict  the clusters and plotted on a scatter plot.

Afterwards I repeated the process with principal component analysis model.

<img width="518" alt="image" src="https://github.com/Pennsyd1/CryptoClustering/assets/118862894/e103ef10-34b6-4981-8ef7-393b4b880893">
<img width="548" alt="image" src="https://github.com/Pennsyd1/CryptoClustering/assets/118862894/c0455a5e-7a2a-45c7-8fc8-7dbaa0229545">
<img width="537" alt="image" src="https://github.com/Pennsyd1/CryptoClustering/assets/118862894/8e1d0fb1-c378-44af-b50b-89853003009d">
<img width="496" alt="image" src="https://github.com/Pennsyd1/CryptoClustering/assets/118862894/f6ede372-9df5-4ebc-9a28-c56b4a2f3bf0">

