# Movies--ETL
Module 8 ETL practice

## General Purpose
The primary task in this analysis was to load, clean, and store data about movies.
The file movie_cleaning.ipynb holds the module's initial work, in which tasks related to cleaning the data were carried out in discrete steps.
Steps taken included removing columns that were mostly empty, reformatting numerical data, and merging information about alternate titles.

## Challenge Deliverables
- [The function test file](ETL_function_test.ipynb) contains the code for cleaning up the columns for an individual movie.
- [The wiki movie cleaning file](ETL_clean_wiki_movies.ipynb) shows the process of loading movie data from Wikipedia and converting the columns.
- [The Kaggle cleaning file](ETL_clean_kaggle_data.ipynb) merges the Wikipedia data with additional information and ratings from Kaggle.
- [The database creation file](ETL_create_database.ipynb) holds the code for uploading the resulting DataFrames into a database.
- The Resources folder holds queries that show the number of entries in the resulting databases.
