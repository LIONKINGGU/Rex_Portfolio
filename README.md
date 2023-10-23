# Rex_Portfolio
Entry data analyst exploring the data world as a professional

# [Project 1: Website Data Classification](https://github.com/LIONKINGGU/Classification-website)
Utilized pandas and matplotlib to explore and visualize the dataset, identifying missing values and gaining insights into the distribution of numerical and categorical variables.
Analyzed the distribution of key metrics such as 'Numof Clicks,' 'Mins spent,' and 'Frequency' to understand user engagement with the website.
Investigated the distribution of devices used by visitors and their geographical locations, providing a comprehensive overview of user demographics.
Employed LabelEncoder from scikit-learn to preprocess categorical variables, enabling the utilization of machine learning algorithms on the dataset.
Implemented a Decision Tree Classifier to predict the 'Category' variable based on features like device, location, and timestamp, demonstrating the application of machine learning for classification tasks.

Split the dataset into training and testing sets, trained the Decision Tree Classifier, and evaluated the model's performance using classification reports and a confusion matrix.
Demonstrated the model's ability to predict user categories, providing valuable information for understanding and segmenting the user base of the website.


# [Project 2: Customer-Segmentation](https://github.com/LIONKINGGU/Customer-Segmentation)
Objective:
This project aims to cluster customers based on their purchasing behavior using the K-means clustering algorithm. The goal is to uncover distinct segments within the customer base.

The project starts by loading customer data from 'customersdata.csv' and exploring the data types to understand the nature of the features.

Irrelevant columns ('Channel' and 'Region') are dropped, as they are not needed for clustering. The dataset is then standardized to ensure uniform scales for accurate clustering.

The optimal number of clusters is determined using the elbow method. This technique helps find the point where the within-cluster sum of squares (WCSS) no longer decreases significantly, indicating a suitable number of clusters.

The K-means algorithm is employed with the chosen number of clusters (5 in this case). The model is fitted to the data, and predictions are made to assign each customer to a specific cluster.

Results are visually presented using a scatter plot. Each cluster is differentiated by a unique color, and centroids are marked in yellow. This visualization provides a clear representation of how customers are grouped based on their 'Frozen' and 'Milk' purchases.

The clusters and centroids reveal insights into customer segments. Businesses can use this information for targeted marketing strategies, product recommendations, and tailored services for each customer cluster.

