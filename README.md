<div align="center">

# 🔬 Srikar Vechalapu

### Data Engineer | Data Lake, Streaming & Warehouse Modeling on AWS

*Layered S3 data lakes, Kafka/Spark streaming pipelines, and dimensional Redshift warehouses*

📍 San Diego, CA · Open to relocate

[![Email](https://img.shields.io/badge/Email-vsrikar2025%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vsrikar2025@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-srikarvechalapu-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srikarvechalapu)
[![Portfolio](https://img.shields.io/badge/Portfolio-srikarvechalapu.com-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://srikarvechalapu.github.io/srikarvechalapu.github.io-7845/)
[![GitHub](https://img.shields.io/badge/GitHub-srikarvechalapu-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/srikarvechalapu)

![Profile Views](https://komarev.com/ghpvc/?username=srikarvechalapu&color=blueviolet&style=for-the-badge)
![GitHub Stars](https://img.shields.io/github/stars/srikarvechalapu?style=for-the-badge&color=yellow)

</div>

---

## 📊 Summary

Data Engineer with **5+ years** building data lake infrastructure, streaming pipelines, and dimensional warehouse models on AWS. I own a layered S3 data lake and the streaming path behind it, processing **12M+ daily supply-chain events** into a multi-billion-row Redshift warehouse. Migrated a **50-workflow** legacy ETL estate to Airflow and added data quality checks gating **200+ production tables**.

**Stack:** Python · SQL · PySpark · Spark Structured Streaming · Kafka · Airflow · dbt · Databricks · AWS · Redshift

**Wins:** 12M+ events/day at 6K/sec peak · P95 report runtime 38 → 5 min · nightly batch window 7 hrs → 90 min · 15-min freshness SLA

---

## 🧬 Pipeline Architecture
```mermaid
graph LR
    A[Data Sources] -->|Ingestion| B[ETL Layer]
    B -->|AWS Redshift/BigQuery| C[Data Warehouse]
    C -->|Transformation| D[dbt Models]
    D -->|Analytics| E[Feature Engineering]
    E -->|ML Models| F[Predictive Analytics]
    C -->|BI Layer| G[Dashboards]
    G -->|Power BI/Looker/Tableau| H[Business Insights]
    F -->|Monitoring| I[Performance Tracking]
    I -->|Feedback Loop| B
    
    style A fill:#e1f5ff,stroke:#01579b
    style C fill:#fff3e0,stroke:#e65100
    style F fill:#f3e5f5,stroke:#4a148c
    style H fill:#e8f5e9,stroke:#1b5e20
```

---

## 📈 Model Results

| Model | Use Case | Size | Accuracy | Business Impact |
|-------|----------|------|----------|-----------------|
| **Customer Churn** | Retention strategies | 50K+ records | **83%** | 11% churn reduction |
| **Marketing Attribution** | Campaign ROI | 328 rows, 3 platforms | — | 18% ROI increase |
| **Healthcare Risk** | Patient outcomes | 1M+ records | — | 20% accuracy gain |
| **Demand Forecasting** | Inventory optimization | Time-series | — | 35% fewer stockouts |

*Models: Random Forest · Logistic Regression · XGBoost · ARIMA*

---

## 💻 Tech Stack

<div align="center">

### Languages & Processing
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### Data Platforms & Orchestration
![Apache Spark](https://img.shields.io/badge/Spark_Batch_%26_Streaming-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)

### AWS
![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=for-the-badge&logo=amazon-redshift&logoColor=white)
![Glue](https://img.shields.io/badge/AWS_Glue-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Athena](https://img.shields.io/badge/Athena-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Step Functions](https://img.shields.io/badge/Step_Functions-FF4F8B?style=for-the-badge&logo=amazon-aws&logoColor=white)
![EventBridge](https://img.shields.io/badge/EventBridge-FF4F8B?style=for-the-badge&logo=amazon-aws&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazon-cloudwatch&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=for-the-badge&logo=amazon-aws&logoColor=white)

### Data Warehousing
![Dimensional Modeling](https://img.shields.io/badge/Dimensional_Modeling-0B5FFF?style=for-the-badge)
![ELT](https://img.shields.io/badge/ELT-1F6FEB?style=for-the-badge)
![CDC](https://img.shields.io/badge/CDC-6E40C9?style=for-the-badge)
![SCD Type 2](https://img.shields.io/badge/SCD_Type_2-8250DF?style=for-the-badge)
![Partitioning](https://img.shields.io/badge/Partitioning-0969DA?style=for-the-badge)
![Data Quality](https://img.shields.io/badge/Data_Quality_Frameworks-2DA44E?style=for-the-badge)

### Databases & Warehouses
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)

### DevOps & Reporting
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

</div>

---

## 🎯 Expertise Distribution
```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor':'#e1f5ff','primaryTextColor':'#01579b','primaryBorderColor':'#0277bd','lineColor':'#0288d1','secondaryColor':'#fff3e0','tertiaryColor':'#f3e5f5'}}}%%
pie title Technical Expertise Areas
    "Data Lake & Pipeline Engineering" : 30
    "Streaming & Real-Time Ingestion" : 25
    "Dimensional Modeling & Warehousing" : 20
    "Orchestration & Data Quality" : 15
    "Query & Cost Optimization" : 10
```

---

## 🏢 Career Timeline
```mermaid
timeline
    title Career Progression in Data Analytics
    section McKesson Corporation
        Aug 2024 : Data Engineer
                 : S3 Data Lake + Kafka to Spark Streaming
                 : 12M+ Events per Day
    section Uber Technologies
        May 2021 : Data Engineer
                 : PySpark, Glue and dbt on S3 and Redshift
                 : 3M+ Daily Trip Events
    section Cipla Ltd
        Nov 2018 : Data Engineer
                 : SAP, Salesforce and Oracle Integration
                 : Batch Window 7 hrs to 90 min
    section Education
        Aug 2022 : MS in MIS
                 : University of Memphis
```

---

## 🔬 Featured Projects

### 1️⃣ Healthcare Data Pipeline & Reporting Automation
**Stack:** `AWS Redshift` `S3` `Apache Airflow` `Python` `SQL`

Built 12+ ETL pipelines with incremental loading and validation checkpoints. Automated recurring reports, cutting manual work by 15+ hrs/week.

- ⚡ **40% faster** processing · ✅ **25% fewer** errors · 📊 **30% fewer** ad-hoc requests

---

### 2️⃣ Customer Churn Prediction
**Stack:** `Python` `Scikit-learn` `Pandas` `Tableau`

Trained Random Forest/XGBoost on 50K+ records with feature engineering and GridSearchCV tuning. Built Tableau dashboard for real-time risk monitoring.

- 🎯 **83% accuracy** · 📉 **11% churn reduction** · 💰 **~$2M** estimated revenue retained

---

### 3️⃣ Cross-Platform Marketing Analytics
**Stack:** `BigQuery` `SQL` `Python` `Looker Studio`

Unified Facebook, Google, and TikTok ad data with 13 quality checks and 3 analytics views.

| Platform | CPA | CVR | Best For |
|----------|-----|-----|----------|
| Facebook | $7.64 | 2.4% | Cost-efficient conversions |
| Google | $24.80 | 3.07% | High-intent traffic |
| TikTok | $12.50 | 1.8% | Brand awareness |

[🔗 View Project](https://github.com/srikarvechalapu/cross-platform-marketing-analytics)

---

### 4️⃣ Pharmaceutical Clinical Data Platform
**Stack:** `Python` `SQL` `AWS S3` `Redshift` `Power BI`

Processed 1M+ clinical records with dimensional modeling and 10+ Power BI dashboards for 60+ business users.

- ✅ **20% accuracy gain** · ⏱️ **35 hrs/month** saved · 🔒 Full HIPAA compliance · Eliminated **30K+ annual data entry errors**

---

## 📚 Open-Source Projects

**🔹 Data Pipelines with Airflow**
Airflow ETL pipeline for S3-to-Redshift warehouse loads with custom StageToRedshift, LoadFact, LoadDimension, and DataQuality operators, plus templated backfills.
`Airflow` `Python` `SQL` `AWS Redshift` · [View Repo](https://github.com/srikarvechalapu/data-pipelines-with-airflow)

**🔹 F1 Data Analysis (1953–2020)**
SQL + Python analysis of 67 years of F1 racing data across 1,000+ Grand Prix events.
`SQL` `Python` `Tableau` · [View Repo](https://github.com/srikarvechalapu/f1-data-analysis)

**🔹 Retail Data Analytics**
End-to-end ETL workflow with data cleaning and EDA.
`Python` `Pandas` `SQL Server` · [View Repo](https://github.com/srikarvechalapu/retail-data-analytics-project-python-sql-integration)

**🔹 Online Payments Fraud Detection**
ML classification model for fraud using Decision Trees.
`Python` `Scikit-learn` · [View Repo](https://github.com/srikarvechalapu/online-payments-fraud-detection-with-machine-learning)

---

## 🏆 Education & Certifications

🎓 **MS – Management Information Systems**, University of Memphis (2022–2024)

🔧 AWS Cloud Practitioner · Tableau Desktop Specialist · Agile/Scrum

---

## 📊 GitHub Analytics

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=srikarvechalapu&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=srikarvechalapu&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=srikarvechalapu&theme=tokyonight&hide_border=true)

</div>
