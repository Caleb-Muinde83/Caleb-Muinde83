<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:1b2a41,100:6C63FF&height=240&section=header&text=Caleb%20Muinde&fontSize=62&fontColor=ffffff&fontAlignY=38&desc=Data%20Engineer%20%C2%B7%20Cloud%20Architect%20%C2%B7%20AI%2FML%20Integration&descSize=20&descAlignY=60" alt="Caleb Muinde: Data Engineer, Cloud Architect, AI/ML Integration" width="100%"/>

<a href="https://qu-bit.org/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3000&pause=1000&color=8B85FF&center=true&vCenter=true&width=900&height=40&lines=Production-grade+data+platforms;Streaming+systems+with+Kafka+%26+Flink;Cloud+architecture+on+GCP+%26+Azure;Local+LLMs%2C+RAG+%26+AI-ready+data+pipelines;Co-founder+of+Qu-Bit+open-source+community" alt="Typing animation"/>
</a>

<br/>

<img src="https://img.shields.io/badge/Nairobi%2C_Kenya-%F0%9F%87%B0%F0%9F%87%AA-1b2a41?style=flat-square&labelColor=1b2a41" alt="Nairobi, Kenya"/>
<img src="https://img.shields.io/badge/Open_to-Data_%26_Cloud_Engineering_roles-6C63FF?style=flat-square" alt="Open to roles"/>
<img src="https://img.shields.io/badge/Co--Founder-Qu--Bit-6C63FF?style=flat-square" alt="Co-Founder of Qu-Bit"/>

</div>

<br/>

## 👋 About

I design and build **reliable, production-grade data systems**: the pipelines, databases, and cloud infrastructure that analytics and AI depend on. I learn by building things that resemble real engineering environments, not isolated notebooks.

Today I'm extending that foundation toward **AI and ML**: integrating **local models**, retrieval, and AI workloads into data platforms, so the systems I build are ready for where the industry is heading.

<table>
<tr>
<td align="center" width="25%">
<img src="https://skillicons.dev/icons?i=kafka" width="52"/><br/><br/>
<b>Data Engineering</b><br/>
<sub>Streaming, CDC, ELT,<br/>orchestration</sub>
</td>
<td align="center" width="25%">
<img src="https://skillicons.dev/icons?i=gcp,azure" width="104"/><br/><br/>
<b>Cloud Architecture</b><br/>
<sub>GCP · Azure · Kubernetes<br/>Infrastructure as Code</sub>
</td>
<td align="center" width="25%">
<img src="https://skillicons.dev/icons?i=postgres" width="52"/><br/><br/>
<b>Database Engineering</b><br/>
<sub>Tuning, partitioning,<br/>zero-downtime migrations</sub>
</td>
<td align="center" width="25%">
<img src="https://skillicons.dev/icons?i=pytorch" width="52"/><br/><br/>
<b>AI / ML Integration</b><br/>
<sub>Local LLMs, RAG,<br/>AI-ready data platforms</sub>
</td>
</tr>
</table>

<br/>

## 🚀 Featured Projects

### ⚡ [Banking Fraud Platform](https://github.com/Caleb-Muinde83/banking-fraud-platform)
> *Real-time, event-driven fraud detection, with two independent risk engines running active-active.*

A containerized banking simulation built on **change data capture**. Transactions flow from PostgreSQL through Debezium into Kafka, where **Flink** handles stateful stream processing and graph-based fraud-ring detection while **Java and Python risk engines** score events in parallel. Alerts are aggregated and surfaced through full observability tooling.

<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/> <img src="https://img.shields.io/badge/Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white"/> <img src="https://img.shields.io/badge/Debezium-CDC-000000?style=flat-square&logo=debezium&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white"/> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

```mermaid
flowchart LR
    A[(Postgres)] --> B[Debezium]
    B --> C{{Kafka}}
    C --> D[Flink]
    C --> E[Java + Python<br/>Risk Engines]
    D --> F[Alerts]
    E --> F
    F --> G[(OpenSearch<br/>+ Grafana)]
```

