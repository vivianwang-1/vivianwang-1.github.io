# Title: Predicting IMDb Ratings of New Movies


## Project Description

Nowadays, ratings have become an essential criterion for many to evaluate the quality of a movie. Many would consult rating sites such as IMDb, Rotten Tomatoes, Metacritic, etc. to help them decide on the content they want to watch. Currently, there are many approaches to predicting movie ratings based on a film's post-production factors (such as comments and reviews posted on social media) but not many on predicting ratings of movies that have not been released yet. For my project, I would like to see if it’s possible to train a model (using convolutional neural network?) predicting IMDb ratings for a new movie prior to its theatrical release based on a film's intrinsic factors such as genres, cast/main actors, directors, writers, plot/synopses, budget, runtime, etc. It would also be interesting to explore what are some of the determining factors for a high-rating film (factors that have the strongest predictive power).

I’m thinking of using open-source data such as “The movies dataset” and the “IMDB Movies Dataset” from Kaggle as well as datasets provided on the IMDb website. Possible input features could be cast, directors, production company, genres, runtime, budget, synopses, etc. The prediction objective is the IMDb film ratings. 

Application of this trained NN would be able to a) provide people with more accurate film recommendations prior to theatrical release and b) provide insights to film producers on the potential performance and marketing strategies of a film.



## Project Goals

1. Create/merge datasets for training a CNN (convolutional neural network)
2. Decide on and apply the methods/techniques to train a model to predict IMDb film ratings (other than using CNN and linear regression, some of the methods I’ve seen in similar projects include decision trees and random forest, support vector regression, etc.)
3...
