# Netflix New User Movie Reccomendation System
![netflix logo](images/netflix_logo.png)
## Overview

Flatiron School Data Science Phase 4 project Reccomendation Systems.  The goal is to produce 5 reccomendations based on user's ratings of movies.

This project is for educational purposes and Netflix has no actual affiliation with the producer or the results.

## Business Problem

Netflix is looking to improve their recomendation system for new users.  As part of a new trial membership program Netflix is looking to maximize their customer retention by providing the best possible recomendations.  It is important that this new recomendation system will also improve recomendations for existing customers.


## Data Used

data from MovieLens can be found in the 'data' folder
* movies.csv
* ratings.csv
* tags.csv
* links.csv

movies.csv and ratings.csv were used to create the model and make predictions 

Movie rating distribution can be seen below.
![movie rating distribution](images/ratings_dist.png)

Movies used by year
![movies by year](images/movies_by_year.png)
## Final Model

The final model was a Singular Value Decomposition(SVD) using surprise library.  The model was hyper-tuned using the following parameters.


![final model params](images/best_svd.png)

## Model Evaluation
the metric used to evaluate the models was root-mean-square error (RMSE).  Our best model had an RMSE of about .860.



## Deliverables
* [Non-Technical Presentation]()
* [GitHub Repository](https://github.com/ceflynn/Movie-Recommendation-System)
* [Jupyter Notebook](https://github.com/ceflynn/Movie-Recommendation-System/blob/main/student.ipynb)



