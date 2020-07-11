# Cryptocurrencies
Supervised machine learning exercise

## Overview:
This project will take a look at the cryptocurrencies that are available and see how they can be grouped together

## Project description:
- Preprocess the data by removing uneccesary columns and rows. 
    - Remove all cryptocurrencies that aren’t trading.
    - Remove all cryptocurrencies that don’t have an algorithm defined.
    - Remove the IsTrading column.
    - Remove all cryptocurrencies with at least one null value.
    - Remove all cryptocurrencies without coins mined.
    - Store the names of all cryptocurrencies on a DataFramed named coins_name, and use the crypto_df.index as the index for this new DataFrame.
    - Remove the CoinName column.
- Convert text columns into integers with get_dummies.
- Scale the data with StandardScaler
- Reduce the data to 3 columns using PCA.
- Cluster the data using K-means.
    - Create an elbow curve to find the K value
    - Create a cluster dataframe
- Visualize the data
    - 3D scatter plot to show clusters
    - Data table to show current tradable cryptocurrencies
    - Scatter plot to show the relationship of total coins mined versus supply.