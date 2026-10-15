# Data Engineering Track

Welcome to the **Data Engineering Track**. This track takes students from the fundamentals of databases and programming to the tools used to build modern, production-oriented data systems.

> **Looking for the learning plan?** [Explore the Full Data Engineering Roadmap](./ROADMAP.md)

---

## Table of Contents

1. [Track Introduction](#1-track-introduction)
2. [What Does a Data Engineer Do?](#2-what-does-a-data-engineer-do)
3. [How Does Data Engineering Work in Real Life?](#3-how-does-data-engineering-work-in-real-life)
4. [Why Join This Track?](#4-why-join-this-track)
5. [Learning Approach](#5-learning-approach)
6. [Prerequisites and Expectations](#6-prerequisites-and-expectations)
7. [Track Structure](#7-track-structure)

---

## 1. Track Introduction

### What is Data Engineering?

Data Engineering is the practice of designing, building, and maintaining the systems that collect, store, move, and prepare data so that other people and applications can use it reliably.

Organizations generate data constantly: app clicks, purchases, sensor readings, database records, and more. This raw data is usually scattered across many sources, inconsistent, and not ready for analysis. Data engineers turn it into trustworthy, well-organized data.

### Why is Data Engineering important?

- **Good decisions need good data.** Reports, dashboards, and models are only as reliable as the data behind them.
- **Data is rarely ready to use.** It must be extracted, cleaned, validated, and modeled first.
- **Data systems must scale.** As data volume grows, systems must keep working reliably, which requires engineering rather than ad-hoc scripts.

### How does it contribute to the modern data ecosystem?

Data Engineering is the foundation of the modern data ecosystem. Data analysts, data scientists, and machine learning engineers all depend on the pipelines, data warehouses, and platforms that data engineers build. Without that foundation, analytics and machine learning cannot work reliably.

---

## 2. What Does a Data Engineer Do?

A Data Engineer is responsible for the journey of data from its source to the people and systems that use it.

| Responsibility | What it means | Example |
|---|---|---|
| **Collect** | Pull data from files, APIs, websites, and databases | Calling a public API or scraping a web page |
| **Process** | Run pipelines on a schedule or continuously | Running a daily batch job |
| **Transform** | Clean, validate, and reshape data | Removing duplicates and fixing missing values |
| **Store** | Organize data in databases, warehouses, and lakes | Loading clean data into a data warehouse |
| **Deliver** | Make data available to analysts and applications | Serving fact and dimension tables for reporting |

Along the way, data engineers also monitor pipelines, handle errors, check data quality, and document their work so others can understand and maintain it.

---

## 3. How Does Data Engineering Work in Real Life?

### The data pipeline lifecycle

Most data engineering work follows a simple lifecycle:

```text
Source Systems  →  Ingestion  →  Storage  →  Transformation  →  Serving
```

1. **Source systems:** where data is created (applications, databases, files, APIs).
2. **Ingestion:** moving data out of the sources, in batches or as a stream.
3. **Storage:** keeping data in a database, data warehouse, or data lake.
4. **Transformation:** cleaning, validating, and modeling the data.
5. **Serving:** delivering the prepared data to dashboards, analysts, and models.

Around these stages, **orchestration** schedules and coordinates the steps, and **monitoring and data quality checks** keep the pipeline reliable.

### A real-world example: a streaming platform

> The following is an illustrative example of the concepts above, not a description of any specific company's internal systems.

Consider a platform like Netflix. Millions of users press play, pause, search, and rate titles every day. To turn those events into analytics and personalized recommendations:

1. Viewing and interaction events are **collected** from apps and devices.
2. The events are **ingested** continuously and in batches, then **stored** at scale.
3. Data engineers **clean and transform** the raw events into organized, reliable datasets.
4. The prepared data is **served** to analysts, dashboards, and machine learning models.

### Data Engineering vs. Data Analysis vs. Machine Learning

| Role | Main focus | In the streaming example |
|---|---|---|
| **Data Engineering** | Building and maintaining the pipelines and systems that deliver reliable data | Collecting, cleaning, storing, and serving viewing data |
| **Data Analysis** | Exploring data to find insights and answer business questions | Studying which genres are watched most and when |
| **Machine Learning** | Building models that learn patterns from data to make predictions | Training a model to recommend what to watch next |

Data Engineering comes first in this chain: analysis and machine learning both depend on the data that engineers prepare.

---

## 4. Why Join This Track?

By the end of the track, students will have practical experience in:

- **Problem solving:** breaking real data problems into pipeline stages and debugging them.
- **Pipeline development:** building ETL/ELT pipelines that extract, transform, load, and orchestrate data.
- **Data management:** working with relational databases, data warehouses, and dimensional models.
- **Modern data technologies:** using tools such as SQL, Python, Docker, dbt, Airflow, Snowflake, Spark, Kafka, Iceberg, and Azure Databricks.
- **Professional practices:** version control with Git and GitHub, documentation, data quality testing, and presenting technical work.

---

## 5. Learning Approach

The track moves from fundamentals to advanced technologies in three levels, each building on the previous one:

1. **Foundations:** SQL, Python, data manipulation, and databases.
2. **Core Data Engineering:** modeling, ETL/ELT, and orchestrating data pipelines.
3. **Advanced Data Engineering:** Big Data technologies, cloud platforms, and production-oriented systems.

Learning is hands-on. Each stage pairs topics with curated learning resources (videos, books, and documentation) and practical deliverables. Students build mini projects along the way, including a data warehouse project and an end-to-end ELT pipeline, and finish with an advanced capstone project.

---

## 6. Prerequisites and Expectations

**Prerequisites**

The roadmap does not list formal prerequisites. Level 1 starts from the fundamentals of databases, SQL, and Python.

**Expectations**

Based on the roadmap's learning plan, students are expected to:

- Follow the weekly topics and learning resources.
- Complete the weekly deliverables and practical tasks.
- Document their projects, including architecture, workflow, and execution steps.
- Keep their project code in a GitHub repository with a README.
- Present their final projects and explain their main design decisions.

Some learning resources are in Arabic and some are in English.

---

## 7. Track Structure

| Level | Focus | Main Outcome |
|---|---|---|
| **Level 1: Foundations** | SQL, Python, Pandas, APIs, Scraping, Databases in Python, Git & GitHub | Build a strong technical foundation |
| **Level 2: Core Data Engineering** | Linux, Docker, Data Warehousing, Dimensional Modeling, ETL, dbt, Airflow, Snowflake | Build and orchestrate data pipelines |
| **Level 3: Advanced Data Engineering** | Hadoop Concepts, Spark, Kafka, Iceberg, Azure, Databricks | Design and build production-oriented data systems |

The detailed weekly plan, resources, and projects are in the roadmap:

**[Explore the Full Data Engineering Roadmap](./ROADMAP.md)**
