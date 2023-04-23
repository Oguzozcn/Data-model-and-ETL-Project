# Data model and ETL Project
### ERD
![](https://github.com/Oguzozcn/Data-model-and-ETL-Project/blob/main/ERD.jpg)


Data Model Project:

1) Installed postgresql database adapter for Python psycopg2.
2) Created a connection to database
3) Get cursor to execute queries
4) Setted automatic commit
5) Created database inside cursor execute (my_db)
6) Connected the database that created after closed previous one (postgres)
7) Created table for students includes columns according to their type
8) Insert into these table some rows
9) Validating data if its working and columns with rows inserted properly
10) Closing cursor and connection

Data Engineer Project:
1) Imported libraries for dataframe creating and for database usage
2) Defined create database function to create a sparkify database with utf8 encoding where we can use wide range of characters
3) Defined drop, create functions with execution and commiting
4) Reading .csv files and checking column head and types
5) Cleaning datas and creating necessary dataframes (also according to the business schema ERD(Entity Relationship Diagram) design)
6) Called create database function and executed Table creating for accountscountry, accountsdata and accountseries.
7) Inserted value types and then inserted every row cleaned dataframes (such as AccountsCountry_clean)
8) Dropped NA and noticed '..' in year so replaced with nan also in AccountsData_clean

