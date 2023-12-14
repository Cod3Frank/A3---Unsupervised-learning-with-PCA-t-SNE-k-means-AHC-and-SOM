# A3---Unsupervised-learning-with-PCA-t-SNE-k-means-AHC-and-SOM

Part 1: Selecting and analyzing the datasets
The unsupervised learning techniques must be applied on two datasets:
1. Synthetic dataset (A3-data.txt):
o Features: 4 variables, 1 class
o Patterns: 360 patterns
o The class information must “not” be used in the unsupervised learning, only to identify the classes in the plots
2. Search a dataset from the Internet, with the following characteristics:
o Features: at least 6 variables, and a class attribute
o The class attribute must refer to, at least, 4 different classes
o Patterns: at least 200 patterns
o The class information must “not” be used in the unsupervised learning, only to identify the classes in the plots
As an output of this part, you should include in your report the following analysis:
• For dataset 2, describe the details of the dataset and the link to the source webpage where it has been download. If you have done any type of data preprocessing also include this information in the dataset description.
principal components, and a scree plot with the accumulated variance.
• t-SNE: find and plot the t-SNE projection in two dimensions, using a different color for each class. You can play with different parameters of the t-SNE (perplexity, …). For each set of parameters you should include a colored scatter plot visualization with the description of the used parameters.
• k-means: use k-means to classify the patterns in 𝑘=2,3,…,𝐾 classes, and compare the obtained classes with the real ones. For each value, include a scatter plot of the data (e.g., using as 𝑥 and 𝑦 coordinates the PCA reduction), and color the points according to the classes they belong to. If the value of 𝑘 is equal to the real number of classes, you can use a confusion matrix to compare the results obtained.
• AHC: use the unweighted average (UPGMA) and complete linkage (CL) methods of Agglomerative Hierarchical Clustering (AHC), using as input the matrix of Euclidean distances between the original patterns, and use different colors to represent the patterns in each original class. Plot the resulting dendrograms.
• SOM: use Self-Organizing Maps (SOM) to visualize the data, using different settings (topology and size of the map, learning rate, neighborhood function, etc.). The minimum size for the SOM architecture must have at least 100 neurons. Examples of visualizations of SOM are a heatmap of the most represented class in each position, or the u-matrix. For the “best” map, also calculate and plot the component planes.
