Here you will find all the scripts that has been used in the Bachelor Thesis, and each of them is referenced in the report. 

---------------------------------------------------------------------------------------------------------------------------------------------
Script 1: DR techniques and clustering algorithms

In this script, by introducing a dataset and specifing the descriptors, you will be able to perform PCA, tSNE and UMAP (n=5,10 and 15)
At the same time, by seting a number of k and n you can test information of the maps by kmeans and hierarchical clustering algorithms.

At the end you will find the space called: Other useful tools, which as the name indicates, are pieces of code useful for the analysis 
of the maps; including: 
- Filter by cluster and returing the id of the ligand
- PCA biplot
- PCA explained variance 
- Optimal k and n for kmeans (by elbow method) and hierarchical (by dendrogram)

---------------------------------------------------------------------------------------------------------------------------------------------
Script 2: Test for clustering and reconstruction of data  

Split and clustering:
By defining the dimensionality reduction you want to test and the corresponding clustering algorithm 
it prints the accuracy score coefficient over 10 random states and the cross validation accuracy score 
coefficients

Split and regression: 
By definig the dimensionality reduction you want it print the regression coefficient over each of the descriptors for
10 random states, all at once. 

---------------------------------------------------------------------------------------------------------------------------------------------
Script 3: Prediction model substitution energy
By definig the dimensionality reduction you want it print the regression coefficient of the prediction model for 10 random states

Then by choosing 1 random state, you can have the regreesion plot and the residuals plot. 

---------------------------------------------------------------------------------------------------------------------------------------------
Script 4: Plotting new ligands without changing the model
A set of ligands can be plotted on the map without changing the previous stablished models

The new ligands are introduced (in our case they are called substitution), and it is indicated the sheet of the file where the calculated
descriptors for this new ligans are. 


