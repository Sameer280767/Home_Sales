# Home_Sales
Module 22 Challenge - DUE 5 June 2023

Home Sales Key Metrics

![House Keys](https://github.com/mugsiemx/Home_Sales/blob/main/Images/pexels-oleksandr-pidvalnyi-7599735.jpg)

In this challenge, we use our knowledge of SparkSQL to determine key metrics about home sales data. Then we use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

   ![](https://github.com/mugsiemx/Home_Sales/blob/main/Images/1_read_in_AWS_S3_bucket.png)
    
# The required questions answered as follows:
First change the data types then sql query for the answers.

   ![](https://github.com/mugsiemx/Home_Sales/blob/main/Images/2_change_data_types_and_create_temp_view.png)

1- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    The average prices for a four bedroom
    house sold by year are as follows:

   ![Avg price of 4 bedroom house](image.png)

2- What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

   ![Avg price 3 brm 3 bath](image-1.png)

3- What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

   ![Avg price 3 brm, 3 bath, 2fl >= 2000sqf](image-2.png)

4- What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

   ![View rating](image-3.png)

   Runtime: --- 0.6633007526397705 seconds ---

Compare the run times for the various methods of running the same sql query as question # 4 above:

   Runtime after cache: --- 0.652350902557373 seconds ---

   Runtime after partioning: --- 0.9011518955230713 seconds ---


