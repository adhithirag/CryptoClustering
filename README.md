# CryptoClustering

## The purpose of this challenge is to use Python and unsupervised learning methodologies to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. 

### Preparing the Data
# Step 1: 
    - Using StandardScaler() to normalize the data
# Step 2:
    - Find the best value of k using the Original DataFrame (df_market_data)
    -Also I used the scaled dataframe to determine the best value of k (crypto_scaled_df)
# Step 3:
    -Cluster the cryptocurrencies with KMeans using the original dataframe and scaled data
    -I created 2 cluster charts of the cryptocurrencies with K-means using the scaled dataframe and using n_clusters =2 and n_clusters=4
# Step 4:
    -Optimize the clusters using Principal Component Analysis (PCA)

