# Density-based-Clustering
Clustering is a well-known task in data mining that focuses on identifying common patterns in large data sets. The task is to partition the data into different groups, called clusters, so that objects classified in the same cluster are more similar to each other than to those in different clusters. One of the most popular and powerful clustering methods is DBSCAN, which defines clusters as areas of higher density separated by lower density areas.

In this project, the efficiency and scalability of two DBSCAN methods using quadtree and boxgraph approach will be evaluated. Thus, the research question is how the quadtree and boxgraph approach scale with the number of points for data sets with little noise and when epsilon is set to correctly identify the clusters. 

To investigate the research question, four data sets with different experimental setup are generated. All of the data sets are created using the SkLearn library from Python. The sample size will be varied between 1000 and 20000 data points to measure the efficiency of the two DBSCAN algorithms. Besides, the standard deviation of the noise is set at small value to make sure that the data has little noise according to the research question.

For each data set, the quadtree and boxgraph DBSCAN methods will be used to cluster the data. The parameters for running the two clustering algorithms are set according to the data generated. The min points for clustering every data set is set to 4. For each algorithm, the time to initialize the data structure as query object and the clustering time will be measured.
