# investigate-a-dataset
In this project, I've analyzed a dataset and communicated my findings about it. I used the Python libraries NumPy, Pandas, and Matplotlib to do the analysis

This Python script is used to explore TMDb movie data. But what determines if a movie is considered as good or bad? There could be several factors influencig the quality of a movie, as for example the budget, genre, etc. This little project helped the author to improve his data analytics skills and explore some of the success criteria for movies.

First some Data Wrangling was applied, before the data was cleaned in order to perform Exploratory Data Analysis.

How to run the script
You can run the script using a Python integrated development environment (IDE). This script is written in Python 3, so you will need the Python 3 version of the installer. The code was written in Jupyter Notebook.

Datasets
This data-set contains information more than 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters. The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

### Variables:

id
imdb_id
popularity
budget
revenue
original_title
cast
homepage
director
tagline
keywords
overview
runtime
genres
production_companies
release_date
vote_count
vote_average
release_year
budget_adj
revenue_adj
Files
tmdb-movies.csv

#### ## Questions to answer
- Which genres are most popular from year to year ?
- Did movies with higher vote count received a better rating ?
- How did the amount of produced films changed over time?
- Does the high budget affects the revenue ?

## Conclusions

##### Which genres are most popular from year to year ?

- We see that the most produced movies were (Drama and Comedy) in spite of the most votes were not none of them so from this we can change our interest in producing Drama and Comedy and go to produced other kind of movies that watchers voted to them such as : "Documentary", "Music" and "Crime"

##### Did movies with higher vote count received a better rating ?

- There's no correlation between the number of votes and the better rating so when the number of votes increase the rating acts as the same

##### How did the amount of produced films changed over time?

- The number of movies that have produced from 1960 to 2015 were increasing remarkably so in 1970 the produced movies were almost 40 in spite of in 2014 were at least 700 so in the past the budget or the watchers of the movies were not have the culture of cinema but now it has changed 

##### Does the high budget affects the revenue ?
- Not nessecary for the high budget to has a high revenue we see from 1960 to 1997 the budget was low compared to after 1997 and after 1997 to 2015 the budget started to be increased and we notice that the revenues started to increased also that maybe because in the past the culture of the cinema and movies were not exist 
