
<!-- ====================================================== -->
<!-- SHIV BHADOURIA | DATA ENGINEER PROFILE                 -->
<!-- ====================================================== -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:090979,50:0077B6,100:00D4FF&height=210&section=header&text=SHIV%20BHADOURIA&fontSize=48&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=DATA%20ENGINEER%20%7C%20AZURE%20%7C%20BIG%20DATA&descAlignY=60&descSize=17" alt="Shiv Bhadouria Data Engineer"/>

<a href="https://readme-typing-svg.demolab.com">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=2500&pause=700&color=38BDF8&center=true&vCenter=true&width=800&lines=Engineering+Reliable+Data+Pipelines;Azure+Data+Factory+%7C+Databricks+%7C+PySpark;Building+Metadata-Driven+ETL%2FELT+Workflows;Turning+Raw+Data+Into+Business+Insights" alt="Animated Data Engineering tagline"/>
</a>

<br/><br/>

<a href="https://linkedin.com/in/shivbhadouria">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:shivbhadouria66@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://drive.google.com/file/d/1Z2IZ-tGeCM0OlM75z6wK06lKqZ26qdpk/view?usp=sharing">
<img src="https://img.shields.io/badge/Resume-View_CV-16A34A?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume"/>
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=shivbhadouria&style=flat-square&color=0077B6&label=PROFILE+VIEWS" alt="Profile views"/>

</div>

---

## ⚡ DATA ENGINEERING CAPABILITIES

<table>
<tr>
<td width="50%" valign="top">

### 🔄 Data Pipeline Engineering

- Metadata-driven ingestion
- ETL/ELT pipeline development
- Full and incremental loads
- Watermark-based processing
- Pipeline parameterization
- Error handling and retries

</td>
<td width="50%" valign="top">

### ⚙️ Distributed Data Processing

- Python and PySpark transformations
- SQL joins and aggregations
- Deduplication and data validation
- Incremental MERGE operations
- Spark partitioning concepts
- Data processing optimization

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏗️ Data Architecture

- Bronze, Silver and Gold layers
- Medallion architecture
- Data lake organization
- Analytics-ready datasets
- Data warehousing fundamentals
- Relational data modeling

</td>
<td width="50%" valign="top">

### 🔐 Production Engineering

- Pipeline control and audit tables
- Secret management with Key Vault
- Git-based version control
- CI/CD workflows
- Pipeline monitoring and logging
- Data quality and reliability

</td>
</tr>
</table>

---

## 🧰 TECHNOLOGY STACK

<div align="center">

### ☁️ Cloud & Data Platforms

<a href="https://azure.microsoft.com/">
<img src="https://skillicons.dev/icons?i=azure" height="55" alt="Microsoft Azure"/>
</a>
<a href="https://aws.amazon.com/">
<img src="https://skillicons.dev/icons?i=aws" height="55" alt="AWS"/>
</a>
<a href="https://spark.apache.org/">
<img src="https://skillicons.dev/icons?i=spark" height="55" alt="Apache Spark"/>
</a>
<img src="https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure Data Factory"/>
<img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks"/>

### 💻 Programming & Databases

<a href="https://www.python.org/">
<img src="https://skillicons.dev/icons?i=python" height="55" alt="Python"/>
</a>
<a href="https://www.mysql.com/">
<img src="https://skillicons.dev/icons?i=mysql" height="55" alt="MySQL"/>
</a>
<a href="https://www.postgresql.org/">
<img src="https://skillicons.dev/icons?i=postgres" height="55" alt="PostgreSQL"/>
</a>
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="PySpark"/>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server"/>

### 🔧 Tools & Engineering Workflow

<a href="https://git-scm.com/">
<img src="https://skillicons.dev/icons?i=git" height="55" alt="Git"/>
</a>
<a href="https://github.com/">
<img src="https://skillicons.dev/icons?i=github" height="55" alt="GitHub"/>
</a>
<img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="CI/CD"/>
<img src="https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge" alt="Delta Lake"/>

### 🌱 Currently Exploring

<img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt"/>
<img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Apache Airflow"/>
<img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" alt="Snowflake"/>

</div>

---

## 🏗️ DATA PIPELINE ARCHITECTURE

<div align="center">

