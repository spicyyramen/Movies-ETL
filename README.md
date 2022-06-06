# Movies ETL
Automated pipeline to intake Wikipedia data, Kaggle metadata, and MovieLens rating data and perform ETL by adding data to PostgreSQL database.

## Reading in the Data Files 
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

## 