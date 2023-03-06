# Twitter Data Pipeline using Airflow

This is a data pipeline project that uses Airflow to extract tweets from Twitter API, process them using Spark, and store the results in SSMS. The project is intended to demonstrate a basic end-to-end data pipeline using popular tools and technologies.

The pipeline consists of the following components:

1. **Twitter API**: Provides access to the Twitter data. The pipeline will use the tweepy Python library to extract tweets.
2. **Airflow**: A platform to programmatically author, schedule, and monitor workflows. We will use Airflow to define and execute the data pipeline tasks.
3. **PySpark**: A fast and general-purpose cluster computing system. We will use Spark to process the tweets and extract the required data.
4. **Amazon S3**: A cloud object storage service. We will use S3 to store the processed data.