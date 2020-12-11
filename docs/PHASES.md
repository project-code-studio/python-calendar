# PHASES

The different phases are described below.

## PHASE 1 (v1.0.0)

- create 2020.csv
- find the holidays for 2020 and store in this csv file
  - have some pre-defined column structure
  - (holiday_name, data, time, day)
- read holidays (_`possibly use dataframes for now, since they are easier to manipulate with csv`_)
- print holidays

## PHASE 2 (v1.1.0)

- get date and time as input from user
- search for holiday in the csv
- print
  - the holiday if it exists
  - otherwise "No holidays found for the given input"

## PHASE 3 (v1.2.0)

- improve the data that we have
  - add more csv files
  - possibly have csv files for 2018-2023
- change the program so as to take year also as an input(_`use custom functions wherever necessary`_)

## PHASE 4 (v2.0.0)

- move the csv files to a database
- create tables in the database and read the files from the database
- find a database which is free for dev
- use `psycopg2` or `sqlalchemy` as the helper dependancies
- make appropriate changes to the codebase (_`we might not want dataframes anymore since we can already filter data in the database itself. convert them to dictionaries`_)

## PHASE 5 (v2.1.0)

- improve the program to take 2 dates as input and print the holidays between them
- these dates can be between dates in 2 years or in the same year
