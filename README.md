Realtime Data Analytics Using Apache Spark
Overview
This project builds a real-time social media analytics pipeline using Apache Spark, Python, and Kafka. It leverages Spark functionalities (SparkSQL, Spark Streaming, and MLlib) to train machine learning models via slow batch processing and applies them to real-time streaming data for fast predictions.

Data Sources
The pipeline ingests both historical and streaming data via APIs from the following platforms:

Twitter: Twitter Apps API

MeetUp: Meetup API

GitHub: GitHub Developer API

Tech Stack & Tools
Core Framework: Apache Spark (SparkSQL, Spark Streaming, Spark MLlib, GraphX)

Messaging: Apache Kafka

Environment: DataBricks Community Edition, Anaconda (Python 2.7)

Data Storage: MySQL (RDBMS), CSV (Columnar), Cassandra, MongoDB (Document)

Installation & Setup
To get started, install the required Python libraries using pip:

Bash
pip install Twitter
pip install PyGithub
