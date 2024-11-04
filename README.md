# Customer-Segmentation-
This project utilizes machine learning techniques to perform customer segmentation for an online retail dataset. By segmenting customers into distinct groups, this analysis helps in creating targeted marketing strategies and enhancing customer experience.
## Project Overview
Customer segmentation is crucial for businesses to understand their audience better and create targeted marketing strategies. In this project, we used various clustering techniques to segment customers based on purchasing behavior, and we evaluated the effectiveness of each method.
## Dataset
The dataset includes transactional data from an online retail store. Key features in the dataset:
- **Transaction ID**: Unique identifier for each transaction
- **Customer ID**: Unique identifier for each customer
- **Product Category**: Category of the purchased product
- **Quantity**: Quantity purchased
- **Price**: Price of the product
## Objectives
The project aimed to:
1. Identify and preprocess relevant data for customer segmentation.
2. Evaluate the performance of different machine learning models on clustering customers.
3. Propose a framework to integrate machine learning-based customer segmentation into online retail strategies.
## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, Scikit-learn, Seaborn, Matplotlib
- **Clustering Algorithms**: K-Means, DBSCAN, Agglomerative Clustering, Gaussian Mixture Models, Spectral Clustering
## Data Preparation
1. **Data Cleaning**: Removed missing values and filtered outliers.
2. **Feature Engineering**: Generated RFM (Recency, Frequency, Monetary) features for better customer segmentation.
3. **Standardization**: Scaled the features to enhance clustering performance.
## Modelling Approach
I applied several clustering methods to identify optimal customer segments:
1. **K-Means Clustering**: Applied to segment customers based on purchasing patterns.
2. **DBSCAN**: Used for density-based clustering.
3. **Agglomerative Clustering**: Hierarchical clustering method for defining groups.
4. **Gaussian Mixture Model (GMM)**: Probabilistic clustering technique.
5. **Spectral Clustering**: Applied for complex datasets with non-convex clusters.
## Results
- **Optimal Model**: Spectral clustering outperformed other clustering algorithms with a silhouette score of 0.9355.
- **Visualizations**: Scatter plots, pie charts, and histograms helped to understand customer distribution in each segment.
