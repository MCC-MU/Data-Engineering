[← Back to Track Introduction](./README.md)

# Data Engineering Learning Roadmap

## Table of Contents

1. [Roadmap Overview](#1-roadmap-overview)
2. [Level 1: Foundations](#2-level-1-foundations)
3. [Level 2: Core Data Engineering](#3-level-2-core-data-engineering)
4. [Level 3: Advanced Data Engineering](#4-level-3-advanced-data-engineering)
5. [Projects and Practical Application](#5-projects-and-practical-application)
6. [Learning Resources](#6-learning-resources)
7. [Roadmap Summary](#7-roadmap-summary)

---

## 1. Roadmap Overview

This roadmap has three progressive levels, designed to build Data Engineering knowledge from the fundamentals to production-ready skills. The levels total 28 weeks.

| Level | Duration | Focus | Main Outcome |
|---|---|---|---|
| **Level 1: Foundations** | 10 weeks | SQL, Python, Pandas, APIs, Scraping, Databases in Python, Git & GitHub | Build a strong technical foundation |
| **Level 2: Core Data Engineering** | 10 weeks | Linux, Docker, Data Warehousing, Dimensional Modeling, ETL, dbt, Airflow, Snowflake | Build and orchestrate data pipelines |
| **Level 3: Advanced Data Engineering** | 8 weeks | Hadoop Concepts, Spark, Kafka, Iceberg, Azure, Databricks | Design and build production-oriented data systems |

**How the levels build on each other**

- **Level 1** gives you the tools to query, manipulate, and version data (SQL, Python, Pandas, Git).
- **Level 2** uses those skills to model data, build ETL/ELT pipelines, and orchestrate them (warehousing, dbt, Airflow, Snowflake).
- **Level 3** scales those ideas to Big Data and the cloud (Hadoop, Spark, Kafka, Iceberg, Azure, Databricks).

**How to use this roadmap:** each week lists its topics, learning resources, and deliverables. Tick the `- [ ]` checkboxes as you complete each deliverable.

---

## 2. Level 1: Foundations

**Objective:** Build a strong foundation in SQL, Python, data manipulation, and databases before moving into core Data Engineering concepts.

**Duration:** 10 weeks

**Recommended order:** Databases → SQL (Weeks 1–4) → Python and Pandas (Weeks 5–6) → APIs, scraping, and databases in Python (Weeks 7–8) → Git and GitHub (Week 9) → Python + SQL project (Week 10).

### Week 1: Introduction to Data Engineering & Database Fundamentals

**Topics**

- **Introduction to Data Engineering:** What Is Data Engineering?, The Data Engineering Lifecycle
- **Database Fundamentals:** Database Management Systems (DBMS), Relational Databases, SQL Server Fundamentals, Databases, Tables, Rows & Columns, Primary Keys, Foreign Keys, Basic Database Concepts

**Learning resources**

- Book: *Fundamentals of Data Engineering* by Joe Reis & Matt Housley (Chapters 1 & 2)
  - [Fundamentals of Data Engineering (book)](https://soclibrary.futa.edu.ng/books/Fundamentals%20of%20Data%20Engineering%20%28Reis,%20JoeHousley,%20Matt%29%20%28Z-Library%29.pdf)
  - [Fundamentals of Data Engineering (Videos)](https://www.youtube.com/playlist?list=PLiKvD85qG0l6aLNRjmVUFsJmw_MvC-gUt)
- ITI Database (SQL Server): first 2 videos
  - [ITI Database (SQL Server) - YouTube](https://www.youtube.com/playlist?list=PLSGEGD0dbMKrvd5ppnyFLm7q3xEH97T-t)

**Deliverables**

- [ ] Understand database fundamentals
- [ ] Understand relational database structure
- [ ] Understand tables and relationships
- [ ] Get familiar with SQL Server

### Week 2: SQL Fundamentals

**Topics**

- **SQL Fundamentals:** `SELECT`, `FROM`, `WHERE`, `ORDER BY`, `DISTINCT`, Filtering Data
- **JOINs:** `INNER JOIN`, `LEFT JOIN`, Joining Multiple Tables

**Learning resources**

- Data With Baraa, SQL Ultimate Course: from #SQL Course1 → #SQL Course11
  - [SQL Ultimate Course](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZY_2eAtUzEUulNjTJREhQe)

**Deliverables**

- [ ] Write basic SQL queries
- [ ] Retrieve and filter data
- [ ] Sort and remove duplicate results
- [ ] Join multiple tables
- [ ] Solve practical SQL exercises

### Week 3: SQL Functions & Advanced Querying

**Topics**

- **Functions:** String Functions, Number Functions, Date & Time Functions, NULL Handling, `CASE WHEN`
- **Aggregation:** Aggregate Functions, `GROUP BY`, `HAVING`
- **Advanced querying:** Subqueries, CTEs, Set Operators

**Learning resources**

- Data With Baraa, SQL Ultimate Course: from #SQL Course12 → #SQL Course32
  - [SQL Ultimate Course](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZY_2eAtUzEUulNjTJREhQe)

**Deliverables**

- [ ] Solve business-oriented SQL queries
- [ ] Apply functions and aggregations
- [ ] Build queries using `GROUP BY` and `HAVING`
- [ ] Use Subqueries and CTEs
- [ ] Solve intermediate SQL problems

### Week 4: Advanced SQL & Performance

**Topics**

- **Window Functions:** Ranking Functions, Value Functions, Running Totals, `LAG` / `LEAD`
- **Performance:** Indexes, Execution Plans, Query Optimization, Clustered & Non-Clustered Indexes, Partitioning Fundamentals, Query Performance

**Learning resources**

- Data With Baraa, SQL Ultimate Course: from #SQL Course33 → #SQL Course42
  - [SQL Ultimate Course](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZY_2eAtUzEUulNjTJREhQe)

**Deliverables**

- [ ] Build analytical SQL queries
- [ ] Use Window Functions for data analysis
- [ ] Analyze query execution plans
- [ ] Identify performance issues
- [ ] Apply basic SQL optimization techniques

### Week 5: Python Fundamentals

**Topics**

- Variables & Data Types, Conditions, Loops, Functions
- Lists, Tuples, Sets & Dictionaries, Strings
- File Handling, Exception Handling
- Modules & Packages
- Object-Oriented Programming Basics

**Learning resources**

- Big Data بالعربي, Python - The Basics
  - [Python - The Basics - Part 2 | صديقي السوعبان](https://www.youtube.com/watch?v=mlbe7Vxr7yA)

**Deliverables**

- [ ] Build small Python scripts
- [ ] Practice file and data manipulation

### Week 6: Pandas

**Topics**

- **Core objects and I/O:** Series & DataFrames, Reading CSV / Excel / JSON
- **Selection and shaping:** Data Selection, `loc` / `iloc`, Filtering, Sorting
- **Aggregation and combining:** GroupBy, Aggregation, Merge / Join, Concat
- **Cleaning:** Missing Values, Duplicates, Data Cleaning, Data Transformation

**Learning resources**

- Python Pandas
  - [(206) Pandas Tutorials - YouTube](https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS)

**Deliverables**

- [ ] Clean and transform real datasets using Pandas

### Week 7: APIs & Web Scraping

**Topics**

- **API engineering:** API Engineering overview, Basic API requests and errors, API authentication methods, Building a robust API client, Handling paginated APIs, Introduction to API series, Incremental data loading, Automated error handling, Integration testing APIs
- **Web scraping:** Introduction to Web Scraping, HTML Basics (Tags, Classes & IDs), Web Scraping using Python, BeautifulSoup Library, Extracting Structured Data from Websites, Saving Extracted Data to CSV & JSON, Error Handling & Responsible Web Scraping

**Learning resources**

1. How to Work with APIs as a Data Engineer! Part 1: [Watch](https://www.youtube.com/watch?v=rXco2Q5uBho)
2. How to Work with APIs as a Data Engineer! Part 2: [Watch](https://www.youtube.com/watch?v=XiSsHqZCaLY)
3. Python Web Scraping with Requests & BeautifulSoup: [BeautifulSoup + Requests | Web Scraping in Python](https://www.youtube.com/playlist?list=PLUaB-1hjhk8G-xVXA5FxT2cLNzd87GInr)

**Deliverables**

- [ ] Extract data from public APIs using Python
- [ ] Handle JSON responses and API pagination
- [ ] Scrape structured data from websites using BeautifulSoup
- [ ] Save extracted data into CSV and JSON files
- [ ] Build a mini data extraction project using APIs or Web Scraping

### Week 8: Databases in Python

**Topics**

- Relational Databases, SQL from Python, Database Connections
- SQLAlchemy, Querying Databases
- Loading Data, Working with Database Tables
- Integrating Python with SQL

**Learning resources**

- Databases in Python: [SQLAlchemy Crash Course - Master Databases in Python](https://www.youtube.com/watch?v=529LYDgRTgQ)
- DataCamp, Introduction to Relational Databases in Python: [DataCamp Course](https://app.datacamp.com/learn/courses/introduction-to-relational-databases-in-python)
- DataCamp, Introduction to Importing Data in Python: [DataCamp Learn](https://app.datacamp.com/learn/courses/introduction-to-importing-data-in-python)

**Deliverables:** none are listed in the source for this week.

### Week 9: Git & GitHub

**Topics**

- **Concepts:** What is Git?, What is GitHub?, Git Installation & Configuration, Repositories, Working Directory, Staging Area & Repository
- **Core commands:** `git init`, `git add`, `git commit`, `git status`, `git log`, `.gitignore`
- **Branching and remotes:** Branches, Merging, Remote Repositories, `git push`, `git pull`, `git clone`
- **Collaboration:** GitHub Repositories, Pull Requests, Basic Collaboration Workflow

**Learning resources**

- Git and GitHub: [Git and GitHub | Complete Guide (Arabic)](https://www.youtube.com/watch?v=FueXoIewxg0)

**Deliverables**

- [ ] Create and manage Git repositories
- [ ] Track changes using Git
- [ ] Create and work with branches
- [ ] Push and pull projects using GitHub
- [ ] Use GitHub for version control and project collaboration
- [ ] Create a GitHub repository for Data Engineering projects

### Week 10: End-to-End Data Analytics Project (Python + SQL)

**Topics**

- End-to-End Data Analytics Project Workflow
- Problem Understanding & Business Requirements
- Exploratory Data Analysis (EDA)
- SQL Queries for Data Analysis
- Data Transformation and Preparation
- Integrating Python with SQL
- Extracting Business Insights

**Learning resources**

- End to End Data Analytics Project (Python + SQL): [YouTube Tutorial](https://www.youtube.com/watch?v=uL0-6kfiH3g)

**Deliverables:** none are listed in the source for this week. This week is a project (see [Projects](#5-projects-and-practical-application)).

---

## 3. Level 2: Core Data Engineering

**Objective:** Move from data manipulation to building, modeling, and orchestrating data pipelines.

**Duration:** 10 weeks

**Recommended order:** Linux and Docker (Weeks 1–2) → Data warehousing and dimensional modeling (Weeks 3–4) → ETL fundamentals (Week 5) → Data Warehouse project (Week 6) → ETL project (Week 7) → dbt (Week 8) → Airflow (Week 9) → End-to-end ELT project (Week 10).

### Week 1: Linux for Data Engineers

**Topics**

- **Basics:** Linux Fundamentals, Linux File System, Files & Directories, Linux Commands, File and Directory Management
- **System administration:** Permissions & Ownership, Users & Groups, Processes & Jobs, Environment Variables, Package Management
- **Working in the shell:** Pipes & Redirection, Text Processing, Shell Scripting Basics
- **Remote and networking:** Networking Basics, SSH
- **Applied:** Linux for Data Engineering Workflows

**Learning resources**

- Linux for Data Engineers, Big Data بالعربي: [Linux for Data Engineers | يعظ العضاض البطريق](https://www.youtube.com/watch?v=gojeTqXdBH0&list=PLrooD4hY1QqADSWBJISGAq_qEPIed550b&index=4)
- [Most used Linux Commands in Data engineering](https://medium.com/art-of-data-engineering/most-used-linux-commands-in-data-engineer-day-to-day-tasks-30a5e30f0c6c)

**Deliverables**

- [ ] Navigate and manage the Linux environment
- [ ] Work with files, permissions, processes, and users
- [ ] Use Linux commands for data engineering tasks
- [ ] Connect to remote systems using SSH
- [ ] Write basic shell commands/scripts
- [ ] Understand the Linux environment used to run data pipelines

### Week 2: Docker

**Topics**

- **Concepts:** Introduction to Docker, Containers vs Virtual Machines, Docker Architecture
- **Core components:** Docker Images, Docker Containers, Docker Engine, Docker Hub, Docker CLI
- **Working with Docker:** Working with Containers, Creating Dockerfiles, Building Docker Images, Running Containers, Environment Variables
- **Storage and networking:** Docker Volumes, Docker Networks, Port Mapping
- **Multi-container setups:** Docker Compose, Multi-Container Applications
- **Applied:** Containerizing Data Engineering Applications, Running Data Pipelines with Docker

**Learning resources**

- Docker: [Docker Tutorial for Beginners (DATA DOMAIN EDITION)](https://www.youtube.com/watch?v=nAHx_uSBfTg)
- [Essential Docker Commands Every Data Engineer Must Master](https://medium.com/@muhamedfahmy7474/essential-docker-commands-every-data-engineer-must-master-2fba7a2ad8d3)

**Deliverables**

- [ ] Understand Docker and containerization
- [ ] Create and manage Docker containers
- [ ] Build custom Docker images using Dockerfiles
- [ ] Work with volumes, networks, and environment variables
- [ ] Use Docker Compose to run multiple services
- [ ] Containerize a simple Data Engineering application
- [ ] Run a data pipeline inside Docker

### Week 3: Data Warehouse Fundamentals

**Topics**

- What is a Data Warehouse?, OLTP vs OLAP, ODS vs EDW, Data Warehouse Characteristics
- Dimensional Modeling, Fact Tables, Dimension Tables
- Star Schema, Snowflake Schema, Multi-Fact Models

**Learning resources**

- Data Warehouse Book: [The Data Warehouse Toolkit](http://www.r-5.org/files/books/computers/databases/warehouses/Ralph_Kimball_Margy_Ross-The_Data_Warehouse_Toolkit-EN.pdf)
- [Data warehouse vs Data Lake vs Data lakehouse | What is the difference?](https://youtu.be/Zst0E1TLWmU)
- Data Warehouse Playlist (from Lecture 1 → Lecture 3-P4): [lecture 1 || Data warehouse || intro to Big Data and Data warehouse](https://www.youtube.com/playlist?list=PL3y0fK2jTsPTNejc7xDuuC1TsQVdQ2haf)

**Deliverables**

- [ ] Understand Data Warehouse architecture
- [ ] Design basic dimensional models

### Week 4: Dimensional Modeling

**Topics**

- **Facts and measures:** Fact Table Types, Measures, Additive Measures, Semi-Additive Measures, Non-Additive Measures
- **Dimensions:** Dimension Types, Slowly Changing Dimensions, Surrogate Keys, Conformed Dimensions

**Learning resources**

- [Understanding Data Modeling](https://www.youtube.com/watch?v=muvqw2iLeew)
- Data Warehouse Playlist (from Lecture 4 → Lecture 8): [lecture 1 || Data warehouse || intro to Big Data and Data warehouse](https://www.youtube.com/playlist?list=PL3y0fK2jTsPTNejc7xDuuC1TsQVdQ2haf)
- Additional resource: [DWH Modelling](https://www.youtube.com/playlist?list=PLxNoJq6k39G_Ffv8Na1oRbob0sVHfFc_T)

**Deliverables**

- [ ] Design a complete Star Schema
- [ ] Implement SCD Type 2

### Week 5: ETL Fundamentals

**Objective:** Understand the fundamentals of data integration and ETL workflows, including data extraction, transformation, loading strategies, and basic pipeline reliability.

**Topics**

- ETL vs. ELT vs. ETLT, Extract, Transform, and Load
- Data Sources: Files, APIs, and Databases
- Batch Processing Fundamentals
- Full Load vs. Incremental Load (Introduction)
- Data Validation and Data Quality (Introduction)
- Error Handling and Logging (Introduction)
- Reverse ETL: Concepts and Use Cases

**Learning resources**

| Topic | Resource |
|---|---|
| ETL vs. ELT vs. ETLT | [ETL vs. ELT vs. ETLT — YouTube](https://youtu.be/EqJ1qHA77z8) |
| ETL Fundamentals | [AWS — What Is ETL?](https://aws.amazon.com/what-is/etl/) |
| Data Extraction Using Python | [Pandas — Reading CSV Files](https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html), [Requests — Quickstart for APIs](https://requests.readthedocs.io/en/latest/user/quickstart/) |
| Data Quality and Validation | [Pandera Documentation](https://pandera.readthedocs.io/en/stable/) |
| Error Handling and Logging | [Python — Errors and Exceptions](https://docs.python.org/3/tutorial/errors.html), [Python — Logging](https://docs.python.org/3/library/logging.html) |
| Reverse ETL | [What Is Reverse ETL? — YouTube](https://www.youtube.com/watch?v=pkoSi8DjTl4) |

**Deliverables**

- [ ] Explain the differences between ETL, ELT, and ETLT
- [ ] Describe the main stages of an ETL pipeline
- [ ] Identify common data sources and batch processing use cases
- [ ] Understand full and incremental loading strategies
- [ ] Explain basic data quality checks, logging, and error handling
- [ ] Describe Reverse ETL and its business use cases

### Week 6: Data Warehouse Project

**Project:** End-to-End SQL Data Warehouse

**Architecture**

```text
Source Systems
      ↓
   Staging
      ↓
Transformation
      ↓
Data Warehouse
      ↓
Fact + Dimensions
```

**Project requirements**

- [ ] Source-to-target mapping
- [ ] Staging layer
- [ ] Dimension tables
- [ ] Fact tables
- [ ] Surrogate keys
- [ ] SCD Type 2
- [ ] Data quality checks
- [ ] Documentation

**Reference**

- Data With Baraa, SQL Data Warehouse Project (video): [SQL Data Warehouse from Scratch | Full Hands-On Data Engineering Project](https://www.youtube.com/watch?v=9GVqKuTVANE)
- Data With Baraa, SQL Data Warehouse Project (repository): [DataWithBaraa/sql-ultimate-course](https://github.com/DataWithBaraa/sql-ultimate-course)

### Week 7: ETL Projects & Hands-on Practice

**Objective:** Apply ETL concepts by building practical data pipelines that extract, transform, and load data from different sources.

**Topics**

- **Workflow:** End-to-End ETL Workflow, ETL Pipeline Automation Basics, ETL Pipeline Documentation
- **Extraction:** Data Extraction from CSV and Excel Files, Data Extraction from APIs
- **Cleaning and transformation:** Data Cleaning and Transformation using Python, Handling Missing Values and Duplicates, Data Type Conversion and Data Validation
- **Loading:** Loading Data into SQL Databases, Full Load vs. Incremental Load
- **Reliability:** Logging and Error Handling, Data Quality Checks

**Learning resources**

1. ETL Practice, Telecom Use Case: [YouTube Playlist](https://www.youtube.com/playlist?list=PLxNoJq6k39G_R3AA108CLE8w6n_CCCmDf)
2. End-to-End ETL with Python and SQL: [Steam Data Engineering Project](https://medium.com/@SamTaylor92/data-engineering-project-an-overview-of-an-etl-pipeline-project-0-x-214c19ea294f)

**Deliverables**

- [ ] Build an end-to-end ETL pipeline using Python and SQL
- [ ] Extract data from at least one source, such as CSV files or an API
- [ ] Clean, transform, and validate the extracted data
- [ ] Load the processed data into a SQL database
- [ ] Implement basic logging and error handling
- [ ] Document the pipeline workflow and data transformations
- [ ] Submit the Python scripts, SQL scripts, and project documentation

### Week 8: dbt Fundamentals

**Topics**

- **Introduction:** What is dbt?, dbt Core vs dbt Cloud, dbt Project Structure
- **Building blocks:** Models, Sources, Seeds, Tests, Documentation, Jinja & Macros
- **Materialization:** Materializations, Incremental Models
- **Workflow:** dbt Project Workflow, Building a dbt Transformation Pipeline, Mini Project

**Learning resources**

- DBT Tutorial for Beginners
  - [DBT Tutorial for Beginners - YouTube](https://www.youtube.com/playlist?list=PLYaPThD6DUS-N6aovIgkc871NJZyw8rY7)
  - [DBT - The Ultimate Guide | With CI/CD](https://www.youtube.com/watch?v=B8uwFmVt4sU)
- dbt documentation: [About documentation | dbt Developer Hub](https://docs.getdbt.com/docs/build/documentation?version=2)

**Deliverables**

- [ ] Understand the role of dbt in a modern data stack
- [ ] Create and structure a basic dbt project
- [ ] Build transformation models
- [ ] Apply tests and documentation
- [ ] Build a small dbt transformation pipeline

### Week 9: Apache Airflow

**Topics**

- **Introduction:** Introduction to Apache Airflow, What is Airflow?, Airflow Architecture
- **Core concepts:** DAGs (Directed Acyclic Graphs), Tasks and Operators, Scheduling in Airflow, Dependencies between Tasks, XComs, Variables and Connections
- **Operating Airflow:** Airflow Web UI, Building and Running DAGs, Monitoring and Managing Workflows

**Learning resources**

- Apache Airflow for Beginners in Arabic: [Apache Airflow for Beginners in Arabic - YouTube](https://www.youtube.com/playlist?list=PLYaPThD6DUS_BKiEPW0W-hZPgxbHXcQ8o)
- Apache Airflow for Beginners (Ansh Lamba): [Airflow Tutorial For Beginners (2026) | Apache Airflow Full Course](https://www.youtube.com/watch?v=IiczxlbQb8s)
- Apache Airflow Documentation: [What is Airflow? — Airflow 3.3.2 Documentation](https://airflow.apache.org/docs/apache-airflow/stable/index.html)

**Deliverables**

- [ ] Understand Apache Airflow and its architecture
- [ ] Create basic DAGs and tasks
- [ ] Schedule and manage data workflows
- [ ] Monitor workflow execution using the Airflow UI

### Week 10: End-to-End Data Engineering Project

**Objective:** Build an end-to-end ELT pipeline using modern data engineering tools, integrating data transformation, data modeling, quality testing, and workflow orchestration.

**Project architecture**

```text
Source Data (CSV Files)
          ↓
Snowflake Data Warehouse
          ↓
Staging Models (dbt)
          ↓
Data Transformation & Modeling (dbt)
          ↓
Fact Tables & Data Marts
          ↓
Data Quality Tests
          ↓
Workflow Orchestration (Apache Airflow)
```

**Snowflake learning scope**

- Introduction to Snowflake and Cloud Data Warehousing
- Snowflake Architecture Fundamentals
- Databases, Schemas, Tables, and Virtual Warehouses
- Loading CSV Files into Snowflake
- Executing SQL Queries and Transformations
- Basic Warehouse Usage and Credit Awareness

**Snowflake resources**

- [Get started with Snowflake for users | Snowflake Documentation](https://docs.snowflake.com/en/getting-started-for-users)
- [Tutorials to get started with Snowflake | Snowflake Documentation](https://docs.snowflake.com/en/en/learn-tutorials)

**Learning resources**

1. Primary resource, Complete Data Engineering Project (dbt, Snowflake & Apache Airflow): [YouTube Tutorial](https://www.youtube.com/watch?v=x8DE4DprAzY)
2. Additional practice, Code Along: Build an ELT Pipeline in 1 Hour (dbt, Snowflake, Airflow): [YouTube Tutorial](https://www.youtube.com/watch?v=OLXkGB7krGo)

**Deliverables**

- [ ] A working end-to-end ELT pipeline
- [ ] A structured dbt project with staging and transformation models
- [ ] Fact tables or analytical data marts
- [ ] Data quality tests and documentation
- [ ] An Airflow DAG that executes the pipeline
- [ ] A GitHub repository containing the project code, configuration instructions, and README
- [ ] A final demonstration explaining the architecture, workflow, and results

---

## 4. Level 3: Advanced Data Engineering

**Objective:** Build production-oriented skills for developing, deploying, and managing scalable data systems using Big Data technologies.

**Duration:** 8 weeks

**Recommended order:** Hadoop (Week 1) → Spark (Weeks 2–3) → Kafka (Week 4) → Iceberg (Week 5) → Azure and Databricks (Weeks 6–7) → Capstone (Week 8).

### Week 1: Hadoop Fundamentals

**Topics**

- **Big Data and Hadoop:** Introduction to Big Data, Introduction to Apache Hadoop, Hadoop Architecture, Hadoop Installation and Configuration
- **HDFS:** Hadoop Distributed File System (HDFS), NameNode and DataNode, HDFS Blocks and Replication, HDFS Commands
- **Processing:** MapReduce Fundamentals, MapReduce Workflow, YARN Architecture, Hadoop I/O
- **Concepts:** Distributed Storage and Processing

**Learning resources**

- Big Data بالعربي, Data Engineering Playlist: [Data Engineering — Hadoop Playlist](https://youtube.com/playlist?list=PLrooD4hY1QqAK5pbBpcthLuMa-cXnXJLE)

**Deliverables**

- [ ] Understand Hadoop architecture and its core components
- [ ] Explain how HDFS stores data across distributed systems
- [ ] Understand the MapReduce processing model
- [ ] Explain the role of YARN in resource management
- [ ] Run basic HDFS commands
- [ ] Set up or explore a basic Hadoop environment

### Week 2: Apache Spark Fundamentals

**Topics**

1. Introduction to Apache Spark
2. Apache Spark vs. Hadoop MapReduce
3. Spark Architecture: Driver, Executors, and Cluster Manager
4. Spark Core and Resilient Distributed Datasets (RDDs)
5. Transformations and Actions
6. Lazy Evaluation
7. Introduction to PySpark and `SparkSession`
8. Working with DataFrames and Schemas
9. Reading and inspecting CSV and JSON datasets
10. Basic DataFrame operations: `select`, `filter`, `withColumn`, and `show`

**Learning resources**

- Apache Spark (videos 1 → 14): [Apache Spark Playlist](https://youtube.com/playlist?list=PLxNoJq6k39G9lTU9A65HwC0uWD-XkqqOi)

**Deliverable**

- [ ] Build a basic PySpark application that loads a dataset, performs simple transformations, and displays the results

### Week 3: Apache Spark for Data Engineering

**Topics**

1. Advanced DataFrame transformations
2. Data cleaning and handling missing or duplicate values
3. Data aggregation and grouping
4. Joining and combining datasets
5. Spark SQL and SQL queries on DataFrames
6. Reading and writing data in CSV, JSON, and Parquet formats
7. Partitioning and repartitioning datasets
8. Caching and persistence
9. Introduction to Spark performance optimization
10. Building ETL pipelines using PySpark
11. Integrating Spark with Hadoop Distributed File System (HDFS)
12. Writing processed data to a storage destination

**Learning resources**

- Apache Spark (videos 15 → 27): [Apache Spark Playlist](https://youtube.com/playlist?list=PLxNoJq6k39G9lTU9A65HwC0uWD-XkqqOi)

**Deliverable**

- [ ] Develop an end-to-end PySpark ETL pipeline that reads raw data, cleans and transforms it, performs aggregations, and writes the final output to storage

### Week 4: Apache Kafka & Real-Time Data Streaming

**Learning objectives**

- Understand Apache Kafka architecture and use cases
- Learn Brokers, Topics, Partitions, Producers, and Consumers
- Understand Consumer Groups, Replication, and Fault Tolerance
- Explore Kafka's role in real-time data pipelines

**Learning resources**

- Kafka Basics: [Kafka بالعربي — Mohamed Ragab & Ahmed Elemam](https://www.youtube.com/watch?v=x_TFyN9w5wA)
- Kafka With Code Examples: [Apache Kafka Crash Course — Hussein Nasser](https://www.youtube.com/watch?v=R873BlNVUB4)

**Deliverable**

- [ ] A working Kafka Producer–Consumer demo

### Week 5: Apache Iceberg Fundamentals

**Objective:** Understand Apache Iceberg as an open table format for large-scale analytical datasets and learn how to create, manage, and query Iceberg tables using Apache Spark.

**Topics**

- **Foundations:** Introduction to Apache Iceberg, Data Lake vs. Data Warehouse vs. Data Lakehouse, Apache Iceberg Architecture and Core Concepts
- **Table internals:** Iceberg Tables, Catalogs, and Metadata; Data Files and Metadata Files
- **Table features:** Snapshots and Time Travel, Schema Evolution, Partition Evolution
- **With Spark:** Creating and Managing Iceberg Tables Using Spark SQL, Reading and Writing Data with PySpark, Introduction to Incremental Data Processing with Iceberg, Basic Iceberg Integration with Apache Spark

**Learning resources**

1. Primary resource, Apache Iceberg Crash Course: [YouTube Playlist](https://www.youtube.com/playlist?list=PLxNoJq6k39G82nVXzU9hFjVwT5Xqb3E6t)
2. Official documentation, Getting Started with Iceberg and Spark: [Apache Iceberg Documentation](https://iceberg.apache.org/docs/latest/spark-getting-started/)
3. Additional resource, Schema Evolution and Partition Evolution: [Apache Iceberg — Evolution](https://iceberg.apache.org/docs/latest/evolution/)

**Deliverables**

- [ ] Explain the role of Apache Iceberg in a modern Data Lakehouse architecture
- [ ] Create and query Iceberg tables using Apache Spark
- [ ] Load and update data in Iceberg tables
- [ ] Explore table snapshots and perform a basic Time Travel query
- [ ] Demonstrate a schema change without recreating the entire table
- [ ] Build a small PySpark pipeline that writes processed data into an Iceberg table

### Week 6: Cloud Computing & Azure for Data Engineers

**Objective:** Understand cloud computing fundamentals and learn how Microsoft Azure services support modern data engineering workflows.

**Topics**

- **Cloud fundamentals:** Introduction to Cloud Computing, Cloud Service Models (IaaS, PaaS, and SaaS), Cloud Deployment Models (Public, Private, and Hybrid)
- **Azure:** Introduction to Microsoft Azure, Azure Portal and Resource Management
- **Azure data services:** Azure Storage Fundamentals, Azure Blob Storage and Azure Data Lake Storage Gen2, Introduction to Azure Data Factory

**Learning resources**

1. Primary resource, Data Engineering on Microsoft Azure (videos 1 → 14): [YouTube Playlist](https://www.youtube.com/playlist?list=PLuQSde7Xvu7DCRenR1otgxAplTtnzKO9e)
2. Additional resource, Get Started with Data Engineering on Azure: [Microsoft Learn](https://learn.microsoft.com/en-us/training/paths/get-started-data-engineering/)
3. Additional resource, Azure Data Factory: [Data Integration at Scale with Azure Data Factory](https://learn.microsoft.com/en-us/training/paths/data-integration-scale-azure-data-factory/)

**Deliverables**

- [ ] Explain cloud computing concepts and service models
- [ ] Identify the main Azure services used in data engineering
- [ ] Understand the role of cloud storage in data lake architectures
- [ ] Build or explore a basic data ingestion pipeline using Azure Data Factory
- [ ] Explain how Azure supports cloud-based data processing and orchestration

### Week 7: Azure Databricks for Data Engineering

**Objective:** Learn how to use Azure Databricks to build, run, and manage cloud-based data engineering pipelines using Apache Spark.

**Topics**

- **Platform:** Introduction to Azure Databricks, Azure Databricks Architecture and Workspace, Databricks Notebooks and Compute Resources
- **Working with data:** Working with PySpark in Databricks, Reading Data from Cloud Storage, DataFrames and Spark SQL, Data Transformation and Data Cleaning
- **Delta Lake:** Delta Lake Fundamentals, Creating and Managing Delta Tables, Data Quality and Validation
- **Governance and operations:** Introduction to Unity Catalog, Running and Monitoring Data Engineering Jobs, Basic Performance and Cost Optimization

**Learning resources**

1. Main resource: [Databricks Tutorial (From Zero to Hero) | Azure Databricks Masterclass](https://www.youtube.com/watch?v=7pee6_Sq3VY&list=PL3xdDnOlnPd1oT-bnut-uJi9BU3a_L_rV&index=1)
2. Microsoft Learn, Set Up and Configure the Azure Databricks Environment: [Set up and Configure an Azure Databricks Environment - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/paths/azure-databricks-data-engineer-set-up-configure-environment/)
3. Microsoft Learn, Prepare and Process Data with Azure Databricks: [Prepare and Process Data with Azure Databricks - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/paths/azure-databricks-data-engineer-prepare-process-data/)
4. Official Azure Databricks tutorials: [Get started tutorials on Azure Databricks - Azure Databricks | Microsoft Learn](https://learn.microsoft.com/en-us/azure/databricks/getting-started/)

**Practical task / deliverable**

Build a cloud-based PySpark data pipeline in Azure Databricks that:

- [ ] Reads a dataset from a supported storage source
- [ ] Cleans and transforms the data using PySpark
- [ ] Applies basic data quality checks
- [ ] Saves the processed data into a Delta table
- [ ] Runs the pipeline in Databricks and verifies the output

### Week 8: Advanced Data Engineering Capstone Project

**Objective:** Apply data engineering concepts by building and analyzing end-to-end batch or real-time data pipelines using modern data engineering technologies.

**Topics**

- End-to-End Data Pipeline Architecture
- Data Ingestion and Storage
- Data Transformation using Apache Spark
- Data Modeling and Star Schema
- Data Lakehouse Architecture
- Workflow Orchestration using Apache Airflow
- Cloud-Based Data Engineering with Azure
- Data Quality and Validation
- Pipeline Monitoring and Error Handling
- Introduction to Real-Time Change Data Capture (CDC) (optional)

**Learning resources**

1. Primary resource, End-to-End Data Warehouse on Azure (Arabic): [YouTube Tutorial](https://www.youtube.com/watch?v=6qE9MJ7oDgQ)
2. Reference project, Charity Data Engineering Pipeline: [GitHub Repository](https://github.com/mohamedmeqlad99/charity_data_engineering_project)
3. Additional practice, Student Performance Data Pipeline: [GitHub Repository](https://github.com/mohamedmeqlad99/student_performance_datapipeline)
4. Advanced optional resource, Real-Time CDC with Debezium, Kafka Connect & Redpanda: [Medium Article](https://medium.com/data-engineering-indonesia/real-time-cdc-using-mysql-postgres-mssql-debezium-kafka-connect-and-redpanda-c8b2a6856bda)

**Deliverables**

- [ ] Build or reproduce an end-to-end data pipeline
- [ ] Ingest data from one or more sources
- [ ] Clean, transform, and validate the data using appropriate tools
- [ ] Store the processed data in a structured analytical destination
- [ ] Implement workflow orchestration and basic monitoring
- [ ] Document the architecture, data flow, and execution steps
- [ ] Submit a GitHub repository with source code and a README
- [ ] Present the project and explain the main design decisions

---

## 5. Projects and Practical Application

Each level includes hands-on work. Use this table to track project progress.

| Level | Week | Project | Main Deliverables | Done |
|---|---|---|---|---|
| 1 | 7 | Mini data extraction project (APIs or Web Scraping) | Data extracted from public APIs or scraped websites and saved as CSV and JSON | [ ] |
| 1 | 9 | GitHub repository for Data Engineering projects | A repository to hold the projects built in the track | [ ] |
| 1 | 10 | End-to-End Data Analytics Project (Python + SQL) | EDA, SQL analysis, data preparation, and business insights | [ ] |
| 2 | 2 | Containerized data application | A simple Data Engineering application and a data pipeline running in Docker | [ ] |
| 2 | 6 | End-to-End SQL Data Warehouse | Source-to-target mapping, staging layer, dimension and fact tables, surrogate keys, SCD Type 2, data quality checks, documentation | [ ] |
| 2 | 7 | End-to-End ETL pipeline (Python + SQL) | Python scripts, SQL scripts, and project documentation | [ ] |
| 2 | 8 | dbt mini project | A small dbt transformation pipeline with tests and documentation | [ ] |
| 2 | 10 | End-to-End ELT pipeline (Snowflake, dbt, Airflow) | Working pipeline, dbt project, fact tables or data marts, data quality tests, Airflow DAG, GitHub repository with README, final demonstration | [ ] |
| 3 | 2 | Basic PySpark application | Loads a dataset, applies simple transformations, displays results | [ ] |
| 3 | 3 | PySpark ETL pipeline | Reads raw data, cleans and transforms it, aggregates, writes output to storage | [ ] |
| 3 | 4 | Kafka Producer–Consumer demo | A working demo | [ ] |
| 3 | 5 | PySpark pipeline writing to an Iceberg table | Iceberg tables with snapshots, time travel, and schema change | [ ] |
| 3 | 7 | Cloud-based PySpark pipeline in Azure Databricks | Processed data saved in a Delta table and output verified | [ ] |
| 3 | 8 | Advanced Data Engineering Capstone | End-to-end pipeline, documentation, GitHub repository with README, project presentation | [ ] |

---

## 6. Learning Resources

Learning resources are listed under each week so you can find them next to the topics they support. They include:

- **Videos and playlists:** many in Arabic and English.
- **Books:** *Fundamentals of Data Engineering* (Level 1, Week 1) and *The Data Warehouse Toolkit* (Level 2, Week 3).
- **Official documentation:** Python, pandas, Requests, Pandera, dbt, Airflow, Snowflake, Apache Iceberg, Microsoft Learn, and Azure Databricks.
- **Courses and articles:** DataCamp courses and Medium articles.
- **Reference projects:** GitHub repositories for the data warehouse and capstone projects.

---

## 7. Roadmap Summary

The track moves from foundational skills to advanced Data Engineering technologies in three levels:

1. **Foundations:** SQL, Python, Pandas, APIs, web scraping, databases in Python, and Git & GitHub, ending with a Python + SQL analytics project.
2. **Core Data Engineering:** Linux, Docker, data warehousing, dimensional modeling, ETL, dbt, Airflow, and Snowflake, ending with an end-to-end ELT pipeline.
3. **Advanced Data Engineering:** Hadoop, Spark, Kafka, Iceberg, Azure, and Databricks, ending with a capstone project.

[← Back to Track Introduction](./README.md)
