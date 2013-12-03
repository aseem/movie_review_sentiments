<h1>CS 109 Final Project<h1>

<h2>movies.dat<h2>
This is a set of movie metadata from Movie Lens project.  It can be downloaded here: http://files.grouplens.org/datasets/hetrec2011/

<h2>Movie_Data_Gathering.ipynb<h2>
This is an iPython Notebook.  It takes the movies from movies.data and fetches ~12,000 movie reviews from Rotten Tomatoes and stores the reviews in critics.csv.  It then goes through each review in critics.csv and downloads the original article from where Rotten Tomatoes got the review.  It stores the full reviews in articles.csv

<h2>critics.csv<h2>
Contains review quotes from Rotten Tomatoes and links to the original review articles

<h2>articles.csv<h2>
Contains everything in critics.csv plus the text of the original article.  The article has been cleaned up using BoilerPipe to strip any html.

<h2>Data_Cleaning.ipynb<h2>
This is an iPython Notebook that filters out incomplete and/or error review articles.  It outputs the cleaned articles into cleaned_articles.csv

<h2>cleaned_articles.csv<h2>
This is the final data containing the Rotten Tomatoes quote, movie metadata, and the movie review article.  It contains ~8000 reviews.

