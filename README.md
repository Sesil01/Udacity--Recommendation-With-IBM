# Recommendations With IMB
## UDACITY - Data Science Nanodegree

### Table of Content
1. [Description](#description)
2. [Project Motivation](#Motivation)
3. [Folder Discription](#Folder)
4. [Getting Started](#getting)
    - [Libraries](#libraries)
    - [Instructions](#instructions)
5. [Licensing, Authors, and Acknowledgements](#Licensing)

<a name="description"></a>
## Description
This is my Third repo for the "Recommendations with IMB" project in Udacity Data Scientist Nano Degree Program. 

<a name="Motivation"></a>
## Project Motivation
In the IBM Watson Studio, there is a large collaborative community ecosystem of articles, datasets, notebooks, and other A.I. and ML. assets. Users of the system interact with all of this. Within this scope, Udacity created this recommendation system project to enhance the user experience and connect them with assets. This personalizes the experience for each user.
For this project i will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles i think they will like. 

<a name="Folder"></a>
## Folder Discription

         Recommendations-With-IBM
          |-- data                
                |-- articles_community.csv
                |-- user-item-interactions.csv
                |-- message.csv # data to process
                |-- process_data.py
          |-- Recommendations_with_IBM.html
          |-- Recommendations_with_IMB.ipynb
          |-- Project_test.py
          |-- user_item_matrix.p
          |-- top_10.p
          |-- top_20.p
          |-- top_5.p
          |-- README

<a name="getting"></a>
## Getting Started

<a name="libraries"></a>
### Libraries
The libraries I used for this project were:
- Python 3,
- Matplotlib,
- NumPy, 
- Pandas, 
- Scikit-Learn,
- Pickle

<a name="instructions"></a>
### Instructions:
This project is divided in the following key sections:
#### I. Exploratory Data Analysis
    Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.
#### II. Rank Based Recommendations
    To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
#### III. User-User Based Collaborative Filtering
    In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.
#### IV. Content Based Recommendations (EXTRA - NOT REQUIRED)
    Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.
#### V. Matrix Factorization
    Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.

## Licensing, Authors, and Acknowledgements<a name="Licensing"></a>
-

## Thanks to 
![logo.png](http://pra-dan.github.io/img/udacimak/logo.png)
![IBM.png](https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/IBM_logo.svg/1200px-IBM_logo.svg.png)

