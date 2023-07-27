# MonthlyRetailTrade-ETL-DataAnalysis-Viz
The objective of the project was to develop an ETL process, Analyse and visualize the Monthly Retail Trade Survey dataset from the U.S Census Bureau. The dataset provides comprehensive data on retail economic activity in the United States. The dataset contained data from 1992 to Feb 2021. <br>
The process involved
- Taking a deep dive into the dataset, researching, and collecting further information such as the hierarchy of NAICS codes.
- Extracting the dataset from the provided Excel workbook and generating a draft of the schema for Mysql tables that would have a user-friendly and efficient design.
- Transforming the dataset using pandas data frames which included excluding the extraneous columns and rows and replacing the missing values in sales.
- Testing the MySQL to Python connection.
- Loading the dataset into separate MYSQL tables, followed by data validation
- Querying the database using conditional statements, and aggregating columns to collect data for further analysis and visualization
- Examining trends, percentage of changes, rolling time trends, and visualization.

Using the MRTS Dataset, we could generate an ETL process that fetches the dataset, transforms it, and creates and loads the data into the database. This Python script lays the groundwork for automating the whole process and can be run using a Windows task scheduler or cron on Mac to automate the process in case the dataset is periodically updated.
