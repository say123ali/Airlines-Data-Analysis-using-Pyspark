# Airlines-Data-Analysis-using-Pyspark
1. Create a DF(airlines_1987_to_2008) from this path

          %fs ls dbfs:/databricks-datasets/asa/airlines/

          (There are csv files in airlines folder. It contains 1987.csv to  2008.csv files. 

          Create only one DF from all the files )

2. Create a PySpark Datatypes schema for the above DF

View the dataframe

Return count of records in dataframe

Select the columns - Origin, Dest and Distance

Filtering data with 'where' method, where Year = 2001

 Create a new dataframe (airlines_1987_to_2008_drop_DayofMonth) exluding dropped column (“DayofMonth”) 

Display new DataFrame

Create column 'Weekend' and a new dataframe(AddNewColumn) and display

Cast ActualElapsedTime column to integer and use printschema to verify

Rename 'DepTime' to 'DepartureTime'

Drop duplicate rows based on Year and Month and Create new df (Drop Rows)

Display Sort by descending order for Year Column using sort()

Group data according to Origin and returning count

Group data according to dest and finding maximum value for each 'Dest'

Write data in Delta format
