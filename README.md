# movie_recommendations

![alt text](https://github.com/alwaysongoogle247/movie_recommendations/blob/main/Images/3e45a34c4808c6122a817a7e6fc431a7.jpg)

## Business Problem 

We were contracted by a small video streaming startup called “Lackluster Video” that has tasked us with creating a model that will return the top 5 movie recommendations for users based on the ratings. 

## About the Data

For this project, we will be using the small MovieLens dataset from the GroupLens research lab at the University of Minnesota. The small dataset contains 100,836 ratings of 9742 movies varying in genre. Below you can see the counts by ratings. 


## Technologies and Packages Used

Pandas

Numpy

Seaborn

Surprise 

Scipy

## Conclusions

We developed two models,  KNN and SVD. We ultimately chose the SVD model because it performed better with a .88 RMSE score.  Then we used Gridsearch to identify the best parameters (n_factors = 10, n_epochs = 20, lr_all = .006, reg_all= 0.4) to fit the model. Finally, a function was created to return the top 5 recommended movies for users. 
