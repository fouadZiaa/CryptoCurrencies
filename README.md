# CryptoCurrencies
Using unsupervised machine learning techniques to analyze cryptocurrency data.

## Project Overview
This project uses machine learning to identify which cryptocurrencies are on the trading market and helps in understanding how cryptocurrencies should be grouped in classifications for developing an investment portfolio.

## Steps included in this project:

- Pre-Processing of Data: Intensive data cleaning, such as removing null values and removing cryptocurrencies without coins mined. For text features  the encoding method "get_dummies()" was used, and StandardScaler() was used to standardize and transform the data.

- Reducing data dimensions using PCA: The dimensions of dataframe were reduced down to three principal components and a new dataframe was created.

- Clustering cryptocurrencies using K-means: Using an elbow curve to find the best value for the clustering groups and K-means algorithm to predict the K clusters for the cryptocurrencies’ data.
![Elbow Curve](https://github.com/fouadZiaa/CryptoCurrencies/blob/ae690de3b62ac2fdb6cfff0e30c0c5a4a7d3a990/Resources/Elbow_Curve.png)

- Visualizing results: 3D scatter plot to visualize the three PCAs, an 'hvplot.table' to visualize all the current tradeable cryptocurrencies, and a 2D scatter plot to visualize "Total Coins Mined" vs. "Total Coin Supply" by coin name and clusters.
![Scatter Plot](https://github.com/fouadZiaa/CryptoCurrencies/blob/f229b7816d0dc1fad2a75e1e9f6eec313c40930f/Resources/Scatter_plot.png)

![Mined vs Supply](https://github.com/fouadZiaa/CryptoCurrencies/blob/3009cae379648be6be50220d20a884b7f0bfbab5/Resources/supply_v_mined.png)
