# crowdfunding_ETL

For Project 2, completed the ETL mini project. Find all resources and outputs in the folders above.
Here is a summary of my code process for each data set.

### Crowdfunding:

- Extract crowdfunding data, create category and subcategory ids using list comprehensions, and create new dataframes with this data
- Export category and subcategory files as csv

### Campaign:

- Make a copy of crowdfunding data and transform by changing data types and renaming columns 
- Merge with category & subcategory dataframes and drop unwanted columns

### Contacts:

- Extract unorganised data from the contacts file
- Use Pandas and Json to create a dataframe from rows of dictionaries
- Split the name column into first & last names 
- Export as a csv


# Postgres

- Create an ERD for all csv files created after extracting and transforming data above
- Create relationships between the files including primary & foreign keys
- Save the schema and create respective tables
- Import the files into tables created using Postgres 