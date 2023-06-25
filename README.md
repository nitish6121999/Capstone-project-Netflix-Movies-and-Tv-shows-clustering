# Capstone-project-Netflix-Movies-and-Tv-shows-clustering
Almabetter verified project

![](https://media.tenor.com/Rfyx9OkRI38AAAAC/netflix-netflix-startup.gif)

## Problem statement
The aim of this project is to perform clustering analysis on a dataset of Netflix movies and TV shows. Netflix is a popular streaming platform that offers a wide range of content. By clustering these movies and TV shows, we can identify similar content and gain insights into the underlying patterns and categories present in the Netflix library.

The specific tasks to be performed in this project include:

1. **Exploratory Data Analysis (EDA)**: Cleaned the data, unnested the Netflix content and tackled the null/missing values and conduct a thorough analysis of the dataset to uncover trends, patterns, and correlations among different attributes.
2. **Understanding Content Availability**: Determine the types of content available in different countries and identify any variations or preferences.
3. **Analyzing Netflix's Focus**: Investigate whether Netflix has been increasingly focusing on TV shows rather than movies in recent years.
4. **Clustering Similar Content**: Utilize text-based features to cluster similar content,

## Dataset
The dataset used in this project contains information about movies and TV shows available on Netflix. It includes features such as title, director, cast, genre, release year, duration, and country. The dataset is sourced from [provide the source of the dataset here].


## Project Summary

The aim of this project is to analyze the Netflix dataset, which includes information on movies and TV shows available on the platform until 2019. With over 220 million subscribers, Netflix is the world's largest online streaming service provider. By analyzing and clustering the content, we can enhance the user experience through a personalized recommendation system, potentially reducing subscriber churn.

The project follows a step-by-step process, as outlined below:

1. **Handling Missing Values**: Address any null or missing values present in the dataset.
2. **Dealing with Nested Columns**: Process nested columns such as director, cast, listed_in, and country to facilitate clear visualization and analysis.
3. **Rating Binning**: Categorize ratings into appropriate categories, including adult, children's, family-friendly, and not rated content.
4. **Exploratory Data Analysis (EDA)**: Perform in-depth EDA on various attributes, uncovering valuable findings to aid in churn prevention.
5. **Cluster Creation**: Create clusters using attributes such as director, cast, country, genre, rating, and description. Tokenize, preprocess, and vectorize the attribute values using TF-IDF vectorizer.
6. **Dimensionality Reduction**: Reduce the dimensionality of the dataset using Principal Component Analysis (PCA) to improve performance.
7. **Clustering Algorithms**: Employ K-Means Clustering and Agglomerative Hierarchical Clustering algorithms to construct two distinct types of clusters. Determine the optimal number of clusters using methods like the Elbow method, Silhouette score, and Dendrogram.
