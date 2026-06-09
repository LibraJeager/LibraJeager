<div align="center">

# Le Nguyen Thanh Cong

### Data Engineer Intern Candidate

<p><em>Turning raw data into structured systems, analytical clarity, and practical intelligence.</em></p>

<p>
  <a href="https://www.linkedin.com/in/libra173/">
    <img src="https://img.shields.io/badge/LinkedIn-libra173-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:conglnt.work@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Location-Ho_Chi_Minh_City-111827?style=for-the-badge" />
  <img src="https://komarev.com/ghpvc/?username=LibraJeager&style=for-the-badge&label=Profile+Views" />
</p>

</div>

---

## About Me

Final-year Information Systems student at UIT (GPA 8.23/10), focused on **data engineering** and **pipeline-oriented thinking**.

Most of my projects begin with **raw, messy, real-world inputs** and move toward **cleaner pipelines, stronger features, and usable outputs**.

I am especially interested in:
- data preprocessing and feature design
- streaming and distributed data systems
- leakage-aware machine learning workflows
- production-minded project structure

---

## Toolkit

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
</p>

<p>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-EC6B23?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ETL-0F172A?style=for-the-badge" />
</p>

---

## Selected Work

### [Market Overview Pipeline](https://github.com/LibraJeager/market-pipeline)
**Data Engineering Project · 2026**

**Problem**  
Raw stock market data arrives fragmented and unaggregated — one record per ticker per day with no derived metrics. Analysts need a clean, enriched dataset that surfaces trend, volatility, and volume signals across a curated basket of stocks.

**System Design**  
Built an automated **batch ELT pipeline** that ingests daily OHLCV data for the **S&P 500 top 30 stocks**, loads into PostgreSQL, and transforms through a **dbt layered architecture** (staging → intermediate → mart) — orchestrated by **Apache Airflow** on a daily schedule.

**Result**  
Processed **7,530 records** across 30 tickers × 251 trading days, producing analytics-ready tables with **daily return, MA7/MA30/MA90, rolling volatility, cumulative return, and volume spike detection** — refreshed automatically every trading day.

**Stack**  
`Python` `Apache Airflow` `dbt` `PostgreSQL` `Docker` `yfinance` `ETL`

---

### [VEEPS — Spatio-Temporal Edge AI for V2X Traffic Forecasting](https://github.com/LibraJeager/v2x-spatio-temporal)
**Graduation Project · Ongoing**

**Problem**  
Forecast traffic congestion **15 minutes ahead** in a V2X setting using **early spatio-temporal signals** instead of reactive speed-only indicators.

**System Design**  
Built a **streaming ETL pipeline** for large-scale SUMO FCD XML, engineered **FDR-based spatio-temporal features**, trained an **XGBoost** model, and deployed inference to a **Dockerized RSU-like edge node** over **MQTT**.

**Result**  
Processed **13.6 GB** of telemetry with memory usage kept **below 50 MB**, and achieved **R² = 0.8919** for **15-minute-ahead forecasting**.

**Stack**  
`Python` `XGBoost` `Docker` `MQTT` `SUMO` `ETL` `Edge AI`

---

> More repositories are being prepared for release.

---

## Profile Snapshot

- **Education:** University of Information Technology (UIT) — Information Systems
- **Current Goal:** Build stronger foundations in data infrastructure, scalable processing, and production-minded project work
- **Certification:** Google Data Analytics Specialization
