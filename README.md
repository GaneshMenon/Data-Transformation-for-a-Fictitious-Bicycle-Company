# Data-Transformation-for-a-Fictitious-Bicycle-Company

Project Overview:
In this Datacamp project, I worked on transforming and preparing data for a fictitious bicycle company using Alteryx Designer. The main focus was understanding the roles of Unions, Appends, Joins, and Parsing tools to clean and merge multiple datasets effectively.

Key Learnings
🔹 Unions and Appends:
I learned how to use the Union tool to combine multiple datasets vertically by aligning fields manually or by name.
 I used Append Fields to join every record of one dataset with every record of another, deepening my understanding of many-to-many data blending.

Example:
 I combined sales and customer feedback data using Union to create a unified performance report.

🔹 Join Types:
 I explored different Join types in Alteryx:

Inner Join: Records matching on keys in both datasets.

Left Join: All records from the left dataset, matched records from the right.

Right Join: All records from the right dataset, matched records from the left.

Full Outer Join: All records from both datasets.

Cartesian Join: Every record from the left joins to every record from the right, without keys.

Example:
 I used an Inner Join to match bicycle sales orders with customer profiles based on Customer ID.

🔹 Application of Tools:

Join to merge customer and order data.

Union to stack multiple quarterly sales files.

Wildcard entries to dynamically read multiple CSV files from a folder without manually selecting each one.

Example:
 I used a wildcard input like Q*_Sales.csv to automatically load all quarterly sales data.

🔹 Parsing and Data Interpretation:
 I deep-dived into Parsing tools to clean and transform data:

String Parsing: Splitting complex product names into individual attributes.

Date/Time Parsing: Converting text-formatted dates into Alteryx DateTime format.

Advanced Parsing: Handling mixed data formats and inconsistencies.

Example:
I parsed product descriptions using Text to Columns and standardized sales dates using DateTime tools.

Tools Used:
I utilized the following tools:

Text Input: To manually input small datasets for testing.

Text to Columns: To split product details.

DateTime Tool: To clean and standardize date fields.
