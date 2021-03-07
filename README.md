# unsupervised_learning_crypto_investment
Using unsupervised learning to perform an analysis of various crypto prices

![K=4 Graph](/Pictures/Crypto_clusters.jpg)
![PCA DataFrame](/Pictures/crypto_pca.jpg)
# Usage
This project aims to group cryptocurrencies with similar price movements. In order to accomplish this, the data is read in from a csv file, then prepared with StandardScaler. Next, we use the KMeans algorithm to cluster the cryptocurrencies according to their price changes. After this, the elbow method is applied to find the best value for K. Then, the analysis is optimized with principal component analysis and plotted twice, once with K=4 and once with K=5.
# Technologies
The application is written in Jupyter lab
The following packages are used: Pandas, hvplot, pathlib, and sklearn (KMeans, PCA, and StandardScaler)
# Contributor
Billy Scolinos billyscolinos1@gmail.com