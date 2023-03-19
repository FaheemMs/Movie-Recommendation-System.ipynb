# Movie-Recommendation-System.py
The code starts with importing of libraries.
And the dataset taken is movies.csv that is comprising a total of 4803 rows and 24 columns.
movies_data.head()
This line is used to print the first 5 rows of the dataframe
Selected features list is used for selecting the relevant features for recommendation.
Combined features combines all featues with the selected features.
This project uses the vectorization technique in which each and every movie is considered as a single vector .
To find the most relevant movies, to a seleted movie, the smimlarity is found using cosine_similarity.
By taking a movie name as input from the user,  We try to find all movie titles that has closest match to the given title and similarity score is also determined.
Now all the relevant movies with similarity score in descending order are printed.
