# Recommending-Moives-at-Scale
* Understanding how to model preferences from a variety of sources
* Learning how to compute similarities using distance metrics
* Modeling recommendations using matrix factorization for star ratings


## Dataset
* Find the data at http://grouplens.org/datasets/movielens/.
* u.data: This contains the user moving ratings
* u.item: This contains the movie information and other details
* For u.data, the frst column is user ID | the second column is the movie ID | the third is the star rating | last is the timestamp.
* For u.item including the ID, title, release date, and even a URL to IMDB.

## Ingest movie review data
* Create function to import moive reviews, check ```def load_reviews```
* Create function to load moive information, check ```def load_moives```
* Create class that will be augmented  ```class MoiveLens(Object)```
* 

## Findhest-score moives

## Improve movie-rating system

## Measure distance between users in preference space

## Compute corelation between users

## Find best critic for users

## Predict movie ratings for users

## Collaboratively fltering item by item

## Build matrix factorization model

## Load entire dataset into memory

## Dump SVD-based model

## Train SVD-based model

## Test SVD-based model




