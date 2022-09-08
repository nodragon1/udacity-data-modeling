### 1. Discuss the purpose of this database

Their purpose of this database is getting results with simpler queries.
With the results, they analyze it and figure out what songs each user like.

### 2. How to run the Python scripts

1. complete CREATE and DROP in sql_queries.py
2. run create_tables.py with terminal
3. complete INSERT in sql_queries.py
4. get the dataset and insert values into tables in etl.ipynb
5. check if the tables have proper values in test.ipynb
6. complete etl.py
7. re-run create_tables.py and run etl.py
8. same with 4
9. set constraints and conflict in sql_queries.py
10. check the condition of contraints and conflict

### 3. Explanations of the files in the repository

create_tables.py = create database, tables and drop tables
etl.ipynb = build etl pipeline with dataset(one record)
etl.py = insert all the values into the tables
sql_queries.py = organize queries needed
test.ipynb = check if processes go well

### 4. Database schema design and ETL pipeline

<center>
  <img
    src="erd.png"
    width="700"
    height="1400"
  />
</center>