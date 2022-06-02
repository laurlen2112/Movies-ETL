# Module 8: Movies_ETL

## Overview and purpose:

The purpose of this project is to create an automated pipeline that extracts, transforms, and loads various data sources into  tables.  This project refactors previous completed code.  The final code is comprised of a ["clean movie" function](https://github.com/laurlen2112/Movies-ETL/blob/main/resources/clean_movie_func.png) and an [ETL function](https://github.com/laurlen2112/Movies-ETL/blob/main/resources/ETL%20funct.png).  The ETL function contains several sub-functions, including one to [parse dollars](https://github.com/laurlen2112/Movies-ETL/blob/main/resources/parse_dollars.png) from the data and another [to fill missing data](https://github.com/laurlen2112/Movies-ETL/blob/main/resources/fill_kaggle_data.png).  Additionally, the ETL function contains code to [load the cleaned data to PostgreSQL](https://github.com/laurlen2112/Movies-ETL/blob/main/resources/SQL.png). 

This project is comprised of 4 deliverables:
  * [ETL_function_test](https://github.com/laurlen2112/Movies-ETL/blob/main/ETL_function_test.ipynb), which opens three files and converts them to data frames.
  * [ELT_clean_wiki_movies](https://github.com/laurlen2112/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb), which builds on the function created in Deliverable 1 by adding code to clean the data in the wiki movies file.
  * [ETL_clean_kaggle](https://github.com/laurlen2112/Movies-ETL/blob/main/ETL_clean_kaggle_data..ipynb), which includes the previous functionality and adds code to clean the Kaggle file, clean the ratings file, and merge data frames.
  * [ETL_create_databse](https://github.com/laurlen2112/Movies-ETL/blob/main/ETL_create_database.ipynb), which represents the completed state of the function.  This iteration of the function performs all steps above and exports completed files to PostgreSQL.
