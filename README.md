# Hi, I'm Chouaib 👋
### Aspiring Data Engineer | Python • SQL • DuckDB • dbt • Databricks

I'm a **Technical Support Specialist** transitioning into **Data Engineering** through rigorous self-study and production-grade projects.

My support background has trained me to investigate edge cases, diagnose complex bugs, communicate technical issues clearly, and keep user needs central. I bring that same reliability-first mindset to building resilient data pipelines.

---

## 🛠️ What I'm building

### 🏎️ [Motorsport Data Pipeline](https://github.com/chouaibmouidis-py/Moto_Sport_BMW_Pipeline)
A standalone Python and DuckDB ELT pipeline turning official IMSA race reports into traceable, tested analytical models, focusing on BMW entries.

- **Data Lineage & Integrity:** Ingest raw JSON reports, compute SHA-256 byte fingerprints, and enforce Bronze-to-Silver data contracts.
- **Scale:** Processes pit-stop reports containing **1,791 stops** (Daytona 24h, Road America, Long Beach) and official classification reports.
- **Relational Normalization:** Links sessions, cars, drivers, and stops with custom handling for edge cases (clock-time overflow across midnight).
- **Data Quality & Reconciliation:** Automated SQL checks for foreign-key consistency, missing values, and duration cross-checks (sum of stops vs. official race totals).
- **Crash-Safety:** Publishes outputs into immutable run directories and performs **atomic pointer swaps** (`current.json`) only upon successful full validation.

*Independent learning project, not affiliated with BMW or IMSA.*

### 📊 [GH Archive Analytics](https://github.com/chouaibmouidis-py/Gh_Archive_Analytics)
A Python, DuckDB, and dbt project analyzing GitHub activity at scale. Explores partitioned Parquet storage, incremental models, deduplication strategies, and automated data testing.

### 🏢 [Job Postings Analytics](https://github.com/chouaibmouidis-py/DBT_project)
An end-to-end analytics engineering project implemented across DuckDB and **Databricks**. Demonstrates dimensional modeling (Kimball), incremental loading, **SCD Type 2 snapshots**, and orchestration.

---

## 🌱 Technical Toolkit

- **Data Engineering:** Medallion Architecture (Raw/Bronze/Silver), Data Lineage, Parquet, Atomic Writes, Dimensional Modeling, SCD Type 2.
- **Languages:** Python (Unit Testing, Mocks, CLI, JSON processing), SQL (Advanced CTEs, Window Functions, Set Differences, Quality Checks).
- **Tools & Ecosystem:** DuckDB, dbt, Databricks, uv, Git, GitHub Actions.
- **Exploring:** Apache Iceberg, BigQuery, and Google Cloud Platform.

---

## 🎓 Learning Milestones

- **Certifications (freeCodeCamp):**
  - Scientific Computing with Python
  - Data Analysis with Python
  - Relational Database
- **Methodology:** I use official documentation and AI-assisted coaching as a sparring partner (code review and architectural challenge), then practice writing, debugging, testing, and defending every line of code myself.
- **Languages:** French (Native/Main working language), English (Working proficiency in technical reading and writing).

---

## 🎯 Next Steps

My goal is to join an engineering team as a **Junior Data Engineer**, where I can contribute to reliable data infrastructure, learn from code reviews, and deliver value on real business problems.

Long-term, I am working toward the **Google Cloud Professional Data Engineer** certification and contributing to open-source data tooling.

---

## 📫 Let's connect

- **LinkedIn:** [Chouaib Mouid](https://www.linkedin.com/in/chouaib-mouid-200893438)
- **Email:** [chouaibmouidis@gmail.com](mailto:chouaibmouidis@gmail.com)
- **GitHub:** [github.com/chouaibmouidis-py](https://github.com/chouaibmouidis-py)
