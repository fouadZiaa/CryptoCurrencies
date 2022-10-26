# CryptoCurrencies
Using unsupervised machine learning techniques to analyze cryptocurrency data.

## Project Overview
This project uses machine learning to identify which cryptocurrencies are on the trading market and helps in understanding how cryptocurrencies should be grouped in classifications for developing an investment portfolio.

## Steps included in this project:

- Pre-Processing of Data: This step included in-depth data cleaning, such as removing null values and removing cryptocurrencies without coins mined. In addition, the encoding method "get_dummies()" was used for the text features and StandardScaler() was used to standardize and transform the data.
- Reducing data dimensions using PCA: In this step, a dataframe's dimensions was reduced to three principal components and a new dataframe was created.
- Clustering cryptocurrencies using K-means: During step, an elbow curve was created to find the best value for the clustering groups and a K-means algorithm was used to predict the K clusters for the cryptocurrencies’ data.
![Elbow Curve](https://github.com/fouadZiaa/CryptoCurrencies/blob/ae690de3b62ac2fdb6cfff0e30c0c5a4a7d3a990/Resources/Elbow_Curve.png)
- Visualizing results: In this final step, three types of figures were used: a 3D scatter plot to visualize the three PCAs, a hvplot.table to visualize all the current tradable cryptocurrencies, and a 2D scatter plot to visualize "Total Coins Mined" vs. "Total Coin Supply" by coin name and clusters.
![Scatter Plot](https://github.com/fouadZiaa/CryptoCurrencies/blob/f229b7816d0dc1fad2a75e1e9f6eec313c40930f/Resources/Scatter_plot.png)
![Mined vs Supply](https://github.com/fouadZiaa/CryptoCurrencies/blob/3009cae379648be6be50220d20a884b7f0bfbab5/Resources/supply_v_mined.png)
