#CS 109 Final Project

##movies.dat
This is a set of movie metadata from Movie Lens project.  It can be downloaded here: http://files.grouplens.org/datasets/hetrec2011/

##Movie_Data_Gathering.ipynb
This is an iPython Notebook.  It takes the movies from movies.data and fetches ~12,000 movie reviews from Rotten Tomatoes and stores the reviews in critics.csv.  It then goes through each review in critics.csv and downloads the original article from where Rotten Tomatoes got the review.  It stores the full reviews in articles.csv

##critics.csv
Contains review quotes from Rotten Tomatoes and links to the original review articles

##articles.csv
Contains everything in critics.csv plus the text of the original article.  The article has been cleaned up using BoilerPipe to strip any html.

##Data_Cleaning.ipynb
This is an iPython Notebook that filters out incomplete and/or error review articles.  It outputs the cleaned articles into cleaned_articles.csv

##cleaned_articles.csv
This is the final data containing the Rotten Tomatoes quote, movie metadata, and the movie review article.  It contains ~8000 reviews.

