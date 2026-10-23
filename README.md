# 2026 FAANG, Fintech & AWS Data Engineer + Agentic AI Master Tracker

An interactive, single-file personal command center and skill-tracking web application designed to guide a beginner-to-production transition into **Product-Company, FAANG, and Tier-1 Fintech Data Engineering roles**.

Built with zero external backend dependencies, this tracker synthesizes a **60-Day / 8-Week AWS & Product-Company Sprint**, a **30-Skill Technical Mastery Matrix**, an **Agentic AI & Model Context Protocol (MCP) Lab**, and **Production System Design Blueprints** into a responsive browser dashboard.

## Live Demo & Quick Start

- **GitHub Pages (Live App):** Once GitHub Pages is enabled on this repository (`Settings → Pages → Deploy from main branch`), access the live tracker at `https://<your-github-username>.github.io/<your-repo-name>/`.
- **Run Locally (Zero Setup):** Clone this repository and open `index.html` directly in any modern browser (Chrome, Edge, Brave, Firefox, or Safari). All progress, XP, checked milestones, and study notes persist automatically in browser `localStorage`, with one-click JSON export/import for cross-device backups.

```bash
git clone https://github.com/<your-github-username>/de-mastery-2026.git
cd de-mastery-2026
# Open index.html in your browser or via VS Code Live Server
```

## Core Modules & Features

