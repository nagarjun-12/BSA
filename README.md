Bank Statement Aggregator

--Project Overview--
Bank Statement Aggregator is a Java-based application that automates the process of collecting, processing, and managing bank statements. The application retrieves CSV-formatted bank statements from AWS S3 using AWSClient, processes the transactions, and stores them in a MySQL database. This helps companies track and manage financial transactions across multiple branches efficiently.

Features
----------
Fetches bank statements stored in AWS S3.
Parses and processes transaction data from CSV files.
Stores transactions in a MySQL database.
Enables businesses to track and manage statements from multiple branches.
Provides filtering options to retrieve data based on business requirements.
--Tech Stack Used--
Backend: Java, Spring Boot
Cloud Storage: AWS S3
Database: MySQL
Tools & Libraries: AWS SDK, Hibernate/JPA
--Project Workflow--
Bank statements (CSV files) are uploaded to AWS S3.
The application retrieves the files using AWSClient.
Parses the CSV data and processes transactions.
Stores the processed data in MySQL.
Enables businesses to access and analyze financial data efficiently.
--Self-Implemented Aspects--
The statements were generated manually and uploaded to AWS S3.
Retrieved, processed, and stored the data in a database.
Designed and implemented the entire workflow independently.
--Setup & Installation--
Clone the repository:shCopy codegit clone https://github.com/nagarjun-12/BSA.git
Configure AWS S3 credentials in application.properties.
Set up a MySQL database and update the connection details.
Run the application using:shCopy codemvn spring-boot:run 
--Future Enhancements--
Implement a frontend dashboard for real-time statement tracking.
Add authentication and authorization for secure access.
Integrate graphical analytics for financial insights.
