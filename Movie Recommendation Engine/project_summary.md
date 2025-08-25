# Movie Recommendation Engine
## Introduction 
The rapid growth of digital platforms has resulted in a massive collection of movies, making it difficult for users to find content suited to their interests. A Movie Recommendation System aims to solve this problem by suggesting personalized movie options. This project leverages Collaborative Filtering and K-Nearest Neighbor (KNN) algorithms to generate recommendations based on user preferences and similarities.

## Objective
To build a movie recommendation system that suggests films to users based on their preferences and the preferences of similar users, using Collaborative Filtering and the K-Nearest Neighbors (KNN) algorithm.
## Data set

The final dataset contains two csv files . That is:
- rating (100836 rows and 5 columns)
- movies (9742 rows and 3 columns)

## Approach
### Collaborative Filtering
*Item-based Collaborative Filtering:* 
Finds similarities between movies based on how users rated them and recommends similar movies to those the user has already liked.

### K-Nearest Neighbors (KNN) Algorithm

Purpose: Identify the 15 most similar movies based on rating patterns.

Distance Metrics:  uses euclidean metrics.

## Results

- The system successfully recommends top-15 movies that align with user preferences.
- The KNN-based Collaborative Filtering model provides personalized recommendations.
- KNN provides interpretable and scalable recommendations.

## Conclusion

The movie recommendation system built with collaborative filtering and KNN is an effective solution for personalizing movie suggestions. It leverages user behavior to create a tailored viewing experience. The model's performance metrics demonstrate its ability to make accurate predictions. 
