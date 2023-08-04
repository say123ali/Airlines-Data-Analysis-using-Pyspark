# Airlines-Data-Analysis-using-Pyspark
About Dataset The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics (BTS) tracks the on-time performance of domestic flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled and diverted flights appears in DOT's monthly Air Travel Consumer Report, published about 30 days after the month's end, as well as in summary tables posted on this website. BTS began collecting details on the causes of flight delays in June 2003. Summary statistics and raw data are made available to the public at the time the Air Travel Consumer Report is released.


1. Create a DF(airlines_1987_to_2008) from this path

          %fs ls dbfs:/databricks-datasets/asa/airlines/

          (There are csv files in airlines folder. It contains 1987.csv to  2008.csv files. 

          Create only one DF from all the files )

2. Create a PySpark Datatypes schema for the above DF

3. View the dataframe

4. Return count of records in dataframe

5. Select the columns - Origin, Dest and Distance

6. Filtering data with 'where' method, where Year = 2001

7. Create a new dataframe (airlines_1987_to_2008_drop_DayofMonth) exluding dropped column (“DayofMonth”) 

8. Display new DataFrame

9. Create column 'Weekend' and a new dataframe(AddNewColumn) and display

10. Cast ActualElapsedTime column to integer and use printschema to verify

11. Rename 'DepTime' to 'DepartureTime'

12. Drop duplicate rows based on Year and Month and Create new df (Drop Rows)

13. Display Sort by descending order for Year Column using sort()

14. Group data according to Origin and returning count

15. Group data according to dest and finding maximum value for each 'Dest'

16. Write data in Delta format
