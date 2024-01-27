## Technical Knowledge Base

### Relational Databases

- [PostgreSQL](https://www.postgresql.org) - is a powerful, open source object-relational database system with over 35 years of active development that has earned it a strong reputation for reliability, feature robustness, and performance.
- [MySQL](https://www.mysql.com) - the most popular Open Source SQL database management system, is developed, distributed, and supported by Oracle Corporation.
- [Amazon Relational Database System (RDS)](https://aws.amazon.com/rds/) is a collection of managed services that makes it simple to set up, operate, and scale databases in the cloud. Choose from seven popular engines — Amazon Aurora with MySQL compatibility, Amazon Aurora with PostgreSQL compatibility, MySQL, MariaDB, PostgreSQL, Oracle, and SQL Server

### Columnar Databases
- [Amazon Redshift](https://aws.amazon.com/redshift/?nc=sn&loc=0) - Store, analyze, and process large amounts of data. Cloud Data Warehouse. PostgreSQL backend. MPP Engine and architecture. Available in **Provisioned** or **Serverless**.
- [Google BigQuery](https://cloud.google.com/bigquery?hl=en) - is a serverless and cost-effective enterprise data warehouse that works across clouds and scales with your data.

### Key-value
- [Redis](https://redis.io) - is an open source (BSD licensed), in-memory key-value cache, message broker, and streaming engine.
- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) - is a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale.

### Object Storage
- [Amazon S3](https://aws.amazon.com/s3/) - is an object storage service offering industry-leading scalability, data availability, security, and performance.
- [Azure Blob Storage](https://azure.microsoft.com/en-us/products/storage/blobs) - massively scalable and secure object storage for cloud-native workloads, archives, data lakes, high-performance computing, and machine learning.
- [Google Cloud Storage](https://cloud.google.com/storage?hl=en) - is a managed service for storing unstructured data. Store any amount of data and retrieve it as often as you like.

## Data Ingestion
- Apache Kafka - a distributed event streaming platform.
    - [Apache Kafka (open-source)](https://kafka.apache.org/)
    - [Apache Kafka (Confluent)](https://www.confluent.io) - A Fully Managed Service of Apache Kafka that offers support from Kafka Committer-led experts, 99.99% uptime SLA, and etc. Apache Kafka in Confluent is **Cloud-Native**
    - [Amazon Managed Streaming for Apache Kafka (Amazon MSK)](https://aws.amazon.com/msk/) - is a Fully Managed Kafka Service that operates, maintains, and scales Apache Kafka clusters, provides enterprise-grade security features out of the box, and has built-in AWS integrations that accelerate development of streaming data applications. Apache Kafka in AWS is **Cloud-Hosted**
- [AWS SDK for pandas (AWS Wrangler)](https://github.com/aws/aws-sdk-pandas) - an open source python initiative that extends the power of the pandas library to AWS, connecting DataFrames and AWS data & analytics services. **Open-source**
- [AWS Kinesis](https://aws.amazon.com/kinesis/) - A fully managed, cloud-based service for real-time data processing over large, distributed data streams.
- [Airbyte](https://github.com/airbytehq/airbyte) - A data integration platform for ELT pipelines from APIs, databases & files to databases, warehouses & lakes.
    - [Open-source](https://airbyte.com/solutions/airbyte-open-source)
    - [Airbyte Cloud](https://airbyte.com/solutions/airbyte-cloud)
- [Pentaho Data Integration (Kettle)](https://www.hitachivantara.com/en-us/products/pentaho-platform/data-integration-analytics.html) - consists of a core data integration (ETL) engine, and GUI applications that allow the user to define data integration jobs and transformations.
    - [Community Edition](https://www.hitachivantara.com/en-us/products/pentaho-platform/data-integration-analytics/pentaho-community-edition.html)

## Data Formats

- [Apache Arvo](https://avro.apache.org) - is the leading serialization format for record data, and first choice for streaming data pipelines.
- [Apache Parquet](https://parquet.apache.org) - is an open source, column-oriented data file format designed for efficient data storage and retrieval.
- [Apache ORC](https://orc.apache.org) - the smallest, fastest columnar storage for Hadoop workloads.

## Data Storage Framework

- [Delta Lake](https://delta.io) - is an open-source storage framework that enables building a Lakehouse architecture with compute engines including Spark, PrestoDB, Flink, Trino, and Hive and APIs for Scala, Java, Rust, Ruby, and Python. Led by [Databricks](https://www.databricks.com).
- [Apache Iceberg](https://iceberg.apache.org) - is an open table format for huge analytic datasets. Iceberg adds tables to compute engines including Spark, Trino, PrestoDB, Flink, Hive and Impala using a high-performance table format that works just like a SQL table. Developed by [Netflix](https://github.com/Netflix/iceberg#status)
- [Apache Hudi](https://hudi.apache.org) - (pronounced Hoodie), stands for `Hadoop Upserts Deletes and Incrementals`. Hudi manages the storage of large analytical datasets on DFS (Cloud stores, HDFS or any Hadoop FileSystem compatible storage). Developed by [Uber](https://www.uber.com/en-TW/blog/hoodie/).

## Batch Processing

### Frameworks and Libraries

- [Apache Spark](https://spark.apache.org) - is a multi-language engine for executing data engineering, data science, and machine learning on single-node machines or clusters.
    - [PySpark](https://spark.apache.org/docs/latest/api/python/index.html)
    - [Scala](https://spark.apache.org/docs/latest/api/scala/org/apache/spark/index.html)
    - [Pandas API on Spark](https://spark.apache.org/docs/latest/api/python/getting_started/quickstart_ps.html) - Allows pandas function on top of Spark
    - [Spark SQL](https://spark.apache.org/docs/latest/api/sql/index.html) - List of SQL Functions
    - [SparkR](https://spark.apache.org/docs/latest/sparkr.html)
    - [Java](https://spark.apache.org/docs/latest/api/java/index.html)
- [Polars (Python)](https://www.pola.rs) - is a lightning fast DataFrame library/in-memory query engine.
- [Dask (Python)](https://docs.dask.org/en/stable/) - is a flexible library for parallel computing in Python.

### SQL

- [Presto](http://prestodb.io) - is a distributed SQL query engine for big data that allows you to run SQL queries against various data sources.
- [Apache Hive](https://hive.apache.org) - is built on top of Apache Hadoop. A distributed, fault-tolerant data warehouse system that enables analytics at a massive scale and facilitates reading, writing, and managing petabytes of data residing in distributed storage using SQL.
- [Apache Drill](https://drill.apache.org)- is an Apache open-source SQL query engine for Big Data exploration.
- [Trino](https://trino.io) - is a distributed SQL query engine designed to query large data sets distributed over one or more heterogeneous data sources.

### Managed Services (Cloud)

- [AWS Elastic MapReduce (EMR)](https://aws.amazon.com/emr/) - is the industry-leading cloud big data solution for petabyte-scale data processing, interactive analytics, and machine learning using open-source frameworks such as Apache Spark, Apache Hive, and Presto.
- [AWS Glue](https://aws.amazon.com/glue/) - is a serverless data integration service that makes it easier to discover, prepare, and combine data for analytics, machine learning (ML), and application development.

## Stream Processing

- [Spark Streaming (DStreams)](https://spark.apache.org/docs/latest/streaming-programming-guide.html) - an extension of core Spark API for processing of live data streams. **Deprecated** as of Spark 2.0.
    - [Spark Structured Streaming (DataFrames)](https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html) - is a stream processing engine built on the Spark SQL engine.
- [Apache Flink](https://flink.apache.org) - is a framework and distributed processing engine for stateful computations over Data Streams
- [Apache Storm](https://storm.apache.org/about/integrates.html) - is a free and open source distributed realtime computation system. Doing for realtime processing what Hadoop did for batch processing.

### Data Stores
- [Apache Druid](https://druid.apache.org) - is a high performance, real-time analytics database that delivers sub-second queries on streaming and batch data at scale and under load.
- [Apache Pinot](https://pinot.apache.org) - realtime distributed OLAP datastore, designed to answer OLAP queries with low latency

## Workflow Orchestration

- [Apache Airflow](https://airflow.apache.org) - is an open-source workflow management platform for data engineering pipelines. Built by [Airbnb](https://airbnb.io/projects/airflow/).
    - [Astronomer](https://www.astronomer.io)
    - [Amazon Managed Workflows for Apache Airflow (MWAA)](https://aws.amazon.com/managed-workflows-for-apache-airflow/)
- [Mage](https://www.mage.ai) - Open-source data pipeline tool for transforming and integrating data. The modern replacement for Airflow.
- [Dagster](https://dagster.io) - An orchestration platform for the development, production, and observation of data assets.
    - [Open-source](https://docs.dagster.io/getting-started)
    - [Dagster Cloud](https://dagster.io/cloud)
- [Prefect](https://www.prefect.io) - is a workflow orchestration tool empowering developers to build, observe, and react to data pipelines.
    - [Open-source](https://docs.prefect.io/2.13.8/getting-started/quickstart/#__tabbed_1_2)
    - [Prefect Cloud](https://www.prefect.io/cloud)
- [Kestra](https://kestra.io) - is a universal open-source orchestrator that makes both scheduled and event-driven workflows easy
    - [Open-source](https://kestra.io/docs)
    - [Kestra Cloud](https://kestra.io/enterprise)
- [AWS Step Functions](https://aws.amazon.com/step-functions/) - is a fully managed service that makes it easier to coordinate the components of distributed applications and microservices using visual workflows.

## Data Transformation

### Frameworks

- [Data Build Tool (dbt)](https://www.getdbt.com) - is a SQL-first transformation workflow that lets teams quickly and collaboratively deploy analytics code following software engineering best practices like modularity, portability, CI/CD, and documentation.
    - [dbt-core (open-source)](https://docs.getdbt.com/docs/core/installation)
    - [dbt Cloud](https://www.getdbt.com/product/dbt-cloud)
- [SQLMesh](https://sqlmesh.readthedocs.io/en/stable/) - is an open source data transformation framework that brings the best practices of DevOps to data teams. It enables data scientists, analysts, and engineers to efficiently run and deploy data transformations written in SQL or Python.

## Data Governance

### Enterprise Data Catalog

- [DataHub Project](https://datahubproject.io) - is an extensible metadata platform that enables data discovery, data observability and federated governance to help tame the complexity of your data ecosystem. Has **open-source** and **Managed**. Built by [LinkedIn](https://engineering.linkedin.com/blog/2019/data-hub). 
- [OpenMetadata](https://open-metadata.org) - A Single Place to Discover, Collaborate and get your Data Right. **Open-source.** Inspired by Uber's metadata platform.
- [Apache Atlas](https://atlas.apache.org/#/) - is an open-source metadata and big data governance framework which helps data users collaborate on their data assets. **Open-source.** Incubated by [Hortonworks](https://www.prnewswire.com/news-releases/hortonworks-establishes-data-governance-initiative-300026958.html).
- [Amundsen](https://www.amundsen.io) - Open source data discovery and metadata engine. Created by Lyft. 

### Data Quality/Observability
- [Great Expectations](https://greatexpectations.io) - a platform for Data Quality.
    - [Open-source](https://docs.greatexpectations.io/docs/tutorials/quickstart/) - is a Python library that provides a framework for describing the acceptable state of data and then validating that the data meets those criteria.
    - [Cloud (SaaS)](https://greatexpectations.io/gx-cloud) - 

## Data Platforms

- [Databricks](https://www.databricks.com) - Founders of Apache Spark. Combines Data Warehouse and Data Lake (Data Lake House) into a platform. Unified. Open. Scalable. Try it [free](https://www.databricks.com/try-databricks#account) for 14 days. Suggest that you use AWS as the choice of platform.
- [Snowflake](https://www.snowflake.com/en/) - The Data Cloud. Cloud-native Data Warehouse Platform. Consists of Cloud Services Layer, Compute Layer, and Data Storage Layer. Try it [free](https://signup.snowflake.com) for 30 days.  