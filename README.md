# Movies ETL
## Project Overview

In this analysis, I created a function that performs the ETL process on three datasets containing movie data. First the function cleans the Wikipedia and Kaggle movie data by transforming the JSON and csv files to Pandas dataframes and then performing necessary operations. Once these two dataframes are properly cleaned, the function merges them into a single movies_df dataframe and drops the columns that display duplicate information. Next, one final merge is executed that adds the ratings information to the movies_df to create the movies_with_ratings_df. The final part of the function uses sqlalchemy to export the movies_df and ratings csv into tables in pgAdmin.

I utilized Python with the Pandas, Numpy and sqlalchemy libraries along with Postgresql and pgAdmin to perform this analysis.

