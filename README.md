# Elevate-your-self
# Introduction
The project target is to create an AI that will music listeners. I developed a class user_similarity_recommender_py to mesure the similarity between users to recommend to each song his potential listeners: I used collaborative based system to predict what a particular user like based on what other similar users like. This approach is based on user-user filtering by defining a sparce matrix based on a user who liked a special song. I'm seeking to answer a question, for each user, what a song listened by a user, will also be listened by another set of users. 
# Tools:
- Google Colab: I uploaded my dataset: out.json file to google colab and then I pre-processed it.
# Requirements:
 - Pandas
 - numpy
 - itertools
 - Json and csv
 # Results : 
 - You can use my user_similarity_recommender_py() class to recommend to any music in the dataset the top 100 listeners based on a calculated score.
 - You can also use my user similarity based collaborative filtering model to find similar users to any users in the dataset.
