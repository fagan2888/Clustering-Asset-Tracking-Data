# Clustering-Asset-Tracking-Data

![Full vs. Reduced Data](https://github.com/paulhgraham/Clustering-Asset-Tracking-Data/blob/master/Output/output_25_1.png)


Using location information, clustering analysis was attempted using Machine Learning with the below information and resources in order to cluster data together to create critical points for route optimization.


DBSCAN Density-Based Spatial Clustering of Applications with Noise. Finds core samples of high density and expands clusters from them. Good for data which contains clusters of similar density.

http://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html
http://scikit-learn.org/stable/modules/clustering.html
http://scikit-learn.org/stable/modules/clustering.html#dbscan

The silhouette coefficient evaluates how close a point is to the other points in its cluster in comparison with how close it is to the points in the next nearest cluster. A high silhouette coefficient indicates the points are well-clustered and a low value indicates an outlier.

http://scikit-learn.org/stable/modules/clustering.html#silhouette-coefficient
