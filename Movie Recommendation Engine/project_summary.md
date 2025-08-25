![alt text ](https://github.com/mayanktiwari-cpu/Data_science_project/blob/46f41d544a6faec719b96eb750fc7de84fb36379/Movie%20Recommendation%20Engine/stars-movies-1200x670-1.jpg)

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
![alt text](https://github.com/mayanktiwari-cpu/Data_science_project/blob/f84167103e53e2671641e7e2062ff200a0e0ae98/Movie%20Recommendation%20Engine/Screenshot_2025-08-25-20-14-58-74_40deb401b9ffe8e1df2f1cc5ba480b12.jpg)
<p align="center"><mark>The top-15 recommended movies based on "Toy Story" movie.</mark></p>

## Conclusion

The movie recommendation system built with collaborative filtering and KNN is an effective solution for personalizing movie suggestions. It leverages user behavior to create a tailored viewing experience. The model's performance metrics demonstrate its ability to make accurate predictions. 
