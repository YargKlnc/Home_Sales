# Home Sales Analysis
by YK

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/10b97996-be33-44fe-90fc-9ece4573cd80)


**Background**

Determining key metrics about home sales data Using SparkSQL. Using Spark to create temporary views, partition the data, cache and uncache a temporary table, and verifying that the table has been uncached.


**Instructions**

1. The Home_Sales_starter_code.ipynb file was renamed to Home_Sales.ipynb

2. Necessary PySpark SQL functions were imported for this assignment

3. The home_sales_revised.csv data in the starter code was read into a Spark DataFrame

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/abf97de8-c7bf-466e-b5c0-4c543d993818)

4. A temporary table named home_sales was created

5. **Following questions answered using SparkSQL:**

   - Average price for a four-bedroom house sold for each year was calculated and rounded off to two decimal places

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/c1632b85-08bb-4951-8fbe-c40bf0230503)

   - Average price of a home for each year it was built, with three bedrooms and three bathrooms, was calculated and rounded off to two decimal places

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/2b0d1b00-5191-4e79-8868-57c663cc7b09)

   - Average price of a home for each year, with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet, was calculated and rounded off to two decimal places

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/fb810b63-a6b0-48c7-9c8c-5ace36c9bac4)

   - "View" rating for homes costing more than or equal to $350,000 was determined, and the run time for this query was rounded off to two decimal places

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/3d0569ad-9673-408c-8056-6432c9e317ee)

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/f1ec1ca6-b3dc-4d90-817d-2eb124b19067)

7. Temporary table home_sales was cached

8. Checked if the temporary table home_sales was cached

9. Using the cached data, a query was run to filter out view ratings with an average price greater than or equal to $350,000. The runtime was determined and compared to uncached runtime

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/17362e0f-99b6-449b-ad4e-e100dcaffb48)

10. The formatted parquet home sales data was partitioned by the "date_built" field

11. A temporary table for the parquet data was created

12. A query was run to filter out view ratings with an average price greater than or equal to $350,000. The runtime was determined and compared to uncached runtime

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/b4727b64-792d-409c-aa7f-72c6103e8be9)

13. The home_sales temporary table was uncached.

14. Verified that the home_sales temporary table was uncached using PySpark.

15. The Home_Sales.ipynb file was downloaded and uploaded into the "Home_Sales" GitHub repository.


**Results**

Runtime for query, rounded off to two decimal places as below:

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/f1ec1ca6-b3dc-4d90-817d-2eb124b19067)

Runtime decreased significantly compared to cached runtime as below:

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/17362e0f-99b6-449b-ad4e-e100dcaffb48)

Parquet Runtime increased compared to uncached runtime as below:

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/b4727b64-792d-409c-aa7f-72c6103e8be9)


**References**

Head photo rights: https://www.mygreatlearning.com/blog/big-data-analytics/
