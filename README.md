Movie Recommendation System

This repository contains a Python implementation of a Movie Recommendation System using various libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn.

Overview: Data Loading:

Three data files ('ratings.csv', 'users.csv', 'movies.csv') are loaded. Relevant columns are selected for 'users' and 'movies' dataframes.

Data Exploration:

Displayed the first 5 rows and information about the 'users' and 'movies' dataframes. Visualized a word cloud of movie titles. Printed summary statistics for movie ratings.

Data Analysis:

Used seaborn to visualize the distribution of movie ratings. Printed a list of 20 movies with the highest ratings.

Genre Analysis:

Extracted genre keywords from the 'genres' column in the 'movies' dataframe. Performed content-based filtering using TF-IDF to analyze movie genres. Computed cosine similarity between movies based on genres. User-Item Matrix:

Created user-item matrices for training and testing data.

Movie Recommendations:

Defined a function for recommending movies based on genre similarity. Provided examples of movie recommendations for specific movies.
