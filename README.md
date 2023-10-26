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

![](/Image/website%20classification%20image.png)

# [Project 2: Customer-Segmentation](https://github.com/LIONKINGGU/Customer-Segmentation)
Objective:
This project aims to cluster customers based on their purchasing behaviour using the K-means clustering algorithm. The goal is to uncover distinct segments within the customer base.

The project starts by loading customer data from 'customersdata.csv' and exploring the data types to understand the nature of the features.

Irrelevant columns ('Channel' and 'Region') are dropped, as they are not needed for clustering. The dataset is then standardized to ensure uniform scales for accurate clustering.

The optimal number of clusters is determined using the elbow method. This technique helps find the point where the within-cluster sum of squares (WCSS) no longer decreases significantly, indicating a suitable number of clusters.

The K-means algorithm is employed with the chosen number of clusters (5 in this case). The model is fitted to the data, and predictions are made to assign each customer to a specific cluster.

Results are visually presented using a scatter plot. Each cluster is differentiated by a unique color, and centroids are marked in yellow. This visualization provides a clear representation of how customers are grouped based on their 'Frozen' and 'Milk' purchases.

The clusters and centroids reveal insights into customer segments. Businesses can use this information for targeted marketing strategies, product recommendations, and tailored services for each customer cluster.

![](/Image/Customer%20Segmentation%20Images.png)


# [project 3: SQL-Covidproject](https://github.com/LIONKINGGU/SQLCovidproject)
In this SQL-driven exploration, we delve into the COVID database, orchestrating a symphony of queries to unravel meaningful insights, particularly focusing on the United States. Database creation (covidproject) and table examination for worldometer_data and usa_county_wise, Rename and modify column names for clarity and consistency. Navigating the vast sea of data, we forge connections between tables. A common identifier (ID) emerges, enabling seamless joins and unleashing the potential for cohesive insights by merging COVID-19 statistics with geographical nuances. Investigate the relationship between the population and COVID-19 cases. Calculate death percentages, recovery percentages, and active case percentages in different locations and continents. Identify the locations with the highest death count and continents with the highest death count. Explore active cases as a percentage of total cases for different continents. Investigate the total number of new cases and deaths over time. Join tables to add dates to the analysis, focusing on the United States and its states. Create a temporary table (Vaccinated People) to showcase vaccination information. Insert sample data and demonstrate SQL queries to analyze vaccination trends, comparing total vaccination with the population.
