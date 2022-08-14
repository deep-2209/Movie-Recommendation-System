# Movie-Recommendation-System

Recommendation System is an information filtering Systems that suggests relevant items to users.

# Types of Recommendation System
Recommendation systems can be broadly classified into 3 types —

1) Collaborative Filtering
2) Content-Based Filtering
3) Hybrid Recommendation Systems

COLLABRATIVE FILTERING - This filtering method is usually based on collecting and analyzing information on user’s behaviors, their activities or preferences, and predicting what they will like based on the similarity with other users.

The two most popular forms of collaborative filtering are:

i) User Based: Here, we look for the users who have rated various items in the same way and then find the rating of the missing item with the help of these users.

ii) Item Based: Here, we explore the relationship between the pair of items (the user who bought Y, also bought Z). We find the missing rating with the help of the ratings given to the other items by the user. The very first step is to build the model by finding similarity between all the item pairs. The similarity between item pairs can be found in different ways. One of the most common methods is to use cosine similarity.

The method used to construct the movie recommendation system is the K-Nearest Neighbours (K-NN) classification algorithm (Item Based), which essentially looks to make predictions based on closest data points.


Check out the live demo: https://movie-recommendation-systemdp.herokuapp.com/
