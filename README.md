# K-means-clustering
A specific case of the general k-means clustering algorithm to separate the points into groups of similar points with in a data set

An iterative algorithm which is a specific case of the very general  k -means clustering algorithm. The algorithm will require us to keep track of two clusters, each of which have a list of points and a center (which is another point, not necessarily one of the points we are clustering). After making an initial guess at the center of the two clusters,  C1  and  C2 , the steps proceed as follows.

1. Assign each point to  C1  or  C2  based on whether the point is closer to the center of  C1  or  C2.
2. Recalculate the center of  C1  and  C2  based on the contained points.

This algorithm will terminate in general when the assignments no longer change. here one cluster is initialized at (1, 0) and the other at (-1, 0).

The returned values are the two centers of the clusters ordered by greatest x value. Returned values are a list of numeric tuples  [(x1,y1),(x2,y2)]
