# End-to-End Reddit ETL Pipeline on AWS

This project implements a scalable ETL pipeline that extracts data from Reddit via its public API, processes it through orchestrated tasks, and loads it into Amazon Redshift for analytical querying. The pipeline utilizes a modern data stack including Apache Airflow, Celery, Docker, and key AWS services like S3, Glue, Athena, and Redshift.

---

## 🛠️ Tech Stack

- **Data Source:** Reddit API  
- **Orchestration:** Apache Airflow, Celery  
- **Storage & Metadata:** PostgreSQL, Amazon S3  
- **Transformation:** AWS Glue, Amazon Athena  
- **Data Warehouse:** Amazon Redshift  
- **Infrastructure:** Docker, Docker Compose  
- **Language:** Python  

---

## 🔁 Pipeline Workflow

1. **Extract** Reddit data using the API and orchestrate using Apache Airflow & Celery.  
2. **Store** raw JSON outputs in Amazon S3.  
3. **Track** metadata and intermediate states in PostgreSQL.  
4. **Transform** the data using AWS Glue and SQL queries via Athena.  
5. **Load** the cleaned datasets into Redshift for querying and BI analysis.

---

## 🧠 Key Concepts Demonstrated

- Asynchronous task orchestration using Celery with Airflow  
- Building containerized data pipelines using Docker  
- Hands-on experience with AWS-native tools for large-scale ETL  
- Modular code design separating DAGs, ETL logic, config, and utility functions  
- Scalable pipeline flow from raw data to query-ready tables

---

