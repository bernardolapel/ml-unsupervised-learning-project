# machine_learning_project-unsupervised-learning

## Project Outcomes
- Unsupervised Learning: perform unsupervised learning techniques on a wholesale data dataset. The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.
### Duration:
Approximately 1 hour and 40 minutes
### Project Description:
In this project, we will apply unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project will involve the following tasks:

-	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
-	Unsupervised learning: We will use the Wholesale Data dataset to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together. We will determine the optimal number of clusters and communicate the insights gained through data visualization.

The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

# machine_learning_project-supervised-learning

## Project Outcomes
- Supervised Learning: use supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements.The project involves three main parts: exploratory data analysis, preprocessing and feature engineering, and training a machine learning model. 
### Duration:
Approximately 3 hours and 20 minutes.
### Project Description:
In this projects, you will apply supervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Diabetes" dataset from the National Institute of Diabetes and Digestive and Kidney Diseases 
The project will involve the following tasks:

-	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
-	Supervised learning: We will use the Diabetes dataset to build a machine learning model that can predict whether a patient has diabetes or not, using appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. We will select at least two models, including one ensemble model, and compare their performance.

The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

# Unsupervised Learning Project

## Project/Goals
- Apply unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis 
- Perform exploratory data analysis, 
- Preprocessing and feature engineering, 
- Perform KMeans clustering, 
- Perform hierarchical clustering,
- Perform PCA

## Process
Step 1: Import libraries and load dataset
Step 2: Perform Explorative Data Analysis to understand the dataset.
Step 3: Check for missing information in the dataset and data description.
Step 4: Clean dataset by identifying and treating outliers.
Step 5: Apply Clustering technique and algorithms.
Step 6: Gain insights from the data sets.
Step 7: Communicate insights using appropriate visualizations.


## Results/Findings
- After analyzing the histogram we can identify that there are some outliers in some columns.
- No Missing Values: There are 440 entries in each column, and no missing values in the data, which is good.

- No Duplicates: The data doesn't have any duplicate rows.

- Channels and Regions: These seem to be categorical variables, with 'Channel' having two categories (1 and 2) and 'Region' three categories (1, 2, 3).

- Different Scales: The means and standard deviations for each feature vary significantly, indicating that the data spans several orders of magnitude. This could potentially impact certain machine learning models that are sensitive to the scale of the input features ). You might need to consider feature scaling.

- Outliers: Looking at the difference between the 75% percentile (Q3) and the maximum values of each feature, we see significant jumps. For instance, in the 'Fresh' feature, the 75% percentile is at 16933.75, but the maximum value is 112151. This suggests the presence of outliers that could potentially skew your model.

- Right Skewness: Features such as 'Fresh', 'Milk', 'Grocery', 'Frozen', 'Detergents_Paper', and 'Delicassen' show a right skew (mean > median). This could impact the performance of some machine learning algorithms.


## Conclusion
- Performing PCA on dataset for feature reduction yielded four clusters; 
	1. Cluster 3 is the combination of products that falls around 	zero and negative. Stakeholders should consider promo or discount 	to encourage customers to engage in the purchase of those items.
	2. Cluster 2 is the combination of products that are of high 	interest to customers, therefore, stakeholder should provide 	measure to retain this group and provide ways to increase their purchasing activities.
- Performing K-means on the dataset grouped the products into 4 clusters.
- Right Skewness: Features such as 'Fresh', 'Milk', 'Grocery', 'Frozen', ‘Detergents Paper', and 'Delicassen' show a right skew (mean > median).This could impact the performance of some machine learning algorithms.
Combination of Milk and detergents paper/Grocery shows a positive linear relationship with channel 2 and region 3 playing a significant part.
- There is a very strong Relationship between the Grocery, Detergents_paper and Channel variables
- The Hierarchical Cluster shows two clusters based on agglomerative clustering.


