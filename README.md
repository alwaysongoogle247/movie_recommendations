# movie_recommendations

## Outline


## Business Problem 

We were contracted by a small video streaming startup called “Lackluster Video” that has tasked us with creating a model that will return the top 5 movie recommendations for users based on the ratings. 

## About the Data

For this project, we will be using the small MovieLens dataset from the GroupLens research lab at the University of Minnesota. The small dataset contains 100,836 ratings of 9742 movies varying in genre. Below you can see the counts by ratings. 

The following graph shows that the more popular a movie is the higher the rating it receives 


## Technologies and Packages Used

Pandas
Numpy
Seaborn
Surprise 
Scipy

## Conclusions

We developed two models,  KNN and SVD. We ultimately chose the SVD model because it performed better with a ___ RMSE score.  Then we used Gridsearch to identify the best parameters (n_factors = 10, n_epochs = 20, lr_all = .006, reg_all= 0.4) to fit the model. Finally, a function was created to return the top 5 recommended movies for users. 
