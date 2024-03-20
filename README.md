# Home_Sales
# Module 22 Home Sales Challenge
This challenge required using SparkSQL to determine key metrics about home sales data and to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

# Requirements
- A Spark DataFrame was created from the dataset.
- A temporary table of the original DataFrame was created.
- A query was written that returns the average price, for a four-bedroom house that was sold in each year.
- A query was written that returns the average price, of a home that has three bedrooms and three bathrooms for each year the home was built.
- A query was written that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year the home was built.
- A query was written that returns the average price of a home per "view" rating having an average home price greater than or equal to $350,000. The output shows the run time for this query.
- A cache of the temporary "home_sales" table was created and validated.
- The query from step 6 was run on the cached temporary table, and the run time was computed.
- A partition of the home sales dataset by the "date_built" field was created, and the formatted parquet data was read.
- A temporary table of the parquet data was created.
- The query from step 6 was run on the parquet temporary table, and the run time was computed.
- The "home_sales" temporary table was uncached and verified.

# Files Included
- Home_Sales_colab_RG - my code that was ran in colag
- Home_Sales_starter_code.ipynb - Jupyter starter code
- Home_Sales_starter_code_colab.ipynb - CoLab starter code

# Resources
I received help from the following

- Instructor - Rufel Estrada
- TA - Manuel Eduardo Sotelo Cervante
- Tutors - Geronimo Perez
