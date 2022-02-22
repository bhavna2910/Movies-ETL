# Movies-ETL
## Project Overview
The scope of this project required us to create an automated pipeline that takes in new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data. It then performs the appropriate transformations and loads the data into an existing PostgreSQL database.

For this analysis, we used the following breakdown:

* Write an ETL function to read three data files
* Extract and transform the Wikipedia data
* Extract and transform the Kaggle and rating data
* Load the data to a PostgreSQL Movie Database.

### Resources
* Data Sources: wikipedia-movies.json, movies_metadata.csv, ratings.csv
* Softwares: Python, Anaconda Navigator, Jupyter Notebook, PostgreSQL, pgAdmin

## Results
### Write an ETL function to read three data files
The function takes the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and creates three separate DataFrames.

### Extract and Transform the Wikipedia data
We filtered out the TV shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.

### Extract and Transform the Kaggle and rating data
Again, we consolidated the redundant data, removed the duplicates, formatted and grouped the data.
The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.
