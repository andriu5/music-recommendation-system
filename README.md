# **Music Recommendation System**


## **Introduction:**

Online music streaming platforms like **Spotify** have plenty of songs in their repositories. If we can build a **recommendation system** to recommend songs to the users based on their historical interactions with songs, this would improve customer satisfaction. Increased customer satisfaction will **increase the revenue of the company.** The techniques that we will learn here will not only be limited to songs but can be any item for which you can build a recommendation system.

## **Problem Statement:**

In this project, we will build a music recommendation system for the [Million Song Dataset](http://millionsongdataset.com/). Our motivation consists of building an information filter to maintain the attention of users of a Music Platform because of information overload and decisions that they make, avoiding attrition of users using the Music Platform, this is of course undesirable. 

The constraints that we main follows given the data that we have, it's the provision of the characteristics of a small dataset constituted mainly of a small number of user_id and song_id of the universe of possibilities of the Million Song Dataset.

There are many types of recommender systems in use today, so a major component of the project will be in benchmarking models to find the more appropriate recommendation system to propose songs for a user based on the user’s listening activity of a given song set.


## **Objective:**

This project involves recommending the top 10 songs for a user based on the likelihood of listening to those songs using recommendation systems techniques.

## **Data Dictionary:**

The core dataset is the Taste Profile Subset released by The Echo Nest as part of the [Million Song Dataset](http://millionsongdataset.com/). There are two csv files in this dataset count_data and song_data. song_data file of 1,000,000 rows of songs contains the details about the song id, titles, release, artist name, and the year of release. The count_data file of 2,000,000 rows contains the user id, song id, and the play count of users.

**song_data**
* **song_id:** A unique id given to every song
* **title:** Title of the song
* **Release:** Name of the released album
* **Artist_name:** Name of the artist
* **year:** Year of release

**count_data**
* **user _id:** A unique id given to the user
* **song_id:** A unique id given to the song
* **play_count:** Number of times the song was played
