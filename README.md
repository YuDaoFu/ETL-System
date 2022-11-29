# ETL-System

## Goal

Create a simple Extract, Transform, Load (ETL) pipeline. Then test it by
loading the data and plotting it.

## Conponents
1. schema for the data (data_v2, reference)
2. function that loads data_v2.csv.gz
3. function that loads reference.csv.gz
4. function that validates the data and report any failed checks in a csv file:
    
    a)check_performed, line_number, field, expected_value, actual_value
    
    b)remove any failed rows

5. function that transforms the data by adding the corresponding company name, adding a derived column total_value per
row, and removing unnecessary columns.
6. function that saves the data to a destination:
data_clean.csv
7. function that reports the number of input rows, output rows and error rows.
8. a main function to run the steps.
9. In a separate Python notebook:
    
    a) Load the cleaned csv file.
    
    b) Plot each time series and verify there are no issues.

