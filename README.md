# Airflow_Pipeline_OpenWeather
This repository is intended to run an Apache Airflow Pipeline on AWS. Refer the video for project explaination

Explaination Video:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/xTqrX4aIrTM/0.jpg)](https://www.youtube.com/watch?v=xTqrX4aIrTM)

Advantages of using Airflow:
1. It is opensource and hence, there are no costs associating with scheduling jobs i.e. certain code pipelines to perform certain operations, which might be required at a frequent interval.

2. Airflow can be a great option to opt for, if you are not using platforms like Databricks or Snowflake, which have a built-in feature for job scheduling. Airflow does that task for you, with all the different types of triggering mechanisms. 

3. Depending on how the pipeline is designed, airflow can be used to extract data at minimal code input. This pipeline can be integrated with a SQL service, which can later be used with a no-code or low code platform like Zapier, Make or n8n for easier automation setup in the backend.

NOTE:
Instead of AWS, you can run airflow locally as well. Besides, instead of S3, AWS Redshift, Oracle SQL, MongoDB, etc. can also be used.
Certain AWS Dependencies are explained within the video. If these dependencies are not completed, airflow run might be successful and there can be errors.
