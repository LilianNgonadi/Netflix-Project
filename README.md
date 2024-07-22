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
      <li><a href="#visualize-numerical-feature-distribution">Visualize Numerical Feature Distribution</a></li>
      <li><a href="#visualize-categorical-feature-distribution">Visualize Categorical Feature Distribution</a></li>
      <li><a href="map-visualization-of-health-facilities">Map Visualization of Health Facilities</a></li>     
    </ul>
  </li>
  </li>
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
