# Recommendations With IMB
## UDACITY - Data Science Nanodegree

### Table of Content
1. [Description](#description)
2. [Project Motivation](#Motivation)
3. [Folder Discription](#Folder)
4. [Getting Started](#getting)
    - [Libraries](#libraries)
    - [Instructions](#instructions)
4. [Results](#result)
5. [Licensing, Authors, and Acknowledgements](#Licensing)

<a name="description"></a>
## Description
This is my Third repo for the "Recommendations with IMB" project in Udacity Data Scientist Nano Degree Program. 

<a name="Motivation"></a>
## Project Motivation
For this project i will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles i think they will like. This project is divided in the following key sections:

### I. Exploratory Data Analysis
        Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

### II. Rank Based Recommendations

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

V. Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.




The motivation behind this project is to potentially build an app to classify real disaster messages. 
This project is divided in the following key sections:
- Processing data, building an ETL pipeline to extract data from source, clean the data and save them in a SQLite DB
- Build a machine learning pipeline to train the which can classify text message in various categories
- Run a web app which can show model results in real time

