# Dissecting Spotify Valence

In this assignment we will dissect Spotify's Valence metric.

Spotify uses a metric called *valence* to measure the happiness of a track. The metric itself, however, was not developed by Spotify. It was originally developed by Echo Nest, a company that was bought by Spotify in 2014. We don't know exactly how valence is calculated. Some details are given by a blog post, which you can find here:

https://web.archive.org/web/20170422195736/http://blog.echonest.com/post/66097438564/plotting-musics-emotional-valence-1950-2013

Our task is to untangle the mystery behind valence and propose how this is derived.

Spotify offers the following information that may be relevant to your task:

* [Get Track's Audio Features](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-audio-features) and [Get Tracks' Audio Features](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features).

* [Get Track's Audio Analysis](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-audio-analysis).



## Part 1: Expore which Track Features Influence Valence

We will use inferential statistic methods to study how track features influence valence. We will find the best possible model for explaining the valence based on the features that you find significant.

## Part 2: Predict Valence

We will use Machine Learning techniques to predict valence based on track features:

* We will use at least three different methods. For each methods we ensure that to tune our hyperparameters as best as we can.

* Once we identify the best method and hyperparameters, we will explain, to the extent that is possible, which features influence the valence metric.

* We will evaluate our predictions on a holdout 20% testing dataset.

* Also, we will evaluate our predictions to a different dataset which we have not use in our training (data/spotify_ids.txt)