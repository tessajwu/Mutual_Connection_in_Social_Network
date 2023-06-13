# Mutual Connection in Social Network
Using BFS to find the distances between all of the vertices with their respective edges. After finding all the distances, average the distances to have one average distance for each vertex. With those average vertices, compare pairs of those vertices to find the average distance between and pairs as well as their common neighbors. Below is a graph created of my findings:

<img align="center" width="650" height="500" src=findings.png>

The graph shows that the higher the average distances (between pairs of vertices), the lower the common neighbors. That is, there is an inverse relationship between average distance and common neighbors between two vertices. This finding makes sense because if the two variables have a positive linear relationship, then that means the distance would be small as they have a lot of common neighbors. Not having common neighbors would require longer distances between vertices when traversing.
