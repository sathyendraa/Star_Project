# Star_Project

The Data flow diagram explains the client requirement in a high-level architectural format which can be executed in sequential order.

The App and Spark Configuration files are required to minimize the hard coding in the main files and the values of the variables are fetched from these at the time of 
execution.

The Spark Job file is the main file that contains all the data, and the tasks are done on the data based on the order given in the DAG file. 

Buildspec is a YAML file to automate this process in AWS Codecommit tool.

Various AWS tools were used to complete this project

Tools Used in AWS: S3, IAM Policies, EMR, EC2, Airflow, Livy, Lambda, AWS Codecommit.
