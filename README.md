This Python script analyzes the McDonald's dataset by performing PCA, clustering, regression analysis, and visualization.

1. Data Preprocessing
Loads the dataset (mcdonalds.csv).

Converts categorical Yes/No responses into binary (1 = Yes, 0 = No).

2. Principal Component Analysis (PCA)
Performs PCA on customer responses.

Scree plot visualizes variance explained by each principal component.

Scatter plot shows data in the first two principal components.

3. Clustering
K-Means Clustering (k=4) groups similar customers.

Hierarchical Clustering (Dendrogram) visualizes feature relationships.

4. Data Visualization
Age Distribution is analyzed across clusters using a boxplot.

Mosaic Plot (Heatmap Approximation) shows cluster-wise liking scores.

5. Regression Analysis
Converts ‘Like’ scores into numerical format (Like.n = 6 - Like).

Runs an OLS regression model to predict Like.n based on features.

Prints the regression summary.

6. Visit Frequency vs. Like Score
Scatter plot visualizing:

Visit frequency vs. Like score.

Bubble size represents % of females in each cluster.

Each cluster is labeled on the plot.

