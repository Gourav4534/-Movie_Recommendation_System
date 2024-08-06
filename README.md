# Movie_Recommendation_System

## Project Overview

This project implements a movie recommendation system using Singular Value Decomposition (SVD) from the Surprise library. The system predicts movie ratings for users and provides personalized recommendations based on their historical data.

## Project Structure

- `combined_data_1.txt`: The dataset containing user ratings for movies.
- `movie_titles.csv`: The file containing movie titles and release years.
- `recommendation_system.ipynb`: Jupyter Notebook implementing the recommendation system.
- `README.md`: This file, containing project details and instructions.

## Dataset
### combined_data_1.txt
Link For Dataset Download = https://www.kaggle.com/code/hardboy/recommendation-system-using-svd-on/input
This file contains the user ratings dataset. The format is:

- `Cust_Id`: Unique identifier for each customer.
- `Rating`: Rating given by the customer to a movie.

### movie_titles.csv

This file contains movie titles and their release years. The format is:

- `Movie_Id`: Unique identifier for each movie.
- `Year`: Release year of the movie.
- `Name`: Title of the movie.

## Requirements
To run this project, you'll need to install the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `surprise`