<br/>

### 🗄️ [Enterprise DB Clinic](https://github.com/Caleb-Muinde83/enterprise-db-clinic)
> *A hands-on lab that recreates real production database problems, across three engines.*

Using one large-scale e-commerce/fintech dataset, this project works through **indexing, partitioning, schema drift, corruption recovery, zero-downtime migrations, and version upgrades**, with side-by-side comparison studies across PostgreSQL, MySQL, and SQL Server.

<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white"/> <img src="https://img.shields.io/badge/Indexing-555555?style=flat-square"/> <img src="https://img.shields.io/badge/Partitioning-555555?style=flat-square"/> <img src="https://img.shields.io/badge/Schema_Evolution-555555?style=flat-square"/> <img src="https://img.shields.io/badge/Migrations-555555?style=flat-square"/> <img src="https://img.shields.io/badge/Performance_Tuning-555555?style=flat-square"/>

<br/>

### 🏎️ [Formula 1 Data Platform](https://github.com/Caleb-Muinde83/f1_data_project)
> *End-to-end ELT: from raw telemetry to interactive dashboards.*

Extracts race and telemetry data from the **OpenF1 API**, stages it as Parquet, models it with **dbt**, and serves it through **DuckDB / BigQuery** to Streamlit dashboards. Orchestrated with **Airflow**, provisioned with **OpenTofu**, shipped through **CI/CD**, and extended with team-radio transcription.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white"/> <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white"/> <img src="https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white"/> <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black"/> <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white"/> <img src="https://img.shields.io/badge/OpenTofu-FFDA18?style=flat-square&logo=opentofu&logoColor=black"/> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>

```mermaid
flowchart LR
    A[OpenF1 API] --> B[Parquet]
    B --> C[dbt]
    C --> D[(DuckDB /<br/>BigQuery)]
    D --> E[Streamlit]
```

<br/>

## 🤖 Where I'm Taking My Work: AI-Ready Data Platforms

Good AI depends on good data engineering. I'm building the bridge between the two, applying data-platform discipline to AI workloads and running models **locally**, where cost, privacy, and control matter.

| | Focus | What it means in practice |
|:-:|---|---|
| 🧠 | **Local & open models** | Running and evaluating open-weight LLMs on my own hardware |
| 🔎 | **Retrieval (RAG)** | Embeddings, vector search, and grounding models in trusted data |
| 🏗️ | **AI-ready pipelines** | Clean, versioned, observable data feeding ML and LLM workloads |
| 🔁 | **MLOps foundations** | Reproducible environments, CI/CD, and monitoring for models |

<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>

<br/>

## 🛠️ Tech Stack

| | |
|:--|:--|
| **Languages** | <img src="https://skillicons.dev/icons?i=python,java,js,bash,&theme=dark" height="34"/> |
| **Streaming & Orchestration** | <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/> <img src="https://img.shields.io/badge/Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white"/> <img src="https://img.shields.io/badge/Debezium-000000?style=flat-square&logo=debezium&logoColor=white"/> <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white"/> |
| **Databases & Warehouses** | <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white"/> <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black"/> <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white"/> |
| **Analytics Engineering** | <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white"/> <img src="https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white"/> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/> |
| **Cloud & Infrastructure** | <img src="https://skillicons.dev/icons?i=gcp,azure,kubernetes,docker,terraform,linux,githubactions&theme=dark" height="34"/> <img src="https://img.shields.io/badge/OpenTofu-FFDA18?style=flat-square&logo=opentofu&logoColor=black"/> |
| **Observability** | <img src="https://skillicons.dev/icons?i=prometheus,grafana&theme=dark" height="34"/> <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white"/> |
| **AI / ML** | <img src="https://skillicons.dev/icons?i=pytorch,tensorflow&theme=dark" height="34"/> <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/> <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> |

