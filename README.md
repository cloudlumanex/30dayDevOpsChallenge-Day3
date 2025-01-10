# OVERVIEW
This project involves extracting data from an API call and storing it in an AWS S3 bucket. It also includes creating a Glue database, linking it to the S3 bucket, and running queries using Athena.

# Tools:
* Cloud services (AWS S3, AWS Athena, AWS Glue)
* Python
* NBA Game API

# Prerequisites:
* AWS account
* NBA API key

# AWS SERVICES AND FUNCTIONS
* AWS S3 is a versatile cloud storage service used for storing, managing, analyzing, and safeguarding data at any scale. It supports a wide range of use cases, including data lakes, hosting static websites, powering cloud-native and mobile applications, among others.

* AWS Athena is a serverless query service that allows you to run SQL queries directly on data stored in S3, supporting formats like JSON, Parquet, and CSV. Being serverless, it requires no infrastructure setup, making it perfect for ad-hoc analysis and gaining insights without the need for a traditional database. Athena can also be integrated with machine learning tools for predictive analytics tailored to business needs.

* AWS Glue is a serverless data integration service designed to prepare and transform data for analytics. It offers tools for ETL (Extract, Transform, Load) tasks and provides a Data Catalog for effective metadata management. Glue simplifies building data pipelines, automates data transformation, and helps clean and structure raw datasets stored in S3 or other sources, making them ready for analytics.

# STEPS

I created my project locally using VSCode, with the parent folder "30dayDevOpsChallenge" that houses all the folders and files for this project. This includes:

* Policy Directory: Contains the IAM policies for this project.
* ![Screenshot 2025-01-10 052503](https://github.com/user-attachments/assets/1532ace2-952f-4482-84c4-2fe695ff8d66)

* SRC Directory: Contains the environment variables for this project.
* ![Screenshot 2025-01-10 052758](https://github.com/user-attachments/assets/61e73068-999c-421c-8295-443fe921f74c)
* ![Screenshot 2025-01-10 052729](https://github.com/user-attachments/assets/199490c2-e990-4c00-9071-f70eea4800be)
* README File: Documents all information about the project.
* ![Screenshot 2025-01-10 053312](https://github.com/user-attachments/assets/dc5cccd9-4b0c-4587-a850-b6a348a1b976)

* .gitignore: Specifies files that will not be pushed to the remote repository.




