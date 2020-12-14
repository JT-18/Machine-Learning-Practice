## Clustering Algorithms
<p>Clustering algorithms come under the unsupervised kind of learning.In this type of learning we only provide data to the algorithm and the algorithm itself clusters or groups 
similar data points together using certain metrics.</p>

<h4>k-means clustering</h4>
<ol>
<li>Initailize k with number of classes (I have started with 1)</li>
<li>Choose k random centroids initially</li>
<li>Form k clusters and add these k centroids to these clusters respectively.
<li>Iterate through the data set and calculate the distance from the centroids for each tuple </li>
<li>Place the tuple into the cluster who's centroid is closest to the tuple</li>
<li>Calculate the mean value of the cluster and update the centroid with this mean value </li>
<li>If the centriods in the previous iteration and current iterations are equal then stop the clustering algorithm for k no of classes</li>
<li>Calculate the varience of the clusteres</li>
<li>If the varience of previous iteration is less than the current iteration then stop the clustering algorithm</li>
</ol>
<b>Reference for k means Algorithm </b> <a href = "https://youtu.be/1XqG0kaJVHY">K means clustering video</a>
<h5>Instruction for running the code</h5>
<ul>
  <li>k is the number of classes in the dataset.If known beforehand one can directly initialize k with no of classes in the dataset.</li>


