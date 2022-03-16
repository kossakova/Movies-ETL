# Extract Transform Load 

## Overview of the project 
We have been tasked with creating the datasets for the hackathon that being sponsored by popular video streaming website. Hackathon is an event where teams of analysts collaborate to work intensively on a project, using data to solve a problem. We needed to provide hackathon participants a nice clean data sets to work on to predict which low budget movies being released will become more popular. 

### Resources 
- Python 
- Pandas
- PostgreSQL

## ETL process 
In this project we worked with two data sources: a scrape of Wikipedia for all movies released since 1990 and rating data from the Movie Land’s website.
Our ETL process consisted of three main steps:

- We extracted the Wikipedia and Kaggle data from multiple sources such as CSV, web scraping and JSON files

- Transformed it into one clean data set by cleaning them up and joining them together.
We manipulated and cleaned the data before loading it in database, read our data into Pandas and removed null values, duplicates, irrelevant information ana entire columns that weren’t required for our project.

- Finally, loaded clean data set into a SQL database tables.
We used Pandas to_sql method and sqlAlchemy to insert the dataframe into a table within a databas.


### Loading data with PostgreSQL.

![movies_query](https://github.com/kossakova/Movies-ETL/blob/main/Resources/movies_query.png)
![ratings_query](https://github.com/kossakova/Movies-ETL/blob/main/Resources/ratings_query.png)
