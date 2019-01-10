# PythonDataCollectionAndProcessingCourseProject
Final Project of the Data Collection and Processing with Python. This course is part of the Python 3 Programming Specialization offer by University of Michigan in Coursera. You can find more information at https://www.coursera.org/learn/data-collection-processing-python/home/welcome
## About it
This project will take you through the process of mashing up data from two different APIs to make movie recommendations. The TasteDive API lets you provide a movie (or bands, TV shows, etc.) as a query input, and returns a set of related items. The OMDB API lets you provide a movie title as a query input and get back data about the movie, including scores from various review sites (Rotten Tomatoes, IMDB, etc.).

You will put those two together. You will use TasteDive to get related movies for a whole list of titles. You’ll combine the resulting lists of related movies, and sort them according to their Rotten Tomatoes scores (which will require making API calls to the OMDB API.)

The documentation for the API is at https://tastedive.com/read/api.

The documentation for the API is at https://www.omdbapi.com/

## functions
#### 1. def get_movies_from_tastedive(movieName, key="327878-course3p-I4ZNBN4A"): 
#### IMPORTANT NOTE: You will need a key to get the request for the TasteDive API. For default, I provided my personal key. Please, be careful we that.
It should take two input parameter, a string that is the name of a movie or music artist and the API key's. The function should return the 5 TasteDive results that are associated with that string; rigth now it only get movies, not other kinds of media. It will return a python dictionary with just one key, ‘Similar’.
