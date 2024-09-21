# Movie Recommendation System with Network and Sentiment Analysis #

This project is a comprehensive film recommendation system that leverages multiple recommendation algorithms, sentiment analysis, and network analysis to suggest movies to users based on their preferences and social interactions. The system provides personalized movie recommendations by integrating collaborative filtering, content-based approaches, and advanced analytics, including sentiment and network analysis.

# Project overview #

The system consists of several core components:

## 1. Collaborative Filtering-Based Recommendation: ## 
Recommends movies by identifying users with similar viewing patterns.

## 2. Content-Based Recommendation: ##
Suggests films by analyzing their features (e.g., genre, cast, and director) in comparison to user preferences.

## 3. Network Analysis: ##
I studied the structure of user and movie data to identify communities within films that share different characteristics.
By examining user interactions and film characteristics, I created recommendations for users without strong expressed preferences.

## 4. Text and Sentiment Analysis: ##
Uses natural language processing (NLP) techniques to analyze movie reviews and ratings. Sentiment scores derived from this analysis are incorporated into the recommendation algorithms to improve personalization.

## 5. Analytics and Data Visualization: ##
Provides in-depth analytics on user behaviors, popular movie genres, sentiment trends, network structures, and more.

# Dataset #
The dataset includes the following attributes:

## Movie Metadata ##

title: The movie title

directedBy: Director of the movie

starring: Main actors

avgRating: Average rating on MovieLens

imdbId: IMDb ID of the movie

item_id: Movie ID

## Survey Answers ##
item_id: Movie ID

user_id: User ID

tag_id: Tag ID

score: User confidence in the relevance of the tag to the movie

## Tags ##
tag: The tag itself

id: Tag ID

User Ratings

item_id: Movie ID rated

user_id: User ID who rated the movie

rating: User rating for the movie

# Technologies Used # 
Programming Languages: R
