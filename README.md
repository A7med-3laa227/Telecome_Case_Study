# ETL | SSIS | Telecome_Case_Study
ETL Telecom Case Study using SQL Server Integration Services (SSIS)
# Project Description
This project for a telecom company successfully addressed several specific requirements:

1️⃣ Real-time File Processing
Files stored in a designated folder are automatically picked up every 5 minutes for processing. The pipeline ensures seamless handling of these files and moves them to the appropriate destination folder after processing.

2️⃣ Input Data Types and Columns
The company provided a table outlining the required data types and columns for the input data. This information is crucial for accurately mapping and transforming the data during the ETL process. Additionally, another table specifies the necessary transformation and data-cleaning steps for the desired output.

3️⃣ Rejected Records
To maintain data integrity, a dedicated table was created in the database to capture any rejected records during the data transformation phase. This allows for easy identification and resolution of data quality issues.

4️⃣ Auditing
An auditing table was implemented to track essential information, such as:

-Number of movements performed for each file.

-Number of records successfully transformed.

-Number of records rejected.

#Project Values
-Analysis Business Demands

-Data Creation (Tables and Attributes)

-Data Extraction and Transforming using SSIS Package

-Source and Destination Error Handling

-Auditing
Refrence:

-Linking the file name with the corresponding auditing information.
