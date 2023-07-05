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
 
 ## Part 3
**Datafile:** SCADI.csv

**Data Description:**
This dataset contains 206 attributes of 70 children with physical and motor disability based on ICF-CY. 
For more information click this link.

	1. Determine the number of subgroups from the dataset using attributes 3 to 205 i.e.,
	exclude attributes 1, 2 and 206. Is this number the same as the number of classes
	presented by attribute 206? Explain and justify your findings.
 
	2. Is this data facing the curse of dimensionality? If so, then how to solve this problem.	
	Explain with a two-dimensional plot and report relevant loss of information.
 
	3. After applying principal component analysis (PCA) on a given dataset, it was found that
	the percentage of variance for the first N components is X%. How is this percentage of
	variance computed?
 
 ## Part 4
**Dataset filename:** obesity_levels.csv

**Dataset description:**
This dataset includes data for the estimation of obesity levels in individuals
based on their eating habits and physical condition. The data contains 17 attributes and 2111
records.

**Features and labels:** 
The attribute names are listed below. The description of the attributes can be
found in this article (web-link).

Create a machine learning (ML) model for predicting “weight” using all features except
“NObeyesdad” and report observed performance. Explain your results based on following
criteria:

	a. What model have you selected for solving this problem and why?
 
	b. Have you made any assumption for the target variable? If so, then why?
 
	c. What have you done with text variables? Explain.
 
	d. Have you optimized any model parameters? What is the benefit of this action?
 
	e. Have you applied any steps for handling overfitting or underfitting issues? What is
	   that?
