# Spotify song recommendation system

This project analyses the dataset obtained using 'spotifyr' package to provide recommendations to users. A Shiny App is created to help provide recommendations based on the genre and / or the artist.

## Data

The [Spotify_data](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-01-21/readme.md) used for this analysis is a contiguous dataset of over 30,000 songs with 
12 audio features for each track, including confidence measures like 
acousticness,liveness, speechiness and instrumentalness, perceptual measures 
like energy, loudness, danceablity and valence (positiveness), and descriptors 
like duration,key, tempo and mode. 

## The approach

A three pronged approach is taken here :

* An overview of the genres and the artists

* An analysis of the track popularity and how it extends aross genres

* Based on the preferences of the user, build a simple system that gives out 
related songs based on genre and / or artist

Several univariate and multivariate analyses are done across variables post 
data preparation to substantiate the findings / results obtained by the above 
approaches

## What can you do with the analysis

* Identify the association between different types of songs 

* As a music aficionado, find the songs that were off your radar

* If you love that genre, get a recommendation for it

* Identify the popular songs, the popularity of artists etc

*Since a song can be associated with multiple genres on Spotify, there may be 
cases of multiple instances of the same song appearing while analysing*
