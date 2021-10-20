# Movies-ETL
# Project Overview
This project was to help Amazing Prime, the world’s largest online retailer, use IMDB data to predict which low-budget movies would become popular. I used Python & Pandas to perform our data wrangling, and PostgreSQL to store the finished data.

## Challenge
- I created an automated pipeline that took in new data (3 files: Wikipedia data, Kaggle metadata, MovieLens rating data), performed the appropriate transformations, and loaded the data into tables in a PostgreSQL database through SQLAlchemy's engine.
- Below are screenshots of 2 queries that retrieve the number of rows for the 2 tables, 'movies' and 'ratings', and their outputs.

![Movies query & output](https://github.com/nhipqnguyen/Movies-ETL/blob/main/Resources/movies_query.png)

![Ratings query & output](https://github.com/nhipqnguyen/Movies-ETL/blob/main/Resources/ratings_query.png)