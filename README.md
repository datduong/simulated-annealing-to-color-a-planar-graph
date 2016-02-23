# simulated annealing to color a planar graph

A planar graph is a graph where 2 edges that cross, can be drawn so that they don’t cross.

The coloring criteria requires that any neighboring nodes must have distinct colors. Neighboring nodes are nodes that have an edge between them. 

It has been proven that this coloring scheme exists (with at least 4 colors) for any planar graph. This code provides an example of this case, and conducts a simulated annealing optimization procedure to find the coloring scheme. 

In general, such coloring scheme may not exist for any arbitrary graph. However, this code provides a backbone such that you can attain a near optimal coloring scheme for any graph (easy modification to the code is required).  

# library

You may need to install igraph. 

install.packages(‘igraph’)
