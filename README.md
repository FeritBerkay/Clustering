# Clustering

In this analysis, I delved into Mall Customer Segmentation Data using unsupervised learning to identify specific customer segments, particularly those likely to converge (Target Customers). To start, I explored the dataset, checked for missing values and duplicates, and standardized the gender variable by assigning numeric values (0 for female, 1 for male). This ensured the data was primed for modeling.

Next, I employed the k-means algorithm, experimenting with different cluster numbers (2, 3, 4, 5). Since the dataset had 5 diverse features, I used PCA to condense the dimensions for visualization. After running the algorithms, I assessed their performance using Inertia and Silhouette Score metrics. The analysis revealed that the algorithm performed best with 2 clusters.

I decided to utilize the DBSCAN clustering algorithm to experiment with my data by employing various clustering techniques. To achieve this, I imported the DBSCAN library and fitted my dataset to it. I aimed to determine the optimal values for epsilon and min_samples, striving for the best model performance. Subsequently, I visualized my dataset using the Seaborn library.
