# BachelorThesis
Scripts and data for the Bachelor Thesis report

Here you will find all the scripts that has been used in the Bachelor Thesis, and each of them is referenced in the report. 

The data base used was created by Dr. Natalie Fey and Dr. Jesús Jover

Dalton Trans., 2013, 42, 172–181

-------------------------------------------------------------------------------------------------------
## Script 1: DR techniques and clustering algorithms
In this script, by introducing a dataset and specifying the descriptors, you will be able to perform PCA, t-SNE and UMAP (n=5,10 and 15).
At the same time, by setting a specific number for k and n you can test information of the maps by k-means and hierarchical clustering algorithms.
At the end you will find the space called: Other useful tools, which as the name indicates, are pieces of useful code for the analysis of the maps; including: 
- Filter by cluster and returning the id of the ligand
- PCA biplot
- PCA explained variance 
- Optimal k and n for k-means (by elbow method) and hierarchical (by dendrogram)

------------------------------------------------------------------------------------------------------
## Script 2: Test for clustering and reconstruction of data  
Split and clustering:
By defining the desired DR technique that you want to test and the corresponding clustering algorithm, it prints the accuracy score coefficient over 10 random states and the cross-validation accuracy score coefficients.
Split and regression: 
By defining the desired DR technique, it prints the regression coefficient over each of the descriptors for 10 random states, all at once.

-------------------------------------------------------------------------------------------------------
## Script 3: Prediction model substitution energy
By defining the desired DR technique, it prints the regression coefficient of the prediction model for 10 random states.

Then by choosing 1 random state, you can have the regression plot and the residuals plot.  

-------------------------------------------------------------------------------------------------------
## Script 4: Plotting new ligands without changing the model.
A set of ligands can be plotted on the map without changing the previous stablished models.

The new ligands are introduced (in our case they are called substitution), and it is indicated the sheet of the file where the calculated descriptors for these new ligands are. 
