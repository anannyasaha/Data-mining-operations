# Comparison between kmeans and DBSCAN
Data mining operations
Database :Compound.txt
 
Here we can see that the number of clusters which will give the most accurate results is 2. But here we see that 2 cluster is not enough to separate the clusters which are visible to us.
    
If we increase the cluster number more then we three, which is more accurate than the first clustering. But when the cluster number is 4 it divides one cluster in half instead of indentifying the top two clusters.

  
When the cluster number is 5 top two clusters are identified but bottom cluster is divided in half. For cluster number 6 the right cluster is divided in half as well.
   
In the graph we see that the change of distance is rapid at 0.75. So the EPS should be 0.75 for DBScan. And min sample points should be 4.
Database :Flame.txt
  
Number of appropriate cluster is 4. 
   
But after plotting we can see that there should be two clusters. The picture with two cluster doesn’t show the clusters clearly. For 3 clusters its still not clear. For 4 clusters it still makes more sense than first two.
   
For cluster 5 and 6 it doesn’t make sense.
  
With DBScan we see that there is a rapid change in distance at 0.85. So the EPS should be 0.85 and the minimum sample number is 4.
Database: Spiral Text
 
Here the elbow is not very clear. But I think at number of cluster 3 we can see a dent.
     
   
All these clusters doesn’t make sense to me. I think each stroke should have been a cluster instead of dividing the spiral in pieces like pies.
   
Here in the line graph we see that the distance rapidly changes around 0.9. So by putting EPS as 0.9 and min samples as 4 the DBScan will look like the right figure. This figure makes better sense than the Kmeans. Because the tightly located points are counted as clusters and lightly located points are made a different cluster.
Dataset: pathbased.txt
 
The elbow point is the point 2 for this graph. That means the number of cluster should be 2 for K means clustering to get the best result with it.

    
  
Among all these clusters the first picture with 2 cluster makes more sense which we anticipated from the SSE plot.

  
Here we can see a rapid change around 1.5. So the EPS is 1.5 and min sample is 4.
 
This cluster makes more sense than the Kmeans clustering. Here the tightly located middle portions are counted as separate clusters. But the outer ones are not one cluster they got divided into some more clusters.
