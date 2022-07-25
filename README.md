# Cryptocurrencies

# Overview of the analysis

You understand what unsupervised learning is used for, how to process data, how to cluster, how to reduce your dimensions, and how to reduce the principal components using PCA. It’s time to put all these skills to use by creating an analysis for your clients who are preparing to get into the cryptocurrency market.


# Resources

Python, Visual Studio Code, Anaconda, Jupyter Notebook and Pandas.


# Results/Deliverables

The following steps would be followed for this analysis:

### Deliverable 1: Preprocessing the Data for PCA

Using your knowledge of Pandas, you’ll preprocess the dataset in order to perform PCA in Deliverable 2.
 
 
 
 ![image](https://user-images.githubusercontent.com/96086671/180847574-6ddd681b-6227-4089-9582-175495e99160.png)



### Deliverable 2: Reducing Data Dimensions Using PCA

Using your knowledge of how to apply the Principal Component Analysis (PCA) algorithm, you’ll reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.



![image](https://user-images.githubusercontent.com/96086671/180847707-fafd1c78-5925-446e-bbe4-776e04b243ff.png)

 
### Deliverable 3: Clustering Cryptocurrencies Using K-means

Using your knowledge of the K-means algorithm, you’ll create an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. Then, you’ll run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.




![image](https://user-images.githubusercontent.com/96086671/180847849-d586899a-4555-439f-bfdd-d36ed317e9a1.png)


### Deliverable 4: Visualizing Cryptocurrencies Results


Using your knowledge of creating scatter plots with Plotly Express and hvplot, you’ll visualize the distinct groups that correspond to the three principal components you created in Deliverable 2, then you’ll create a table with all the currently tradable cryptocurrencies using the hvplot.table() function.


Create a table with tradable cryptocurrencies using the hvplot.table() function.




![image](https://user-images.githubusercontent.com/96086671/180848020-472268da-b6a4-4193-81b8-eb0e24a36474.png)

 
Create a new DataFrame using the clustered_df DataFrame index that contains the scaled data you created in Step 5.
 
 
 
 
![image](https://user-images.githubusercontent.com/96086671/180848109-0f661a05-06d4-4488-bfc2-949af1718cd6.png)

Create an hvplot scatter plot with x="TotalCoinsMined", y="TotalCoinSupply", and by="Class", and have it show the CoinName when you hover over the the data point.
 


![image](https://user-images.githubusercontent.com/96086671/180848233-b8fe3f74-bea7-469a-9222-c26c8e61e09b.png)





![image](https://user-images.githubusercontent.com/96086671/180848285-c9d06a32-8ac9-4197-9b41-71dad0af2f24.png)


# Summary

We provided the client with a list of cryptocurrencies being traded and classified them into 4 clusters. We also identified the classification of 532 cryptocurrencies based on similarities of their features.

