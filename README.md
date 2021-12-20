# Moviews-ETL Challenge 
### Purpose
The Movies-ETL Challenge is for Britta to help create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. Britta will need to refactor the code to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.Britta used the following process to accomplish the goal;
* The "process_ETL" function to run through the data pipeline from extraction, transformation, and loading. 
* Wikipedia.movies.json, movies_metadata.csv, and ratings.csv. 
* perform the transformation steps, which include cleaning data from both Wikipedia and Kaggle. 
* Wikipedia and Kaggle Movies datasets are merged into one dataset. 
* The ratings dataset is kept apart. 
* The newly transformed datasets are then loaded into SQL database.

### Deliverable 1 Write an ETL Function to Read Three Data Files
The function converts the Wikipedia JSON file to a Pandas DataFrame, and the DataFrame is displayed in the

![`ETL_function_test.ipynb`](https://github.com/gracemarshall/Movies-ETL/blob/main/ETL_function_test.ipynb)

![`wiki_movies_df.png`](https://github.com/gracemarshall/Movies-ETL/blob/main/Resources/wiki_movies_df.png)

![`kaggle_metadata.png`](https://github.com/gracemarshall/Movies-ETL/blob/main/Resources/kaggle_metadata.png)

![`Ratingd_df.png`](https://github.com/gracemarshall/Movies-ETL/blob/main/Resources/Ratingd_df.png)

### Deliverable 2 Extract and Transform the Wikipedia Data
![`wiki_movesDF_Delivery2.png`](https://github.com/gracemarshall/Movies-ETL/blob/main/Resources/wiki_movesDF_Delivery2.png)

![`wiki_movies_df_columns.png`](https://github.com/gracemarshall/Movies-ETL/blob/main/Resources/wiki_movies_df_columns.png)

### Deliverable 3 Extract and Transform the Kaggle data
![`ETL_clean_kaggle_data.ipynb`](https://github.com/gracemarshall/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb)

![`ETL_clean_wiki_movies.ipynb`](https://github.com/gracemarshall/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb)

### Deliverable 4 Create the Movie Database
![`ETL_create_database.ipynb`](https://github.com/gracemarshall/Movies-ETL/blob/main/ETL_create_database.ipynb)

![`movies_query.png`](https://github.com/gracemarshall/Movies-ETL/blob/main/Resources/movies_query.png)

![`ratings_query.png`](https://github.com/gracemarshall/Movies-ETL/blob/main/Resources/ratings_query.png)

