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

o	What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places. Compare it to cache and parquet data runtime. 

    - The parquet data runtime is only .21 seconds, comparing to cached data at .27 seconds and uncached data at .34 seconds. 


Uncache Data Runtime 

![avgviewavgpricemorethan35000uncache](https://github.com/AnnLy2023/Home_Sales/assets/129100456/ab934afa-2c2a-4e14-9ddb-7175a9ec29be)


Cache Data Runtime 


![withcacheddata](https://github.com/AnnLy2023/Home_Sales/assets/129100456/34e212dd-e79a-413d-999c-d3cb6cc06eac)


Parquet Data

![parquetdata](https://github.com/AnnLy2023/Home_Sales/assets/129100456/0a645518-d1eb-4cd3-84b2-f0801ee267ec)
