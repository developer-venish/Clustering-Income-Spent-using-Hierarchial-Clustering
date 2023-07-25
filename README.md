# Clustering-Income-Spent-using-Hierarchial-Clustering
ML Python Project


![](https://github.com/developer-venish/Clustering-Income-Spent-using-Hierarchial-Clustering/blob/main/tree%20graph.png)

![](https://github.com/developer-venish/Clustering-Income-Spent-using-Hierarchial-Clustering/blob/main/clustering.png)


---------------------------------------------------------------------------------------

Note :- All the code in this project has been tested and run successfully in Google Colab. I encourage you to try running it in Colab for the best experience and to ensure smooth execution. Happy coding!

---------------------------------------------------------------------------------------

This code is an example of hierarchical clustering for analyzing income and spending patterns. Let's go through it step by step:

1. Importing Libraries: The necessary libraries, including pandas for data handling, matplotlib for visualization, and LabelEncoder for encoding categorical data, are imported.

2. Reading Data: The code uses the `files.upload()` method to upload the 'data.csv' file and reads the data into a pandas DataFrame called `dataset`.

3. Data Exploration: The code prints the shape, summary statistics, and the first five rows of the `dataset` to get an overview of the data.

4. Data Preprocessing: The 'Gender' column contains categorical data, and it is encoded using LabelEncoder to convert it into numerical values.

5. Dendrogram Visualization: The code uses hierarchical clustering to create a dendrogram tree graph. The dendrogram shows the hierarchical relationships between data points, and it helps in choosing the appropriate number of clusters for clustering.

6. Hierarchical Clustering: The AgglomerativeClustering algorithm is used to perform hierarchical clustering with 5 clusters (`n_clusters = 5`). The clusters are based on the 'Income' and 'Spent' columns of the dataset.

7. Scatter Plot Visualization: Finally, the clustered data is visualized in a scatter plot. Each cluster is represented by a different color, and the 'Income' is plotted on the x-axis, and 'Spent' is plotted on the y-axis.

Overall, this code demonstrates how hierarchical clustering can be used to segment customers based on their income and spending behavior. The dendrogram is used to help decide the appropriate number of clusters, and the scatter plot visualizes the resulting clusters.
