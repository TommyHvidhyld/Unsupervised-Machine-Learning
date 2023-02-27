# Unsupervised Machine Learning
## Creating a classification model to better predict myopia patients

### This project is broken down into four parts:

### Part 1: Prepare the Data

  -Read in the myopia.csv into a Pandas Dataframe

  -Remove the "MYOPIC" column from the dataset

  -Standardize your dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values

### Part 2: Apply Dimensionality Reduction

  -Perform dimensionality reduction with PCA

  -Further reduce the dataset dimensions with t-SNE and visually inspect the results

  -Create a scatter plot of the t-SNE output

### Part 3: Perform a Cluster Analysis with K-means

  -Create an elbow plot to identify the best number of clusters

### Part 4: Make a Recommendation

After data preparation, PCA data reduction, and further reduction using the t-SNE method a cluster analysis with K-Means model was applied to the data. According to the analysis of the elbow chart, out data indicated k=3. My recommendation moving forward would be to cluster the patients into three groups.