<br/>

## 🎓 Certifications

| | Certification | Issued by | |
|:-:|---|---|:-:|
| <img src="https://skillicons.dev/icons?i=gcp" width="34"/> | **Professional Data Engineer** | Google Cloud | [Verify ↗](https://www.credly.com/badges/aede4782-60e1-41db-bc8f-ca2695c1d0cb/linked_in?t=t9wls5) |
| <img src="https://skillicons.dev/icons?i=gcp" width="34"/> | **Professional Cloud Architect** | Google Cloud | [Verify ↗](https://www.credly.com/badges/3c1cce87-ac05-42d0-8e74-21f54816cfd4/linked_in_profile) |
| <img src="https://skillicons.dev/icons?i=azure" width="34"/> | **Azure Data Fundamentals** | Microsoft | [Verify ↗](https://www.credly.com/badges/0e57c2c8-ce50-485a-bfe7-37666b273b67/linked_in_profile) |
| <img src="https://skillicons.dev/icons?i=kubernetes" width="34"/> | **Kubernetes and Cloud Native Associate (KCNA)** | CNCF / Linux Foundation | [Verify ↗](https://www.credly.com/badges/aab70a6d-d038-4372-9b61-ed562fcf62e8/linked_in_profile) |
| <img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@latest/icons/huaweicloud-color.svg" width="34"/> | **Cloud Developer Associate – AI (HCCDA-AI)** | Huawei | [Verify ↗](https://www.linkedin.com/in/caleb-muinde-2564a534b/overlay/Certifications/709748936/treasury/?profileId=ACoAAFd1rSIB1A0yTTftDkMplZ7-BaCXEfR4yMk) |

<br/>

## 🌍 Community: Qu-Bit

<div align="center">

<a href="https://qu-bit.org/"><img src="https://img.shields.io/badge/Qu--Bit-Open_Source_Data_Engineering_Community-6C63FF?style=for-the-badge&labelColor=1b2a41" alt="Qu-Bit"/></a>

**Build production-grade data engineering systems. No fluff. Just architecture, code, and execution.**

</div>

I'm a co-founder of Qu-Bit, an open-source community for learning by building. It covers the whole data stack: infrastructure, streaming, analytics, databases, distributed systems, and now AI.

<div align="center">

[🌐 **Website**](https://qu-bit.org/) &nbsp;·&nbsp; [💻 **GitHub Organization**](https://github.com/QuBitDECommunity) &nbsp;·&nbsp; [💬 **Discord**](https://discord.com/)

</div>

<br/>

## 📊 GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Caleb-Muinde83&show_icons=true&hide_border=true&bg_color=0d1117&title_color=8B85FF&icon_color=6C63FF&text_color=c9d1d9&count_private=true" alt="GitHub stats"/>
&nbsp;
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Caleb-Muinde83&hide_border=true&background=0d1117&ring=6C63FF&fire=8B85FF&currStreakLabel=8B85FF&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=8b949e" alt="Streak stats"/>

</div>

<br/>

## 📬 Get in Touch

I'm happy to connect with people building data platforms, cloud systems, and AI-powered tools, or hiring for them. Copy my email with one click:

```text
muindecaleb83@gmail.com
```

```text
+254794501179
```

<div align="center">

<a href="https://www.linkedin.com/in/caleb-muinde-2564a534b/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://medium.com/@calebmuinde4"><img src="https://img.shields.io/badge/Medium-Read_my_writing-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
<a href="https://wa.me/254794501179"><img src="https://img.shields.io/badge/WhatsApp-Message_me-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/></a>
<a href="https://qu-bit.org/"><img src="https://img.shields.io/badge/Qu--Bit-Join_the_community-6C63FF?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="Qu-Bit"/></a>

<br/><br/>

**Build. Learn. Share. Repeat.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,55:1b2a41,100:0d1117&height=110&section=footer" width="100%" alt=""/>

</div>
