# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING

# Introduction
Netflix, the world’s largest on-demand internet streaming media and online DVD movie rental service provider.it Founded August 29, 1997, in Los Gatos, California by Marc and Reed. It has 69 million members in over 60 countries enjoying more than 100 million hours of TV shows and movies per day
Netflix is the world’s leading internet entertainment service with enjoying TV series, documentaries, and feature films across a wide variety of genres and languages. I was curious to analyze the content released in Netflix platform which led me to create these simple, interactive, and exciting visualizations and find similar groups of people.

# Problem Statement
The goal of this project is to find similarity within groups of people to build a movie recommendation system for users. We are going to analyze a dataset from the Netflix database to explore the characteristics that people share in movies. We have experienced it ourselves or have been in the room, the endless scrolling of selecting what to watch.  Users spend more time deciding what to watch than watching their movie.

# Data Summary
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.
* show_id : Unique ID for every Movie / Tv Show
* type : Identifier - A Movie or TV Show
* title : Title of the Movie / Tv Show
* director : Director of the Movie
* cast : Actors involved in the movie / show
* country : Country where the movie / show was produced
* date_added : Date it was added on Netflix
* release_year : Actual Release Year of the movie / show
* rating : TV Rating of the movie / show
* duration : Total Duration - in minutes or number of seasons
* listed_in : Genere
* description: The Summary description

# Exploring Solutions:
Having a deeper understanding of what problem we are trying to solve, what the users’ needs, and frustrations are, and what the goals are for achieving the best possible solution for both for the business as well as the user, I began by listing out the possible solutions that were arrived from the research.
1. Improve rating system: Use the star rating rather than a thumbs up and thumbs down rating system to help guide in decision making when selecting a film.
2. Separate recently watched: Hide the movies and TV-Shows on a separate page so users don’t have to scroll through those already seen. — users have to do more searching
3. Randomize a Movie: When users are unsure of what to choose, Netflix will randomly select something to watch based on their viewing history.
4. Show popular/trending films: Create a category which showcases only trending content.
5. Connect with Friends: It was proven that users watch shows and movies based on friend recommendations so this may be useful for keeping users locked into Netflix for longer.
6. Organizing films by the mood: Alongside the genres filter, it may be possible to organize content based on the mood that is experienced after watching the film.

# Steps involved:
* Loading and inspecting the Dataset
* Checking Shape of the Dataset
* Meaningful Column names
* Validating Duplicate Records
* Checking Missing values
* Unique values (counts) for each Feature
* Unique values (names) are checked for Features with a unique value count below 100
* Data validation - like for rating feature value cannot be the duration of the movie.
* Dataset Preparation
* DataType Validation
* Derived Columns
* Exploratory Data Analysis
* Movies & TV shows - Distribution
* A pattern for adding Movies & TV shows content annually, monthly, etc.
* Release year of a movie or TV show
* Identify how content is distributed based on maturity level - kids, teens, and adults
* Netflix's most popular genre
* Top 25 cast contributed to Netflix content
* day content added and Type (Movie or Tv Show)
* rating and type
* Summary of final recommendations

# What is a Recommendation System?
A recommendation system is a platform that provides its users with various contents based on their preferences and likings. A recommendation system takes the information about the user as an input.
This information can be in the form of the past usage of the product or the ratings that were provided to the product. It then processes this information to predict how much the user would rate or prefer the product. A recommendation system makes use of a variety of machine learning algorithms.
Another important role that a recommendation system plays today is to search for similarity between different products. In the case of Netflix, the recommendation system searches for movies that are similar to the ones you have watched or have liked previously.
This is an important method for scenarios that involve cold start. In cold start, the company does not have much of the user data available to generate recommendations.
Therefore, based on the movies that are watched, Netflix provides recommendations of the films that share a degree of similarity. There are two main types of Recommendation Systems –
1. Content-based recommendation systems
In a content-based recommendation system, the background knowledge of the products and customer information are taken into consideration. Based on the content that you have viewed on Netflix, it provides you with similar suggestions.
For example, if you have watched a film that has a sci-fi genre, the content-based recommendation system will provide you with suggestions for similar films that have the same genre.
2. Collaborative filtering recommendation systems
Unlike the content based filtering that provided recommendations of similar products, Collaborative Filtering provides recommendations based on the similar profiles of its users. One key advantage of collaborative filtering is that it is independent of the product knowledge.
Rather, it relies on the users with a basic assumption that what the users liked in the past will also like in the future. For example, if a person A watches crime, sci-fi and thriller genres and B watches sci-fi, thriller and action genres then A will also like action and B will like crime genre.
3. There is also a third type of recommendation system that combines both Content and Collaborative techniques. This form of recommendation system is known as Hybrid Recommendation System. Netflix makes the primary use of Hybrid Recommendation System for suggesting content to its users.


* Clustering:
Clustering or cluster analysis is a machine learning technique, which groups the unlabelled dataset. It can be defined as "A way of grouping the data points into different clusters, consisting of similar data points. The objects with the possible similarities remain in a group that has less or no similarities with another group."
It does it by finding some similar patterns in the unlabelled dataset such as shape, size, colour, behaviour, etc., and divides them as per the presence and absence of those similar patterns. 
It is an unsupervised learning method; hence no supervision is provided to the algorithm, and it deals with the unlabeled dataset. After applying this clustering technique, each cluster or group is provided with a cluster-ID. ML systems can use this id to simplify the processing of large and complex datasets.

# Conclusion
Data Analysis is a fundamental step to address the various needs of a client in any professional spectrum. The varied range of insights that can be derived from data is itself primarily valuable in nature as there are multiple businesses that are actively looking for futuristic, predictive and descriptive insights from the already present raw data generated by them. It helps the organizations to gain access to numerous concealed patterns, information and bits of knowledge after the analysis has been performed. The analysis that we have just performed using the Netflix data not only provides us with incentives to make smart and intelligent business decisions, but also contributes to the overall growth of the firm. These insights maintain a clear sight and perspective for various stakeholders and help in targeting a positive vision for the future. The future scope of Data Analysis is bound to remain intact as long as businesses require Data Science in their everyday applicable decision-making processes. Also, there is a great scale of possibilities when it comes to developing unique interactive solutions and methods that are confined to make data exploration much more intriguing in nature. These constant advancements have stabilized a promising direction for data analysis as a systemic study that is going to stay as long as there is the crunch for data in any viable field of study in the real-world.


# References:
* https://www.kaggle.com/onyonixch/netflix-movies-tv-shows-eda-and-clustering
* https://medium.com/@chitu_rk/clustering-algorithm-89f79c456336
* https://www.analyticsvidhya.com/blog/2021/06/tv-shows-analysis-netflix-prime-video-hulu-and-disney/
