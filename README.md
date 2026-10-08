# Hi, I'm Jeeraphat 👋

Data Engineering enthusiast focused on building scalable ETL pipelines, cloud data platforms, and transforming raw data into analytics-ready datasets.

---

## 👨‍💻 About Me

- 🎓 Bachelor of Science in Business Information Technology at King Mongkut's Institute of Technology Ladkrabang
- 🔧 Interested in Data Engineering, Lakehouse Architecture, Cloud Data Warehousing, Orchestration, and Data Modeling
- 🔍 Currently seeking a Data Engineering / Data internship opportunity
- 🌱 Working with Apache Airflow, Apache Spark, Docker, and Google Cloud Platform (BigQuery, GCS)
- 📫 Contact:
  - Email: [jeeraphat.sutti@gmail.com](mailto:jeeraphat.sutti@gmail.com)
  - LinkedIn: [My LinkedIn](https://www.linkedin.com/in/jeeraphat-suttitheeravut-0281b93a6)

---

## 🚀 Projects

### [Retail Customer 360 & Feature Store Pipeline](https://github.com/JeeraphatSutti/retail-customer-360)

Hybrid cloud data platform implementing Medallion Architecture (Bronze → Silver → Gold) on Olist E-Commerce dataset:

- Ingests raw data across 5 relational datasets into Google Cloud Storage (Bronze)
- Orchestrates multi-step ELT workflows using **Apache Airflow** in a containerized Docker environment
- Cleans, deduplicates, and models normalized tables into **Google BigQuery** (Silver)
- Builds Customer 360 analytics table with **RFM Segmentation**, review sentiment scores, and payment method breakdowns (Gold)
- Delivers an interactive **Looker Studio** dashboard tracking R$ 15.7M in revenue across 94,990 unique customers

**Tech stack:** Python, Apache Airflow, Apache Spark (PySpark), dbt, Google Cloud Storage, BigQuery, Looker Studio, Docker

---

### [Movie Box Office ETL Pipeline](https://github.com/JeeraphatSutti/movie-box-office-etl)

End-to-end ETL pipeline using a medallion architecture:

**Bronze → Silver → Gold**

- Ingests approximately 1M movie records incrementally
- Supports idempotent and re-runnable processing
- Includes deduplication and data quality checks
- Performs date parsing and year validation
- Tracks data lineage using `_ingested_at` and `_source_file`
- Creates gold-layer aggregates by year, genre, and top directors

**Tech stack:** Python, Pandas, Parquet, Airflow, Docker

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

---

### Language & Status

![Thai](https://img.shields.io/badge/Language-Thai-1f9d55?style=for-the-badge)
![English](https://img.shields.io/badge/Language-English-007ACC?style=for-the-badge)
![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Work-00C853?style=for-the-badge)
![Seeking Internship](https://img.shields.io/badge/Seeking-Data%20Engineering%20Intern-FF9800?style=for-the-badge)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=JeeraphatSutti&show_icons=true&theme=default" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JeeraphatSutti&layout=compact" alt="Top languages" />
</p>
