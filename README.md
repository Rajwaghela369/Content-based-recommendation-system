# Content-Based Movie Recommender

## Aim: 
The main goal of this project is to develop a content-based recommendation system that suggests movies and tv-shows or web-shows to users based on their preferred genres. 

## Abstract:
The content-based recommendation system addressed in this project leverages the genres associated with each movie and the user's preferred genres to generate relevant movie recommendations. By employing techniques such as genre similarity calculation and personalized user profiles, the system offers an efficient way for users to explore movies aligned with their interests. 

## Data Introduction:
Netflix and Amazon Movies and Tv Shows Dataset from Kaggle is used to build the recommendation system. This Dataset include columns such as 
1. Id - movies and tv shows id
2. Title - of movies and shows
3. Type - define each data is 'MOVIE' or 'SHOW'
4. Genres - define features like action, thriller, scifi, horror, drama, etc for each observations
others are release year, imdb_score, tmdb_score. Listed columns are considered for further processing.

## Data references: 
1. [Netflix data set](https://www.kaggle.com/datasets/shivamb/netflix-shows)
2. [Prime data set](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)

## Features Distribution Graphs:
![1](https://github.com/Rajwaghela369/Content-based-recommendation-system/blob/b51d073a7f5549db9baf8ad7c577f5f1837216e9/Assets/Graph%201.png)
![2](https://github.com/Rajwaghela369/Content-based-recommendation-system/blob/b51d073a7f5549db9baf8ad7c577f5f1837216e9/Assets/Graph%202.png)
![3](https://github.com/Rajwaghela369/Content-based-recommendation-system/blob/b51d073a7f5549db9baf8ad7c577f5f1837216e9/Assets/Graph%203.png)

## WorkFlow:
**1. Features Extraction**
**2. Features Matrix Creation**
**3. User Profile Creation**
**4. Cosine Similarity Computation**
**5. Recommendations Generation**
