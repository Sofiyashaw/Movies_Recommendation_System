Movies Recommendation System

* I developed a personalized movie recommendation system for Diginuque Tech Labs using collaborative filtering techniques. 
* The system analyzes user preferences and provides tailored movie suggestions based on previous interactions, enhancing user engagement and satisfaction

Dataset Description

The dataset used for the movie recommendation system includes a variety of user and movie-related features to build personalized recommendations. The key columns in the dataset are:

* user_id: Unique identifier for each user.
* item_id: Unique identifier for each movie (not used in the current model).
* rating: The rating given by users to movies (used as the target variable in the model).
* timestamp: The time when the rating was made (processed for better model performance).
* age: The age of the user.
* gender: The gender of the user (encoded as binary features).
* occupation: The profession of the user (used to analyze user preferences).
* zip_code: The geographical location of the user, which can offer insights into regional movie preferences.
* movie_title: The title of the movie (used to match user preferences and generate recommendations).
* release_date: The release date of the movie.
The dataset was preprocessed to remove duplicates, handle missing values, and transform categorical variables through techniques like one-hot encoding. The features were used to train a Logistic Regression model to predict movie ratings and generate personalized recommendations.