| Tab / Module | Primary Focus | Key Technologies & Frameworks Covered |
| :--- | :--- | :--- |
| **1. 60-Day / 8-Week Sprint** | Day 1 local cluster setup (32GB RAM Docker workstation), 3-2-1 daily study rhythm, and week-by-week deliverables | [Harvard CS50P](https://cs50.harvard.edu/python), [StrataScratch](https://platform.stratascratch.com/coding), PostgreSQL 15, Docker, [AWS Certified Data Engineer – Associate](https://aws.amazon.com/certification/certified-data-engineer-associate/) |
| **2. Deep Skill Tracker** | 30 granular skills across 6 architectural phases with 4-stage mastery toggles (`Not Started` → `Learning` → `Built PoC` → `Mastered`), sub-skill checklists, notes, and GitHub proof links | Python, Analytical SQL, Kimball SCD Type 2, AWS (`S3`, `Glue`, `Redshift`, `Lambda`, `Athena`, `IAM`), [Apache Iceberg](https://iceberg.apache.org/), [Delta Lake](https://complereinfosystem.com/blogs/data-engineering-trends-2026), [DuckDB](https://duckdb.org/docs/current/), Polars, [Apache Arrow / Rust](https://techpreneurr.medium.com/can-rust-replace-java-in-the-spark-flink-world-a-data-engineers-view-in-2026-ae527d980dcb), [Apache Spark 4.x](https://spark.apache.org/docs/latest/), [Apache Kafka](https://kafka.apache.org/documentation/), [Apache Flink](https://flink.apache.org/), [Debezium CDC](https://debezium.io/documentation/reference/stable/index.html), [Trino](https://trino.io/docs/current/index.html), [dbt Core](https://docs.getdbt.com/), [Dagster](https://www.getorchestra.io/guides/dagster-pipelines-leverage-duckdb-polars-for-data-management), Apache Airflow, [Great Expectations](https://greatexpectations.io/), [Soda](https://soda.io/product/lineage), [OpenLineage](https://openlineage.io/docs/integrations/great-expectations/), [DataHub](https://docs.datahub.com/docs/lineage/openlineage), [ClickHouse](https://clickhouse.com/blog/clickhouse-airflow-provider), Apache Pinot |
| **3. Agentic AI & Prompt Vault** | 2026 autonomous pipeline patterns, reusable agent "Skills", copy-paste debugging prompts, and an 8-point Agent-Ready Pipeline Audit | [Model Context Protocol (MCP)](https://modelcontextprotocol.io/docs/2026-07-28/getting-started/intro), [Integrate.io MCP](https://www.integrate.io/blog/ai-agents-data-engineering-teams/), LangGraph, CrewAI, [Databricks Genie Code & Snowflake Cortex Code ("CoCo")](https://resources.rework.com/tools/ai-agents/best-ai-agents-for-data-engineering-2026), [dbt Semantic Layer](https://docs.getdbt.com/docs/dbt-apis/sl-python), [LlamaIndex MCP](https://developers.llamaindex.ai/python/framework/module_guides/mcp/), [Milvus](https://milvus.io/docs/milvus_for_agents.md), [Qdrant](https://github.com/qdrant/mcp-server-qdrant), pgvector, LanceDB |
| **4. FAANG, Fintech & 2030 Matrix** | Interactive stage-by-stage architecture diagrams, staff-level interview Q&As, and the 2027–2030 Sustainability & Autonomy Matrix | [Netflix Iceberg & Keystone Kafka](https://factorhouse.io/resources/iceberg/use-cases/netflix/), [Airbnb Kafka & SpinalTap CDC](https://factorhouse.io/articles/airbnb-kafka-architecture/), Stripe-style Double-Entry Ledgers, AWS Medallion Lakehouse |
| **5. Projects & Shadowing Hub** | 4 portfolio-grade capstone projects (20 trackable milestones) + curated GitHub repositories and industry educators | [DataTalksClub DE Zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp), [Zach Wilson DE Handbook](https://github.com/dataexpert-io/data-engineer-handbook), [Daniel Beach Practice](https://github.com/danielbeach/data-engineering-practice), [Joseph Machado Beginner DE Project](https://github.com/josephmachado/beginner_de_project), [ABZ-Aaron Reddit AWS Pipeline](https://github.com/ABZ-Aaron/Reddit-API-Pipeline) |
| **6. Readiness Analytics** | Real-time Chart.js Domain Mastery Radar, Skill Distribution Doughnut, Weekly Study Velocity Simulator, and JSON State Backup/Restore | Tailwind CSS, Chart.js, Browser `localStorage` |

## 6-Phase Technical Mastery Roadmap

1. **Phase 1 — Core Foundations (Weeks 1–3):** Python CS fundamentals ([Harvard CS50P](https://cs50.harvard.edu/python)), defensive REST API ingestion, generators (`yield`), OOP pipeline stages, analytical SQL window functions (`ROW_NUMBER`, `RANK`, `LAG/LEAD`, rolling frames), `EXPLAIN ANALYZE` query plans, Kimball dimensional modeling (`SCD Type 2`), Docker Compose, Terraform IaC, and zero-copy [Apache Arrow](https://techpreneurr.medium.com/can-rust-replace-java-in-the-spark-flink-world-a-data-engineers-view-in-2026-ae527d980dcb) memory concepts.
2. **Phase 2 — AWS Cloud & Modern Lakehouse Storage (Weeks 4–6):** Amazon S3 Medallion architecture (`Bronze` / `Silver` / `Gold`), AWS Glue, Amazon Redshift (`DISTKEY` / `SORTKEY`), AWS Lambda, Amazon Athena, IAM least-privilege security, Apache Parquet internals, [Apache Iceberg](https://iceberg.apache.org/) metadata trees (`CoW` vs. `MoR`, hidden partitioning), Delta Lake, and single-node vectorized engines ([DuckDB](https://duckdb.org/docs/current/) & Polars).
3. **Phase 3 — Distributed Compute & Real-Time Streaming:** [Apache Spark 4.x](https://spark.apache.org/docs/latest/) internals ([Catalyst Optimizer, Project Tungsten, Adaptive Query Execution (AQE)](https://www.techinterview.net/blog/mastering-apache-spark-faang-playbook), data skew & disk spill debugging), [Apache Kafka](https://kafka.apache.org/documentation/) (`KRaft`, idempotent producers, Dead-Letter Queues), [Apache Flink](https://flink.apache.org/) stateful stream processing (event-time watermarks, RocksDB checkpoints), and log-based Change Data Capture ([Debezium](https://debezium.io/documentation/reference/stable/index.html)).
4. **Phase 4 — DataOps, Contracts, Observability & FinOps:** Modular ELT transformations in [dbt Core](https://docs.getdbt.com/), idempotent DAG orchestration in Apache Airflow & [Dagster](https://www.getorchestra.io/guides/dagster-pipelines-leverage-duckdb-polars-for-data-management), Write-Audit-Publish (`WAP`) validation with [Great Expectations](https://greatexpectations.io/) & [Soda](https://soda.io/product/lineage), column-level lineage via [OpenLineage](https://openlineage.io/docs/integrations/great-expectations/) & [DataHub](https://docs.datahub.com/docs/lineage/openlineage), and Cloud FinOps / Green Compute optimization.
5. **Phase 5 — Agentic AI in Data Engineering:** Building scoped, read-only [Model Context Protocol (MCP)](https://modelcontextprotocol.io/docs/2026-07-28/getting-started/intro) servers, packaging repeatable DAG and SQL review standards as reusable Agent **Skills**, orchestrating self-healing triage agents with LangGraph & CrewAI, grounding [Text-to-SQL agents](https://www.sketricgen.ai/blog/best-ai-text-to-sql-agents) in the [dbt Semantic Layer](https://docs.getdbt.com/docs/dbt-apis/sl-python), and building hybrid vector pipelines ([Milvus](https://milvus.io/docs/milvus_for_agents.md), [Qdrant](https://github.com/qdrant/mcp-server-qdrant), `pgvector`, `LanceDB`).
6. **Phase 6 — FAANG & Fintech System Design:** Sub-second user-facing OLAP ([ClickHouse](https://clickhouse.com/blog/clickhouse-airflow-provider) & Apache Pinot), immutable double-entry fintech ledgers with automated T+0/T+1 reconciliation, Data Mesh governance, and structured system design mock loops.

## Capstone Portfolio Projects Tracked in This Repo

1. **Project 1 (Batch ELT Foundation):** Public REST API → AWS S3 / PostgreSQL → Modular `dbt` Star Schema (`SCD Type 2`) → Dockerized Apache Airflow DAG → `Great Expectations` / `Soda` Quality Gate → GitHub Actions CI.
2. **Project 2 (10M+ Row Medallion Cloud Lakehouse):** AWS S3 (`Bronze` / `Silver` / `Gold`) → `PySpark` & `Apache Iceberg` / `Delta Lake` → Serverless `AWS Athena` + Single-node `Polars` & `DuckDB` FinOps benchmark.
3. **Project 3 (Real-Time Streaming & Fintech Anomaly Detector):** `PostgreSQL` + `Debezium CDC` / Python Event Producer → 3-Partition `Apache Kafka` → Stateful `Apache Flink` / `Spark Streaming` consumer → Dead-Letter Queue (`DLQ`) + `ClickHouse` / `Redshift` real-time business dashboard.
4. **Project 4 (Agentic AI Data Platform):** Custom read-only Python `MCP Server` + `dbt Semantic Layer` governed Text-to-SQL agent + `Qdrant` / `Milvus` hybrid vector pipeline + `LangGraph` self-healing DAG triage agent.

## Repository Structure

```text
.
├── index.html          # Self-contained interactive tracker web application (HTML + Tailwind CSS + Chart.js)
├── README.md           # Project overview, roadmap architecture, and setup documentation
└── skills/             # (Optional) Reusable AI Agent Skill definitions for DAG review & SQL audits
```

## Backing Up & Restoring Progress

Because this app runs 100% client-side for privacy and speed:
1. Click **Backup / Restore** in the top-right header of the web app.
2. Click **Copy JSON** to save a snapshot of your XP, checked tasks, custom skills, and personal study notes.
3. Paste that JSON into the modal on any other computer or mobile browser and click **Import & Apply** to sync your state.
