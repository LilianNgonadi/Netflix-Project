# Netflix-Project
<!-- About The Project -->

<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->


<summary>Table of Contents</summary>
<ol>
  <li><a href="#description">Description</a></li>
  <li><a href="#dataset">Dataset</a></li>
  <li><a href="#exploratory-data-analysis">Exploratory Data Analysis</a></li>
  <ul>
    <li><a href="#visualize-distribution-of-content-types">Visualize Distribution of Content Types</a></li>
    <li><a href="#visualize-country-distribution">Visualize Country Distribution</a></li>
    <li><a href="#visualize-distribution-of-genre">Visualize Distribution of genre</a></li>
    <li><a href="#visualize-director-distribution">Visualize Director Distribution</a></li>
  </ul>
  <li><a href="#sentiment-analysis">Sentiment Analysis</a></li>
  <ul>
    <li><a href="#sentiment-distribution-by-release-year">Sentiment Distribution By Release Year</a></li>
  </ul>
  <li><a href="#k-means-clustering">K-means Clustering</a></li>
  <ul>
    <li><a href="#the-elbow-method">The Elbow Method</a></li>
    <li><a href="#the-silhouette-score">The Silhouette Score</a></li>
    <li><a href="#k-means-clustering">K-means Clustering</a></li>
    <li><a href="#k-means-clustering-with-pca">K-Means Clustering With PCA</a></li>
  </ul>
  <li><a href="#distribution-of-release-year-by-cluster">Distribution of Release Year by Cluster</a></li>
  <li><a href="#overall-insights">Overall Insights</a></li>
</ol>


# Author: Lilian Ngonadi

# Description

- This project aims to analyze Netflix content distribution and the sentiment of descriptions. It identifies trends in content types, countries producing content, and genres, and categorizes sentiment into positive, negative, and neutral.
- Additionally, the project groups titles based on release year and duration using clustering techniques. The analysis provides insights for content strategy and viewer engagement.

# Dataset

The dataset [Netflix  Titles dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download&select=netflix_titles.csv) is a comprehensive collection of information on various movies and TV shows available on Netflix. The dataset includes details such as the title, type, release year, duration, country, rating, and description, among other attributes:

- **show_id** :  Unique identifier for each title.
- **type** : Type of content (e.g., Movie, TV Show).
- **title** : Title of the content.
- **director** : Director(s) of the content.
- **cast** : Cast members in the content.
- **country**: Country where the content was produced.
- **date_added** : Date when the content was added to Netflix.
- **release_year** : Year the content was released.
- **rating** :Content rating (e.g., PG, R).
- **duration** :Duration of the content (e.g., 90 min, 1 Season).
- **listed_in** :Genres the content is listed under.
- **description** :Description of the content.

# Exploratory Data Analysis
* To analyze the distribution and trends of content types, countries producing content, and genres on Netflix using the [Netflix  Titles dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download&select=netflix_titles.csv)
## Visualize Distribution of Content Types
- The chart indicates that there are significantly more movies available on Netflix compared to TV shows. The count of movies exceeds 6000, while the count of TV shows is slightly above 3000.
- There are roughly twice as many movies as TV shows, suggesting that Netflix's catalog leans heavily towards movie content.

![Content type](Contenttype.png "Content type")

## Visualize Country Distribution

The bar chart shows that the United States is the dominant producer of Netflix content, contributing over 2500 titles. India follows as the second-largest contributor, with the United Kingdom in third place. Other notable contributors include Japan, South Korea, Canada, Spain, France, Mexico, and Egypt. This diverse range of content sources reflects Netflix's global reach and its strategy to cater to a wide variety of audience preferences worldwide.

![ Country feature](Countryfeature.png "Country feature")

## Visualize Distribution of genre

The  chart shows that the most prevalent genre on Netflix is International Movies, with over 2500 titles. This is followed by Dramas with around 1500 titles, and Comedies with about 1000 titles. Action & Adventure and Documentaries each have approximately 800 titles. This indicates a diverse content library on Netflix, with a strong emphasis on international movies and a balanced mix of other popular genres.

![Genre](genre.png "Genre")

## Visualize Director Distribution

This chart highlights the directors who have a substantial number of works featured on Netflix, showcasing their prolific contributions to the platform's diverse range of content.

![Director](director.png "Director")

# Sentiment Analysis

The chart shows that Netflix content descriptions are predominantly positive, with fewer negative and neutral sentiments. This suggests that Netflix emphasizes positive descriptions to engage viewers and promote its content.

![Sentiment Analysis](SentimentAnalysis.png "Sentiment Analysis")

## Sentiment Distribution By Release Year


The chart reveals that Netflix content descriptions are predominantly positive across all years from 2014 to 2021. There is a consistent presence of negative and neutral sentiments, but they are significantly fewer in comparison to positive sentiments. The trend also shows a peak in content descriptions around 2018. This analysis indicates Netflix's strategy of using positive language to market its content effectively.

![Sentiment By Year](Sentiment_by_year.png "Sentiment By Year")

# K-means Clustering


## The Elbow Method 

The Elbow Method chart suggests that the optimal number of clusters for this dataset is 3. This choice balances capturing the data’s structure and maintaining simplicity.

![Elbow Method](Elbowmethod.png "Elbow Method")

## The Silhouette Score 

The Silhouette Score chart suggests that the optimal number of clusters for this dataset is 3. This number of clusters provides the highest quality of clustering, with well-defined and separated clusters.

![Silhouette Score](Silhouettescore.png "Silhouette Score")

## K-means Clustering

The plot shows three distinct clusters of Netflix titles based on their release year and duration. Cluster 0 contains older, longer titles; Cluster 1 includes more recent, shorter titles; and Cluster 2 encompasses a variety of older content with mixed durations. This clustering highlights patterns in Netflix's content library, showing how the duration and release periods of titles can group into distinct categories.

![ K_Means_Clustering]( K_means_clustering.png "K_Means_Clustering")

## K-Means Clustering With PCA

The PCA plot shows that the titles can be effectively grouped into three distinct clusters based on their reduced dimensionality. Cluster 0 and Cluster 1 are more compact, indicating that the titles within these clusters are more similar to each other. Cluster 2 is more spread out, suggesting a more diverse set of titles.

![K_Means_Clustering_PCA](K_means_clustering_PCA.png "K_means_Clustering_PCA")

## Distribution of Release Year by Cluster

The histogram shows that Netflix's content library is heavily skewed towards titles released after the mid-1990s, with a sharp increase in the number of titles from 2000 onwards. Cluster 0 and Cluster 1 represent recent and contemporary titles, respectively, while Cluster 2 encompasses older content. This distribution reflects Netflix's focus on acquiring and producing new content while also maintaining a collection of classic titles.

![Cluster](cluster.png "Cluster")

# Overall Insights
- Netflix’s content library is heavily skewed towards movies, particularly those produced in the United States.
- There is a broad range of genres, with a significant focus on International Movies.
- Positive sentiments dominate content descriptions, reflecting a marketing strategy aimed at attracting viewers.
- Clustering analysis reveals distinct groupings of content based on release year and duration, with recent titles forming clear clusters.
