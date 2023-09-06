# Home_Sales
Module 22 Challenge

For this challenge, we’ll use our knowledge of SparkSQL  to determine key metrics about home sales data. We’ll use Spark to create temporary view, partition the data, cache and uncache a temporary table, and very that the table has been uncached. 

We'll use SparkSQL to answer the following questions:


o	What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

    
 ![image](https://github.com/AnnLy2023/Home_Sales/assets/129100456/998c4551-6af5-4268-9914-27cfe2f0cb66)

o	What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

![image-2](https://github.com/AnnLy2023/Home_Sales/assets/129100456/20287909-9549-4a89-9e2d-47e9a865008a)

o	What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

 ![image-3](https://github.com/AnnLy2023/Home_Sales/assets/129100456/5ff1ae4a-0e5f-4e0d-900b-b0b3b34998e8)

o	What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
 
![image-5](https://github.com/AnnLy2023/Home_Sales/assets/129100456/7e23da0f-7f28-44f5-990d-1557cebe8b13)

o   Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

-Comparing to the uncached runtime, the cached is a bit faster at .83 seconds vs. uncached at .89 seconds. 

Uncached             vs                               Cached  
 	 
![image-6](https://github.com/AnnLy2023/Home_Sales/assets/129100456/16092993-aeb4-485d-a102-96dc025565cd)
![image-8](https://github.com/AnnLy2023/Home_Sales/assets/129100456/6f092cb1-e667-4d24-aedf-88b06503bf59)



o   Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Uncached vs parquet DF 
Uncached DF run time is .89 while Parquet home sales DF only took .57 to run the same query. 
    
![image-9](https://github.com/AnnLy2023/Home_Sales/assets/129100456/2a0066aa-d41c-4be1-95fc-3074c32edad9)
![image-10](https://github.com/AnnLy2023/Home_Sales/assets/129100456/66d7033b-51b1-434d-8dd0-e8185402641f)
