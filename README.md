# Recommendation System Using (Rank, User-User, Matrix Factorization) on Streaming App



# Project Overview
This project is intended to leverage my skills in data science and apply recommendation_system to a streaming service. The goal of this project is help the company understand different approaches in recommendation_systems in order to implement the models in their products.

# Business Understanding
Do you ever wonder how your friends saw similar movies and none of you recommended it to each other but still all of you saw it? OR everyone on the streaming app saw it!

Let’s take Squid Game for example, we could say, its an incredible show! but what else? what drove every user to make a decision to watch it? The short answer is Recommendation System.

# Intro to Recommendation System:
It is a machine learning algorithm that utilize users’ preferences and historical decisions all together and output a recommendation to each users. Simply, if you like actions movies, you are more likely will be recommended with more action movies from other users that watched action movies. It is by far one of the best features that allow users to make faster decision or relate to other contents based on their previous likings.

Types of Recommendation Systems:
Knowledge Based Recommendation System: Knowledge based are very informative technique that help users make decisions based on specific information about the item characteristics such as using filtering in Amazon to only get Prime Delivery. Also, other technique using Rank-Based recommendation such as Netflix to get top 10 Movies.
Collaborative Filtering Recommendation System: It is another technique that is based on users interactions with other users using similarities with items. There is also a Model Based which is more advanced and using modeling and Machine Learning to validate recommendations to users and how accurate our model perform.
Content Based Recommendation System: Mostly, recommendations are derived from metadata of users and items, and by leveraging item information. For example, user X bought a book and we could use the book contents such as book author, description or genre to find other similar books to the same user X because we could assume that this user is more likely to buy other books similar to these criteria.
# Data Source and download
Now we will try to implementing Recommendation System by applying these techniques with real streaming data Data The data is from Saudi Telecom Company. STC recently shared a new initiative for Open Data for the public. https://lab.stc.com.sa/dataset/en/


# Dataset Description:
## Problem Statement
Recommender systems are among the most popular applications of data science today. They are used to predict “best next action” for a customer or “rating of preference” that a user would give to items. Today, major tech company has applied them in some form or the other. For example, YouTube uses it to decide which video to play next on autoplay, Facebook uses it to recommend pages to like and people to follow, and Amazon uses it to suggest products to customers, and so on. In general, there are three ways to build a recommendation engine:

1. Popularity based recommendation engine
2. Content based recommendation engine
3. Collaborative filtering based recommendation engine Another type of recommendation system is Hybrid model which can be created by mixing two or more types of recommendation systems. This type of recommendation systems usually gives better performance.
STC Lab wants to know how they can use recommendation systems to apply it to their services to enhance user experience

The IPTV dataset contains the following features and it has more than 70 million rows and the size of data is more than 1 terabyte (TB), a sample is provided here:

- User ID
- SESSION START (DATE/TIME)
- SESSION DURATION
- PROGRAM NAME
- PROGRAM DESCRIPTION
- PREOGRAM GENRE
- PROGRAM CLASS
- SERIES TITLE
- SERIES NAME
- Episode title
- Episode number
- Recommendations with STC Data
- In this notebook, I will be putting recommendation techniques to use on real data from the STC OpenData Source.

By following the table of contents, you will find a number of different methods for making recommendations that can be used for different situations.

# How to Run:

Simply download the data from the source https://lab.stc.com.sa/dataset/en/
and run the notebook
