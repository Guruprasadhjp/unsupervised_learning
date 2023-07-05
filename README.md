# unsupervised_learning
Clustering and Dimensionality Reduction 

## Part 1
Load data from digitData2.csv file. The last column of each file presents the label and the rest of the columns are features.

	1. Selecting the optimum k value using Silhouette Coefficient and plot the optimum k values.
	
	2. Create clusters using Kmeans and Kmeans++ algorithms with optimal k value found in the previous problem. 
       Report performances using appropriate evaluation metrics. Compare the results.
	   
	3. Now repeat clustering using Kmeans for 50 times and report the average performance. 
       Again,compare the results that you have obtained in Q3 using Kmeans++ and explain the difference (if any).
	
 	4. Apply DBSCAN on this dataset (digitData2.csv) and find the optimum "eps" and "min_samples" value. 
       Is the number of clusters the same as the cluster found in Q2? 
       Explain the similarity or differences that you have found between two solutions.
	   
## Part 2 
Load "diabetes" datasets from SKlearn and do the PCA for n=3, and plot the data.

	1. What is the variance (%) covered by the first 3 components? How is this percentage of variance computed?
 
	2. Is there any correlation between these three components?
 
	3. Apply t-SNE on the same dataset, select the first 3 components and plot them.
 
	4. Report the comparison between the results obtained using t-SNE and PCA
