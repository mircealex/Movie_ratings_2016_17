# Movie_ratings - IMDB, Fandango, Metacritic, RottenTomato s
This repo contains a dataset with movie ratings for 214 of the most popular movies in 2016 and 2017.

The data was up to date on March 22, 2017. Significant changes should be expected mostly for movies released in 2017.


Column | Description
--- | ---------
movie | the name of the movie
year | the release year of the movie
metascore | the Metacritic rating of the movie (the "metascore" - critic score)
imdb | the IMDB rating of the movie (user score)
tmeter | the Rotten Tomatoes rating of the movie (the "tomatometer" - critic score)
audience | the Rotten Tomatoes rating of the movie (user score)
fandango | the Fandango rating of the movie (user score)
n_metascore | the metascore normalized to a 0-5 scale
n_imdb | the IMDB rating normalized to a 0-5 scale
n_tmeter | the tomatometer normalized to a 0-5 scale
n_audience | the Rotten Tomatoes user score normalized to a 0-5 scale
nr_metascore | the metascore normalized to a 0-5 scale and rounded to the nearest 0.5
nr_imdb | the IMDB rating normalized to a 0-5 scale and rounded to the nearest 0.5
nr_tmeter | the tomatometer normalized to a 0-5 scale and rounded to the nearest 0.5
nr_audience | the Rotten Tomatoes user score normalized to a 0-5 scale and rounded to the nearest 0.5
