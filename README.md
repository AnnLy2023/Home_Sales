# Home_Sales
Module 22 Challenge

For this challenge, we’ll use our knowledge of SparkSQL  to determine key metrics about home sales data. We’ll use Spark to create temporary view, partition the data, cache and uncache a temporary table, and very that the table has been uncached. 

We'll use SparkSQL to answer the following questions:


o	What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

![Alt text](image-1.png)

    
 
o	What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.


![Alt text](image-2.png)
 
o	What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.


![Alt text](image-3.png)
 
o	What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
 

![Alt text](image-5.png)



o   Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

-Comparing to the uncached runtime, the cached is a bit faster at .83 seconds vs. uncached at .89 seconds. 

Uncached             vs                               Cached  
 	 
![Alt text](image-6.png)                    ![Alt text](image-8.png)

o   Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Uncached vs parquet DF 
Uncached DF run time is .89 while Parquet home sales DF only took .57 to run the same query. 
    
![Alt text](image-9.png)                  ![Alt text](image-10.png)