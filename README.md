# Spotify-playlist-analysis

## Are the music genres similar between friends?
In this project, I'd like to explore the songs in me and my friend Cindy's Spotify playlists.
Cindy and I have been close friends since college. I know that she mainly listens to Japanese songs, but I prefer English songs.
My guessing is that our music tastes are very different.

I fetched our playlists using Spotify API.
Let's try to answer the question: **Are the music genres similar between friends?**

This project is divided into two parts, presented by two notebooks, this is notebook 1, which contains the following steps:

1. **Data cleaning** (check for variable types, missing data, duplicates in each user's playlist)
2. **Normalization** before drawing the histogram
3. **Data visualization** (histograms, bar plots)
4. Find repeated songs in both playlists
5. **Correlation** between each variables


In notebook 2, we'll try to build a model to predict which user a song should belong to, which contains the following steps:

1. **Feature engineering** (standardization)
2. **Logistic regression** model
3. **Random forest** classifier
4. **Hyperparameters tuning**
5. Conclusions
