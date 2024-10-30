## Customer Segmentation Project
For this project, we will be working with  online_transactions_cleaned table we have been querying from redshift.

This is the dataset where we carried out a series of transformations  and built an ETL pipeline  that cleans the data.

A sales analysis via Tableau is also available.

This ETL pipeline is in my [repository](https://github.com/nadiasao/ETL_pipeline_docker)

For this project we carried out following tasks:

 #### Part1: Analysing and visualizing
    -statistical summary
    -Checking the missing values
    -Checking the data types
    -Investigating the negativ values of quantity
    -the top ten most popular geographical locations 
    -Distribution of invoices per year, month, weekday and datetime using sql query
#### Part2: RFM Analysis & K-Means Clustering:    
    -Calculate RFM score by adding the individual scores
    -Calculate RFM score by combining the individual scores
    -Customer segmentation with K-means
        -Interpret segments with the average RFM values
        -Interpret segments with the snake plot

## Requirements

#### The minimum requirements:
    AWS Redshift connection details
    Python 3.9 or higher
#### Instructions on how to execute the code
Copy the .env.example file to .env and fill out the environment variables.
