# Big Data Project - Million Song Dataset
Map-Reduce framework based project using Apache Spark.

This project uses data from the Million Song Dataset.  The files used are as follows.
- 'kaggle_visible_evaluation_triplets.txt'
- 'kaggle_songs.txt'
- 'kaggle_users.txt'

This project consists of 4 parts:

1. Create an RDD with kaggle_visible_evaluation_triplets.txt and replace the song name with the song index from kaggle_songs.txt. Identify the number of songs that do not have any rating.
2. Generate song ratings based on the song play count as a normalized score between 0 and 1.
3. Identify the popular song based on this rating and recommend songs to user, given user id based on the algorithm used in Movie recommender system from class.
4. Using Cosine similarity function, identify pair-wise similarity between each pair of users and generate the top 5 most similar users without an overlap in users.
