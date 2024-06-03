# ETL | SSIS | Telecom Case Study
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

• Number of movements performed for each file.
• Number of records successfully transformed.   
• Number of records rejected.

# Project Values
• Analysis of Business Demands

• Data Creation (Tables and Attributes)

• Data Extraction and Transformation using SSIS Package
  
• Source and Destination Error Handling

• Auditing

# Control Flow
![Screenshot 2024-06-03 015721](https://github.com/A7med-3laa227/Telecome_Case_Study/assets/86737077/0ca58cd6-3df7-4f08-b2d4-d3a995f0e4b6)

# Data Flow
![Screenshot 2024-06-03 020109](https://github.com/A7med-3laa227/Telecome_Case_Study/assets/86737077/ce1f8e34-5aba-47b2-8e43-1740ed8e35cb)
