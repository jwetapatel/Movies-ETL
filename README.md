# Movies-ETL

# Extract, Transform, Load

## Purpose

1. Create an ETL pipeline from raw data to a SQL database.
2. Extract data from disparate sources using Python.
3. Clean and transform data using Pandas.
4. Use regular expressions (Regex) to parse data and to transform text into numbers.
5. Load data with PostgreSQL and verify in PgAdmin.

The project included extracting a large data set from Kaggle, then transforming the data into a usable dataset for a "hacking competition." Once the data was transformed and narrowed in scope for the hack-a-thon, the DataFrames were loaded into PostgresSQL.

# Results

## Deliverable 1 : Write an ETL Function to Read Three Data Files

Wikipedia Movies JSON file, starting with 193 Columns:

<img width="541" alt="d1_1wiki_movies" src="https://user-images.githubusercontent.com/96400887/173410284-48b52088-05b7-4cbe-a9c8-2ec9d1a4c5ae.png">

Kaggle Movie Metadata, 24 columns

<img width="540" alt="d1_2kaggle_metadata" src="https://user-images.githubusercontent.com/96400887/173410308-464c544b-9ce1-4240-b08f-fb6e8e53e889.png">

Kaggle Ratings data, 2602489 rows by 4 columns

<img width="217" alt="d1_3ratings" src="https://user-images.githubusercontent.com/96400887/173410332-82913419-2edb-414c-b7ec-dfd9a09936f8.png">

## Deliverable 2: Extract and Transform the Wikipedia Data

Wikipedia Movies transformed, 23 columns

![d2_1 wiki_movie](https://user-images.githubusercontent.com/96400887/173412008-82e41938-80c1-4d87-865b-8a2a1842430f.png)

Wikipedia Movies, making the column names more succinct and uniform, 7033 rows of data.

![d2_2 wiki movie_columns](https://user-images.githubusercontent.com/96400887/173412218-0104fe4a-5fb7-415d-83d5-40781c5e7046.png)

## Deliverable 3: Extract and Transform the Kaggle data

movies_with_ratings_df DataFrame 41 columns

![d3_1 wiki_movie_ratings](https://user-images.githubusercontent.com/96400887/173412305-2d5b74a8-d37f-49ac-a09f-36ddaffef59c.png)

Movie dataFrame 31 columns

![d3_2 movie_df](https://user-images.githubusercontent.com/96400887/173412333-7241f690-0a57-4fd8-a187-43195c45cf21.png)

## Deliverable 4: Create the Movie Database













