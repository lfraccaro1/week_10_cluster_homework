# Unit 10 Assignment - Unsupervised Learning
## Summary
In this assignment, I cover new skills learned in the unsupervised learning module to cluster cryptocurrencies by their performance in different time periods (24h and 1W). 

First,  I use the elbow method to find the best value for k, and plot a line chart to identify the optimal value. I then run the K-means model to predict the cluster to group the cryptocurrencies and create a scatter plot with the results. 

Next, I ran a principal component analysis using 3 components. I obtained the explained variance to determine how much information I can attribute to each principal component and then created a new dataframe with the PCA data. I then ran the elbow method algorithm again to find the value of k for the PCA data, plotting a line chart to identify this. Following this, I created another k-means model with the PCA data, and created another plot from the results. 

Finally, I created composite plots to view the elbow curve plots and the cluster plots for the two different methods side by side, so we could easily compare the results. 