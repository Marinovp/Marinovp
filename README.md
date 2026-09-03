# Marino V.

**Senior Data Engineer **

I build lakehouse platforms that hold up in production: incremental ingestion that reruns safely, transformations that are tested before they ship, and pipelines that fail loudly instead of quietly writing bad data.

📍 Orlando, FL · Open to [collaboration and conversation](https://www.linkedin.com/in/Marinovp)

---

## What I work on

- **Lakehouse architecture** — medallion (bronze/silver/gold) designs with an emphasis on schema evolution and partition strategy that survives contact with real data volumes.
- **Incremental & CDC ingestion** — watermarking, `MERGE INTO` Delta, late-arriving record handling, and idempotent reruns so a failed pipeline is a non-event.
- **Data quality as code** — expectation checks, quarantine tables for rejected records, and quality metrics tracked over time rather than discovered by a stakeholder.
- **Tested pipelines** — pytest against local Spark sessions, CI on every push. Transformation logic gets the same treatment as application code.

---

## Stack

**Processing & Lakehouse**
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat&logo=delta&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Cloud**
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)

**Orchestration, Modeling & Ops**
![Data Factory](https://img.shields.io/badge/Data%20Factory-0089D6?style=flat&logo=microsoftazure&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Storage & Serving**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)



---

## Selected projects

| Project | What it does | Stack |
|---|---|---|
| [pyspark-data-quality](#) | Reusable expectation framework — row-level checks, quarantine tables for failures, and a quality metrics table you can trend. | PySpark, Delta, pytest |
| [incremental-ingestion-patterns](#) | Watermarking, CDC, and `MERGE INTO` patterns with idempotent reruns and late-arriving data handling, benchmarked against full reloads. | PySpark, Delta |
| [spark-testing-ci](#) | How to actually test Spark transformations — local session fixtures, pytest, and GitHub Actions running on every push. | PySpark, pytest, Actions |


---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/Marinovp)
[![X](https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white)](https://x.com/Marinovp)
