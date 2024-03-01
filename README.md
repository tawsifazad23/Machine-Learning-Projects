# Customer Segmentation Analysis Using K-Means Clustering

## Project Overview
This project demonstrates an application of the K-Means clustering algorithm for customer segmentation. Using a dataset of mall customers, the analysis aims to categorize customers into distinct groups based on their annual income and spending score. This segmentation provides valuable insights into customer behavior, aiding in the development of targeted marketing strategies.

## Technologies Used
- Python
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

## Dataset
The dataset, named 'Mall_Customers.csv', includes the following columns:
- CustomerID
- Gender
- Age
- Annual Income (in thousand dollars)
- Spending Score (1-100)

## Methodology
1. **Data Preprocessing**: The dataset is loaded into a Pandas DataFrame, and preliminary analysis is conducted to understand its structure and content.

2. **Exploratory Data Analysis**:
   - The dataset is explored to check for missing values and understand data types.
   - Key variables 'Annual Income' and 'Spending Score' are identified for clustering.

3. **Determining the Number of Clusters**:
   - The Elbow Method is employed to determine the optimal number of clusters by calculating the Within-Cluster-Sum-of-Squares (WCSS) for different cluster numbers.

4. **Model Training**:
   - The K-Means clustering algorithm is applied to the dataset with the chosen number of clusters (5 in this case).

5. **Cluster Visualization**:
   - A scatter plot is created to visualize the clusters based on 'Annual Income' and 'Spending Score'.
   - Centroids of the clusters are marked to highlight the core of each cluster.

## Results
The analysis successfully segments the mall customers into 5 distinct groups. Each group represents a combination of annual income and spending score, providing a clear picture of different customer types. This segmentation can be instrumental in designing personalized marketing campaigns and enhancing customer satisfaction.

## Visualizations
The project includes several visualizations:
- The Elbow Point Graph: To determine the optimal number of clusters.
- Cluster Scatter Plot: Illustrating the customer segments with their respective centroids.

## Conclusion
This customer segmentation analysis showcases the power of K-Means clustering in marketing analytics. The insights derived from this project can help businesses understand their customer base better and tailor their strategies accordingly.

