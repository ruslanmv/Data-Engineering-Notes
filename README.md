# Data-Engineering-Notes
Data Engineering Notes

1- Data Modeling
In this project we create relational and NoSQL data models to fit the diverse needs of data
consumers. We will use  Postgres and build an ETL pipeline using Python. We  define fact and dimension tables for a star schema for a particular analytic focus, and write an ETL pipeline that transfers data from files in two local directories into these tables in Postgres using Python and SQL.

2-Data Modeling with Cassandra

In this project we will Processing the files to create the data file csv that will be used for Apache Casssandra tables in a ETL Pipeline .





3- Cloud Data Warehouses
We will  create cloud-based data warehouses using Amazon Web Services (AWS)In this project, we will acreate a data warehouse by using AWS and build an ETL pipeline for a database hosted on Redshiftt. In this project we will need to load data from S3 to staging tables on Redshift and execute SQL statements that create the analytics tables from these staging tables.



 4: Spark and Data Lakes
We will use Spark to work with massive datasets. You’ll also learn about how to store big data in a data lake and query it with Spark. In this project we will build an ETL pipeline that extracts their data from the data lake hosted on S3,  processes them using Spark which will be deployed on an EMR cluster using AWS, and load the data back into S3 as a set of dimensional tables in parquet format.
Aim of this project is to create an ETL pipeline using the data stored in S3 buckets and process that data into respective Fact and dimentsion tables using spark and then upload the parquet files back to S3.

5-Data-Pipeline-with-Airflow

We will  schedule, automate, and monitor data pipelines using Apache Airflow.This project will introduce you to the core concepts of Apache Airflow. To complete the project, you will need to create your own custom operators to perform tasks such as staging the data, filling the data warehouse, and running checks on the data as the final step.



