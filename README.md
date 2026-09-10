# Thiago Morellato
Data Engineer based in Porto Alegre, Brazil.
I spent around 10 years in control rooms across heavy industry and power generation (ENGIE, CMPC, IFF), monitoring real-time SCADA telemetry, operating high-pressure boilers, and managing mission-critical physical systems. That journey included an on-site international assignment in China for power plant commissioning, which solidified my full professional English fluency and an engineering mindset where system downtime or dirty data simply isn't an option.
Today, I translate that operational rigor, SLA discipline, and deep industrial domain expertise into Data Engineering: designing reliable ETL/ELT pipelines, analytical lakehouses, and high-integrity data architectures.
### Core Technical Stack
- **Languages & Querying:** Python, SQL, DuckDB, PySpark.
- **Data Architecture & Storage:** Medallion Architecture (Bronze / Silver / Gold), Apache Parquet, Delta Lake, PostgreSQL, SQLAlchemy.
- **Orchestration & Tools:** Apache Airflow, Databricks, Docker, REST API Ingestion.
- **Data Quality & Testing:** Pytest, Schema Enforcement, Automated Validation.
### Featured Projects
- **[powerplant-telemetry-lakehouse](https://github.com/thiagomorellato/powerplant-telemetry-lakehouse):**
  End-to-end SCADA telemetry lakehouse for a 480 MW Combined-Cycle Power Plant (CCPP). Ingests high-frequency sensor readings (gas turbine exhaust, steam turbine pressure, ambient conditions) into a Medallion Parquet storage layer, computes thermodynamic efficiency KPIs (Heat Rate, condenser degradation) via zero-copy DuckDB SQL, and serves an operational dashboard backed by automated test suites.
  *Tech: Python, DuckDB, Parquet, Pytest, Plotly, Streamlit.*
- **[brazil-grid-worldcup-pipeline](https://github.com/thiagomorellato/brazil-grid-worldcup-pipeline):**
  Macro-scale analytics pipeline ingesting Brazil's National Electrical System Operator (ONS) open data. Models the 15,000+ MW instantaneous national demand collapse during Brazil's 2022 FIFA World Cup matches against 2021 pre-tournament baselines, analyzing regional disconnection shares and ONS generation flexibility constraints (thermal baseline lockouts vs. hydro maneuvering).
  *Tech: Python, ONS Open Data, DuckDB, Snappy Parquet, Pytest, Plotly, Streamlit.*
- **[pipeline-etl-vendas-python](https://github.com/thiagomorellato/pipeline-etl-vendas-python):**
  Modular ETL pipeline in Python handling automated REST API ingestion, data normalization, and relational persistence via SQLAlchemy and PostgreSQL.
  *Tech: Python, SQLAlchemy, PostgreSQL, Docker.*
- **[abrigoamigo](https://github.com/thiagomorellato/abrigoamigo):**
  Data structuring and deduplication initiative created during the May 2024 Rio Grande do Sul flood crisis to catalog, standardize, and match rescued animals across emergency shelters.
  *Tech: Python, Data Wrangling, Relational Modeling.*
### Contact
- LinkedIn: [linkedin.com/in/thiagomorellato](https://www.linkedin.com/in/thiagomorellato)
- Email: thiago.morellato@outlook.com
