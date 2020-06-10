# Accident-Hotspot-detection---DBSCAN-and-OPTICS-with-significance-testing

First step was to cluster the points using the Density based clustering algorithms clustering algorithm
which does not require any previous information of boundaries or shape of clusters. Besides this,
since the decision of declaring a cluster as a hotspot is crucial, considering the resources and
effort that is going in it , the possibility of chance clusters in the result needs to be eliminated.
Hence Significance testing of the clustering result is important.
To ensure only the significant clusters, we have applied the Montecarlo estimation algorithm,
implemented in python in order to analyze the data and determine a threshold value for the
minimum number of points in a cluster so as to exclude the chance/false positive results. The
results obtained are hence plotted on a map.
We use two popular density based algorithms in this project, DBSCAN and OPTICS, in order to
compare the results based on the V-Measure obtained by both of the algorithms on the given
data. We also study about the advantages and disadvantages in the implementation of one over
the other.
