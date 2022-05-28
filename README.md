# Module 8: Movies_ETL

## Overview and purpose:

The purpose of this project is to create an automated pipeline that extracts, transforms, and loads various data sources into  tables.  This project refactors previous completed code.  The heart of the final code is comprised of a ["clean movie" function](https://github.com/laurlen2112/Movies-ETL/blob/main/resources/clean_movie_func.png) and an [ETL function](https://github.com/laurlen2112/Movies-ETL/blob/main/resources/ETL%20funct.png).  The ETL function contains several sub-functions, including one to [parse dollars](https://github.com/laurlen2112/Movies-ETL/blob/main/resources/parse_dollars.png) from the data and another [to fill missing data](https://github.com/laurlen2112/Movies-ETL/blob/main/resources/fill_kaggle_data.png).  Additionally, the ETL function contains code to [load the cleaned data to PostgreSQL](https://github.com/laurlen2112/Movies-ETL/blob/main/resources/SQL.png). 
