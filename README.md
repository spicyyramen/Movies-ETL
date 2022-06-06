# Movies ETL
Automated pipeline to intake Wikipedia data, Kaggle metadata, and MovieLens rating data and perform ETL by adding data to PostgreSQL database.

## Write ETL Function to Read in Data Files
Created ETL function to import Wikipedia JSON file, Kaggle metadata file, and MovieLens ratings data file, then transform them into Pandas DataFrames.
<br>

Example Code - ETL function<Br>
![ETL Function Code](./resources/etl-function.png)
<br>

Wikipedia DataFrame<Br>
![Wikipedia DataFrame](./resources/wiki-df.png)
<br>

Kaggle DataFrame<br>
![Kaggle DataFrame](./resources/kaggle-df.png)
<br>

MovieLens Ratings DataFrame<br>
![MovieLens Dataframe](./resources/movielens-df.png)
<br>

## Extract and Transform Wikipedia Data
Using Python, Pandas, ETL, and code refactoring- extracted and transformed Wikipedia data to merge with Kaggle metadata.

<br>
Example Code - ETL Function<br>

![ETL Function](./resources/wiki-etl.png)

<br>
Example Code - Try-Except Statement<br>

![Try-Except Statement](./resources/try-except.png)

<br>
Pandas DataFrame<br>

![Combined DataFrame](./resources/combined-df.png)