```mermaid
flowchart LR
    A["📥 Sources<br/>Files • APIs • SQL"] --> B["🔄 Azure Data Factory"]
    B --> C["🥉 Bronze<br/>Raw Data"]
    C --> D["⚡ Databricks<br/>PySpark / Delta"]
    D --> E["🥈 Silver<br/>Clean Data"]
    E --> F["🥇 Gold<br/>Curated Data"]
    F --> G["📊 Analytics"]

    H[("🗄️ SQL Audit Tables")] -.-> B
    I["🔐 Key Vault"] -.-> B
    J["🚀 GitHub CI/CD"] -.-> D

    classDef source fill:#102A43,stroke:#38BDF8,color:#FFFFFF
    classDef process fill:#123B56,stroke:#00D4FF,color:#FFFFFF
    classDef layer fill:#1D3557,stroke:#60A5FA,color:#FFFFFF
    classDef output fill:#14532D,stroke:#4ADE80,color:#FFFFFF

    class A source
    class B,D process
    class C,E layer
    class F,G output
```

</div>

<p align="center">
<i>Ingest → Transform → Validate → Curate → Deliver</i>
</p>

---

## 🏢 ENGINEERING EXPERIENCE & PRACTICAL CAPABILITIES

<table>
<tr>
<th>Area</th>
<th>Technical capabilities</th>
</tr>
<tr>
<td>📥 Ingestion</td>
<td>Azure Data Factory pipelines, parameterized datasets, source-to-target processing and incremental loading</td>
</tr>
<tr>
<td>⚡ Transformation</td>
<td>Python, PySpark, SQL joins, aggregations, deduplication and MERGE patterns</td>
</tr>
<tr>
<td>🗄️ Storage</td>
<td>Azure Data Lake concepts, Delta Lake, relational databases and medallion architecture</td>
</tr>
<tr>
<td>🔎 Reliability</td>
<td>Control tables, audit logging, pipeline monitoring, error handling and data validation</td>
</tr>
<tr>
<td>🚀 Delivery</td>
<td>Git, GitHub, CI/CD workflows, deployment practices and maintainable pipeline design</td>
</tr>
</table>

<p align="center">
<i>Practical data engineering capabilities spanning ingestion, transformation, orchestration, storage and delivery.</i>
</p>

---

## 📈 GITHUB CONTRIBUTION UNIVERSE

<div align="center">

<p>
<i>Real contribution history. A snake that follows the contribution calendar.</i>
</p>

<!-- Real GitHub contribution heatmap -->
<a href="https://github.com/shivbhadouria">
<img width="100%" src="https://ghchart.rshah.org/00D4FF/shivbhadouria" alt="GitHub contribution history"/>
</a>

<br/>

<!-- Automatically generated animated snake -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shivbhadouria/shivbhadouria/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/shivbhadouria/shivbhadouria/output/github-contribution-grid-snake.svg"/>
  <img width="100%" src="https://raw.githubusercontent.com/shivbhadouria/shivbhadouria/output/github-contribution-grid-snake.svg" alt="Animated snake following actual GitHub contributions"/>
</picture>

<br/><br/>

<a href="https://github.com/shivbhadouria?tab=overview">
<img src="https://img.shields.io/badge/Explore-My_Contribution_History-0077B6?style=for-the-badge&logo=github&logoColor=white" alt="View contributions"/>
</a>

<a href="https://github.com/shivbhadouria?tab=repositories">
<img src="https://img.shields.io/badge/Explore-My_Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="View repositories"/>
</a>

</div>

---

## 📊 GITHUB ANALYTICS

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=shivbhadouria&show_icons=true&theme=tokyonight&hide_border=true&hide=commits,contribs,prs,issues&rank_icon=github" alt="GitHub statistics"/>

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shivbhadouria&layout=compact&theme=tokyonight&hide_border=true" alt="Most used programming languages"/>

<img width="85%" src="https://streak-stats.demolab.com?user=shivbhadouria&theme=tokyonight&hide_border=true" alt="GitHub contribution streak"/>

</div>

---

## 🤝 LET'S CONNECT

<div align="center">

<a href="https://linkedin.com/in/shivbhadouria">
<img src="https://img.shields.io/badge/LinkedIn-Shiv_Bhadouria-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

<a href="mailto:shivbhadouria66@gmail.com">
<img src="https://img.shields.io/badge/Email-Let's_Talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

<br/><br/>

<b>⚡ Engineering Data. Building Pipelines. Enabling Insights. ⚡</b>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:090979,50:0077B6,100:00D4FF&height=120&section=footer&animation=fadeIn" alt="Animated footer"/>

</div>
