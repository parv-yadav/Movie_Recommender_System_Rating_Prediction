# Movie_Recommender_System_Rating_Prediction
The Main objective of this project was to build a recommender system and create a model through which we can predict what rating can be expected for that movie.

Tools Used: Python (Pandas, Numpy), KNN(Scipy)

Technique: : KNN (k Nearest-Neighbors), Correlation and Data Analysis.

Description:
•	Imported Data from Movie lens and created correlation matrix between every movie based on rating.
•	Movie Rating given by new user’s similar movies were retrieve using correlation matrix. 
•	Correlation score of similar movies were multiplied by the new user rating so that movies that new user 
liked gets high correlation score and it was recommended.
•	Using KNN the movies ratings were predicted by finding 
10/5 movies that were closest to it in terms of popularity and in which category it belongs.  
