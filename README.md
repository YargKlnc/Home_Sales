# Home Sales Analysis
by YK

![image](https://github.com/YargKlnc/Home_Sales/assets/142269763/10b97996-be33-44fe-90fc-9ece4573cd80)


**Background**

Determining key metrics about home sales data Using SparkSQL. Using Spark to create temporary views, partition the data, cache and uncache a temporary table, and verifying that the table has been uncached.

**Instructions**

1. The Home_Sales_starter_code.ipynb file was renamed to Home_Sales.ipynb.

2. Necessary PySpark SQL functions were imported for this assignment.

3. The home_sales_revised.csv data in the starter code was read into a Spark DataFrame.

4. A temporary table named home_sales was created.

5. **Following questions answered using SparkSQL:**

   - Average price for a four-bedroom house sold for each year was calculated and rounded off to two decimal places.
   - Average price of a home for each year it was built, with three bedrooms and three bathrooms, was calculated and rounded off to two decimal places.
   - Average price of a home for each year, with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet, was calculated and rounded off to two decimal places.
   - "View" rating for homes costing more than or equal to $350,000 was determined, and the run time for this query was rounded off to two decimal places.

6. Temporary table home_sales was cached.

7. Checked if the temporary table home_sales was cached.

8. Using the cached data, a query was run to filter out view ratings with an average price greater than or equal to $350,000. The runtime was determined and compared to uncached runtime.

9. The formatted parquet home sales data was partitioned by the "date_built" field.

10. A temporary table for the parquet data was created.

11. A query was run to filter out view ratings with an average price greater than or equal to $350,000. The runtime was determined and compared to uncached runtime.

12. The home_sales temporary table was uncached.

13. Verified that the home_sales temporary table was uncached using PySpark.

14. The Home_Sales.ipynb file was downloaded and uploaded into the "Home_Sales" GitHub repository.

**References**

Head photo rights: https://www.mygreatlearning.com/blog/big-data-analytics/
