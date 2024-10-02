# Social Media User Segmentation
This project uses **Hierarchical Clustering** to segment social media users into distinct groups based on their behavior. By analyzing features such as **satisfaction, addiction level, and time spent** on social media, we identify meaningful clusters that help understand different user types.

## Table of Contents
+ Project Overview
+ Dataset
+ Clustering Algorithm
+ Results
+ Requirements
+ Conclusion

## Project Overview
The goal of this project is to perform segmentation on a social media dataset to discover different groups of users based on their behavior. This segmentation can be useful for understanding user engagement patterns, addiction levels, and satisfaction with the platform.

## Key Steps:
+ **Data Preprocessing:** Handling missing values, scaling features.
+ **Hierarchical Clustering:** Using agglomerative clustering with Ward’s linkage to group users into clusters.
+ **Cluster Profiling:** Analyzing and visualizing the clusters to understand the differences in user behavior.

## Dataset
The dataset consists of user information including:

+ Total Time Spent on social media.
+ Addiction Level: Self-reported level of addiction.
+ Satisfaction: Self-reported satisfaction from using social media.
For Dataset Link Click [HERE](https://www.kaggle.com/datasets/muhammadroshaanriaz/time-wasters-on-social-media)

## Clustering Algorithm
+ Hierarchical Clustering:
+ **Linkage:** Ward’s method
+ **Distance Metric:** Euclidean distance
+ **Number of Clusters:** 4 (based on the dendrogram analysis)

The algorithm iteratively merges data points based on their similarity, resulting in a hierarchical structure visualized through a dendrogram.

## Results
The social media users were divided into 4 clusters:

+ Cluster 0: Highly satisfied but highly addicted users.
+ Cluster 1: Moderately satisfied and moderately addicted users.
+ Cluster 2: Low satisfaction and low addiction levels.
+ Cluster 3: Balanced users with moderate satisfaction and low to moderate addiction.

## Visualization:

+ **Dendrogram:** Used to determine the optimal number of clusters.

![image](https://github.com/user-attachments/assets/6fe6673c-33f8-4170-9f6d-30c10baf2322)


+ **Scatter Plot:** Satisfaction vs Addiction Level by Cluster.

![image](https://github.com/user-attachments/assets/6398dd2a-782d-4635-bbfd-6ff1d56cc11f)


+ **Box Plot:** Comparing total time spent across clusters.

![image](https://github.com/user-attachments/assets/af87fda9-b59e-4187-be47-018d292371a0)


## Requirements
+ Python 3.x
### Required libraries:
+ pandas
+ matplotlib
+ seaborn
+ scikit-learn
+ scipy

## Conclusion
By clustering social media users, this project demonstrates how user segmentation can provide insights into different behaviors and addiction levels. These findings can inform targeted strategies for engagement, user satisfaction, and healthier social media use.

## Future Work
+ Apply other clustering algorithms (e.g., K-Means, DBSCAN).
+ Use advanced techniques such as dimensionality reduction (e.g., PCA) to enhance the clustering process.
+ Integrate more features (e.g., demographics, usage frequency) for a richer user segmentation.
