# Customer-Segmentation
Problem statement-
Dividing customers into various groups by using different clustering algorithms for customer segmentation

Toolkit- 
Using the following python libraries-
For data cleaning- Numpy, Pandas
For data visualization- Matplotlib, Seaborn, Plotnine
For clustering- Sklearn, Scipy, factor_analyzer
For factor analysis- factor_analyzer

Data Dictionary-
The raw data contains 10 columns- ID, Gender, Ever_Married, Age, Graduated, Profession, Work_Experience, Spending_Score, Family_Size, and Var_1.
Age, Work_Experience, and Family_Size are numerical columns, while Ever_Married, Graduated, Profession, Spending_Score, and Var_1 are categorical. 
The column ‘ID’ is dropped because of its irrelevance to the analysis.

Methods-
K-means clustering-
K-means clustering is the most commonly used clustering algorithm. It's a centroid-based algorithm and the simplest unsupervised learning algorithm. This algorithm tries to minimize the variance of data points within a cluster.

Gaussian Mixed Models-
One of the problems with k-means is that the data needs to follow a circular format. The way k-means calculates the distance between data points has to do with a circular path, so non-circular data isn't clustered correctly. This is an issue that Gaussian mixture models fix. You don’t need circular shaped data for it to work well. The Gaussian mixture model uses multiple Gaussian distributions to fit arbitrarily shaped data. There are several single Gaussian models that act as hidden layers in this hybrid model. So, the model calculates the probability that a data point belongs to a specific Gaussian distribution and that's the cluster it will fall under.

Agglomerative clustering-
Agglomerative clustering follows a bottom-up approach and starts by placing each data point in its own cluster. It then merges each of these individual clusters into larger and larger clusters, up until all of the data points are grouped into a single cluster, also called root, or until certain termination conditions are satisfied.

Factor Analysis-
Factor Analysis (FA) is an exploratory data analysis method used to search influential underlying factors or latent variables from a set of observed variables. It helps in data interpretations by reducing the number of variables. It extracts maximum common variance from all variables and puts them into a common score.

Spectral clustering-
Spectral clustering  treats each data point as a graph-node and thus transforms the clustering problem into a graph-partitioning problem.
