# K-Means Garden

Plant a few point clouds, then watch cluster centres find their way home one iteration at a time.



## Try it

Step through several iterations, then change k and run again. Notice how the cluster count changes both assignments and squared-distance loss.

## How it works

This is Lloyd’s k-means algorithm with Euclidean distance: nearest-centre assignment, cluster means, then reassignment. Empty clusters retain their existing centre. Initialization uses random dataset points, so different runs can settle differently.


