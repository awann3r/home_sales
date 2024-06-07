# Big Data Challenge

## Background 
For this challenge, the task is to use SparkSQL to determine key metrics about home sales data. Then use Spark to create temporary views, 
partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Challenge Deliverables
Answer the following questions using SparkSQL:

* What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
  ![img1](https://github.com/awann3r/home_sales/blob/main/images/avg_price_4bedroom.png)

* What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
  ![img2](https://github.com/awann3r/home_sales/blob/main/images/avg_price_3bedroom.png)

* What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
  ![img3](https://github.com/awann3r/home_sales/blob/main/images/avg_price_3bedroom_3bath.png)

* What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
  ![img4](https://github.com/awann3r/home_sales/blob/main/images/view_gt_350k.png)

* Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
  ![img5](https://github.com/awann3r/home_sales/blob/main/images/cached_view_gt_350k.png)

* Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
  ![img6](https://github.com/awann3r/home_sales/blob/main/images/avg_view_gt_350k.png)
