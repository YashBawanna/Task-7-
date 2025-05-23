📝 Steps to Analyze Sales Data Using SQL and Python
1. Check for Existing Database
Verify if the SQLite database file (sales_data.db) already exists.

If it doesn’t exist, proceed to create the database and insert sample data.

2. Connect to the SQLite Database
Establish a connection to the database.

Use a cursor to execute SQL commands.

3. Create a Table and Insert Sample Data (If Needed)
Create a sales table with columns for product name, quantity sold, and price.

Insert a few sample rows for products like Apples, Bananas, and Oranges.

4. Run SQL Queries
a. Query 1 – Product-Wise Sales Summary
Calculate total quantity sold and total revenue for each product.

Group the results by product name.

b. Query 2 – Overall Sales Totals
Compute the overall quantity sold and overall revenue (all products combined).

c. Query 3 – Average Price per Product
Calculate the average price for each product.

Useful when the same product is sold at different prices.

5. Close the Database Connection
Safely close the connection to the database once all queries are completed.

6. Display the Results
Print the results of all three SQL queries to the console using tables.

7. Create and Display a Bar Chart
Generate a simple bar chart showing revenue by product.

Label the axes and title.

Save the chart as an image file.

Display the chart using a Python plotting library (like matplotlib).

