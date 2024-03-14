# SOEN471-Project
## Describe the dataset and main characteristics (number and type of features)
The dataset represents the characteristics of movies. 
In total, there are 7 features to the dataset. 

The title feature is a string type which represents the name of the movie, 
The year feature is an integer type that represents the year of release of the movie, 
The runtime feature is an integer type which represents the length of the movie in minutes
The genre feature is a string type that represents the category of the movie and is the prediction label
The director feature is a string type that represents the person who directed the film, 
The writer feature is a string type that represents the person who wrote the film, 
The ratings feature is a floating-point number type that represents the weighted average of the movie ratings, 
The star1 feature is a string type that represents the name of the first star of the movie,
The star2 feature is a string type that represents the name of the second star of the movie,
The star3 feature is of string type that represents the name of the third star of the movie, 
The star4 feature is a string type that represents the name of the fourth star of the movie. 

## The research questions to be addressed in the project
Can we predict the movie genre?  

Which feature is most important to precisely predict the movie genre?

How can we use KNN on non-numerical data?  

## The class of models to be applied to the dataset
The class of models that will be applied to the dataset are supervised learning models since we are predicting features that are labeled.


## Algorithms
The Decision Tree algorithm will be used. The Decision Tree algorithm will be used because it is a supervised classification algorithm. The Decision Tree algorithm can handle both numerical and categorical data. However, decision trees can suffer from overfitting. 
The Random Forest algorithm will be used. The Random Forest algorithm will be used because it is a supervised classification algorithm. The algorithm will avoid the problem of overfitting the training set. Furthermore, the algorithm can easily be parallelized, reducing the time to train the model.

The K-Nearest Neighbors algorithm will be used. The K-Nearest Neighbors algorithm will be used because it is a supervised classification algorithm. However, cross-validation will need to be performed to choose k. Moreover, careful thought will need to be put into choosing a distance metric since a lot of our data is string-based. 

