<h1 align="center">Hi, I'm Mahendra Mahato 👋</h1>

<p align="center">
  <b>Full-Stack Software Engineer</b> · <b>Data Engineering</b> · <b>AI Agents</b><br/>
  M.S. Computer Science @ Boise State University · Boise, ID
</p>

<p align="center">
  <a href="https://mahendra-mahato.com"><img src="https://img.shields.io/badge/Portfolio-mahendra--mahato.com-000000?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
  <a href="https://linkedin.com/in/mahendramahato"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:mahendramahato@u.boisestate.edu"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

I'm a full-stack engineer with 3+ years of experience shipping web applications: back-end services in **Java/Spring Boot** and **Python/FastAPI**, front-ends in **React**. I also build streaming data pipelines and AI agent systems. I care about the whole lifecycle, from design and code review to containerization, CI/CD, monitoring, and load and chaos testing.

## 🚀 Featured Projects

### 🎵 [Soundly — Distributed Music Streaming Platform](https://m-stream.duckdns.org)
`React` `Spring Boot ×3` `Redis` `MySQL` `Docker` `Oracle Cloud` `Prometheus` `Grafana`
- Built and deployed a music streaming service on Oracle Cloud with Docker, HTTPS, and CI/CD gated by **49 automated tests**.
- Load-tested at **~600 req/s, 57 ms p95, 0% errors**. Chaos testing exposed a cache outage that hung the API for 5 minutes, which I cut to a **0.2 s fallback**.
- Stateless HMAC-signed session auth across 3 instances, plus Prometheus/Grafana monitoring with email alerting.

### 🤖 [Pipeline Copilot — Autonomous Incident Diagnosis for Data Pipelines](https://pipeline-copilot.duckdns.org) · [code](https://github.com/mahendramahato/pipeline-copilot)
`LangGraph` `MCP` `RAG` `Python` `Docker` `GitHub Actions`
- An AI on-call agent that diagnoses failures in a live Kafka/Spark/AWS pipeline using **21 read-only tools** across Airflow, Athena, Glue, and Docker.
- Verifiable diagnoses: SQL checks, question screening, and evidence that must match tool output word for word. It diagnosed **all 7 injected failure types** correctly at **~$0.09 per investigation**.
- Its monitor alerts only on new failures, and it caught a **real silent Glue partition failure** in production.

### 🌎 [Real-Time Weather & Seismic Anomaly Detection Pipeline](https://weather-seismic.duckdns.org) · [code](https://github.com/mahendramahato/weather-seismic-pipeline)
`Kafka` `Spark Structured Streaming` `S3` `AWS Glue` `Athena` `Airflow` `FastAPI` `DuckDB` `React`
- Streams live NOAA weather data (15 stations) and USGS earthquake data through Kafka into Spark Structured Streaming, with checkpointed, fault-tolerant processing and deduplication.
- Detects anomalies in real time with a seasonal median/MAD baseline that removed false positives caused by daily temperature cycles.
- Raw/curated S3 lake with idempotent Glue ETL and Athena partition projection (**266× less data scanned**), orchestrated nightly by Airflow.
- Self-healing Docker services, least-privilege IAM, and GitHub Actions CI/CD with OIDC and smoke tests. Powers a public dashboard at **~$0.30/month** in query cost.

## 💼 Experience

| Role | Company | Dates |
|---|---|---|
| **Business Analyst** | Zareen Enterprise LLC, Lafayette, LA | May 2024 – Dec 2025 |
| **Full Stack Developer** | Srimatrix Inc., Dallas, TX | Mar 2023 – May 2024 |
| **Software Developer** | CGI Capstone Program, Lafayette, LA | Aug 2022 – Dec 2022 |

- **Zareen:** SQL Server OLAP cubes that improved inventory forecasting accuracy by **20%+**, and Python reporting automation that cut report time by **75%**.
- **Srimatrix:** Java/Spring Boot and React apps for industry clients, and Docker plus Jenkins CI/CD that reduced deployment cycle time by **30%**.

## 🛠️ Tech Stack

**Languages**<br/>
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**Full-Stack**<br/>
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

**Data Engineering & Cloud**<br/>
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20(S3·Glue·Athena)-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat&logo=oracle&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)

**DevOps**<br/>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**AI & ML**<br/>
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT--4o-412991?style=flat&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB%20(RAG)-FF6B6B?style=flat)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

## 🎓 Education

- **M.S. Computer Science**, Boise State University (expected Dec 2027)
- **B.A.S. Computer Science**, University of Louisiana at Lafayette (Dec 2022)

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=mahendramahato&show_icons=true&theme=radical&hide_border=true"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mahendramahato&layout=compact&theme=radical&hide_border=true"/>
</p>

<p align="center"><i>Open to software engineering, data engineering, and AI engineering roles.</i></p>
