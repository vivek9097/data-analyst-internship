# Data cleaning task performed
1. handled missing values
   identify null values uning .isnull()
   filled missing values with "unknown" in director,cast and country column
   and "N/A' in rating,duration and date_added column
2. remove dublicate rows
   used .drop_dublicates() to remove dublicates
3. standardised text data
4. convert date formate
   ensured all date values follow a consistent dd-mm-yyyy formate using pd.to_datetime()
5. rename column headers
6. checked and fixed data types
   convert column date_added to datetime
