Introduction

In this project I am segmenting mall customers into distinct groups by examining their spending scores and income. 
This segmentation enables the implementation of targeted marketing strategies, ensuring that each group receives personalized and relevant marketing efforts.

To segment customers I am using an unsupervised machine learning technique called K-means clustering for the following reasons -
- K-means algorithm can efficiently identify distinct groups within the two-dimensional space. 
- The results of k-means are easy to interpret, as customers are grouped into clusters based on their proximity to cluster centroids, allowing for straightforward visualization and understanding.
- Additionally, K-means is well-suited for continuous data, such as income and spending scores, where distance measures like Euclidean distance can be effectively used to define similarity.

Data Preparation 

I am extracting spending score and annual income features for the purpose of clustering as it will help identify distinct customer groups based on their spending potential. 
Identifying such groups will provide actionable insights into customer behavior, allowing the mall to tailor marketing strategies, promotions, and offerings to specific customer segments.

K-Means Clustering 

After running the K-means algorithm, the elbow chart reveals a distinct decline in the Within-Cluster Sum of Squares at 5 clusters, 
suggesting this as the optimal number of clusters.

<img width="335" alt="K5" src="https://github.com/user-attachments/assets/414f3c7f-c68c-43c2-b5ff-314bf75db7d0">

Visualization of Clusters

<img width="367" alt="K5Clusters" src="https://github.com/user-attachments/assets/3b917fb3-7f07-42b8-8faa-defe2e60d6cb">

Distinct clusters can be observed in the scatterplot. 
The 5 clusters observed are as follows -

- High Income - High Spending
- High Income - Low Spending
- Low Income - High Spending
- Low Income - Low Spending
- Middle Income - Average Spending










