## Hi, I'm Guilherme Fialho

**Data & Machine Learning Engineer (GenAI/LLMs)** · Rio de Janeiro, Brazil (UTC−3) · Open to remote roles · [gcfialho.github.io](https://gcfialho.github.io)

I build production GenAI products on top of solid data platforms: LLM agents and extraction
pipelines with evaluation and guardrails, and the pipelines, warehouses and infrastructure they
depend on, on AWS and Google Cloud. Certified on Google Cloud and Oracle Cloud Infrastructure (OCI).

### What I work on

**Data & ML Engineer** at a government-sector organization (confidential), since 2026, on AWS:

- **Transformation layer redesign**: moved Athena + Airflow transformations to SQLMesh with
  incremental models, column-level lineage and tests on every model: ~40% faster processing at
  ~65% lower cost. Infrastructure with Terraform, orchestrated by Azure DevOps CI pipelines.
- **Document-to-form automation**: an LLM pipeline that reads submitted documents, extracts the
  required fields with schema-constrained outputs and pre-fills a structured form, with a human
  review step before anything is committed.

At **IPNET by Vivo** (Google Cloud Premier Partner), 2023–2026, Data Engineer, then ML Engineer:

- **WhatsApp Contact Center AI**: an enterprise AI agent rolled out to ~1,000 businesses that
  answers customers using business actions and a knowledge base, keeps per-customer behavioral
  profiles in the CRM, scores its own answers in an evaluation layer and hands off to humans by
  email ticketing or Google Cloud CCAI.
- **Accelero**: a Google Chat assistant that reads the last 24 hours of conversations and
  delivers each person's action items every morning. Messages are processed in memory only,
  in line with LGPD.
- **Data platforms**: migrations of 1 TB+ tables with Cloud Composer and Dataflow, a
  three-layer government data lake, Waze traffic ETL, and Pulumi infrastructure-as-code that
  provisions governed GCP projects end to end.

### Featured projects

| Project | What it shows | Stack |
|---|---|---|
| [dental-analytics-medallion](https://github.com/gcfialho/dental-analytics-medallion) | Bronze/silver/gold pipeline on public health data, a data audit that fixed v1's numbers, and an LLM brief whose every figure is fact-checked against the warehouse | dbt · DuckDB · OpenAI · Streamlit |
| [lgpd-face-redactor](https://github.com/gcfialho/lgpd-face-redactor) | Blurs every face in a video except the data subject's, for LGPD/GDPR access requests: runs locally, fails safe and writes an audit record of every decision | Python · OpenCV (YuNet + SFace) |
| [marketing-report-generator](https://github.com/gcfialho/marketing-report-generator) | Funnel and channel analysis of messy CRM exports with honest statistics (Wilson intervals, Holm correction, a logistic model), validated against known true rates in simulation | pandas · statsmodels · SciPy |
| [uerj-marica-transit-network](https://github.com/gcfialho/uerj-marica-transit-network) | Graph model of a city bus network: centrality, shortest routes, reach by number of transfers and stop spacing, in a [bilingual explorer](https://gcfialho.github.io/uerj-marica-transit-network/) | NetworkX · MapLibre |
| [uerj-optimization-methods](https://github.com/gcfialho/uerj-optimization-methods) | Nelder–Mead from scratch that matches SciPy step for step, and a constrained design optimizer with Newton and quasi-Newton methods, both runnable in a [browser lab](https://gcfialho.github.io/uerj-optimization-methods/) | NumPy · Pyodide · Plotly |

Every project above is tested and type-checked (mypy strict) in CI. Live demos: the
[transit explorer](https://gcfialho.github.io/uerj-marica-transit-network/) and the
[optimization lab](https://gcfialho.github.io/uerj-optimization-methods/), both in Portuguese and English.

More coursework, rewritten as tested packages with measured results:
[uerj-advection-schemes](https://github.com/gcfialho/uerj-advection-schemes) (finite-difference and TVD schemes),
[uerj-intro-ai](https://github.com/gcfialho/uerj-intro-ai) (search, constraint satisfaction, an MLP from scratch) and
[uerj-linear-models](https://github.com/gcfialho/uerj-linear-models) (OLS inference and diagnostics).

### Toolbox

- **Languages:** Python, TypeScript/Node.js, SQL, Go
- **AI/ML:** LLM orchestration, agent workflows, RAG and embeddings, structured extraction,
  evaluation pipelines, MCP servers, Vertex AI, Google CCAI
- **Data:** SQLMesh, dbt, Airflow/Cloud Composer, Apache Beam/Dataflow, BigQuery, Athena, Snowflake, DuckDB
- **Backend & infrastructure:** FastAPI, Docker, Kubernetes, Terraform, Pulumi, Kafka, GitHub Actions, Azure DevOps
- **Cloud:** AWS (Athena, ECS, RDS, EC2), Google Cloud, Oracle Cloud Infrastructure (OCI)

### Certifications

- **Google Cloud:** Associate Data Practitioner, Cloud Digital Leader
- **Oracle Cloud Infrastructure:**
  - Professional: Generative AI, Data Science, DevOps, Developer
  - Associate: Foundations, AI Foundations, Data Platform

### Background

BSc in Computer Engineering at UERJ (Instituto Politécnico, 2020–2025), where I was a
Calculus I teaching assistant and led the computing projects at Serra Jr. Engenharia.
Co-founded the startup Opinei and took it from idea to investor presentations
(TIM Brasil Academic Working Capital, 2022).

Portuguese (native) · English (C1) · Spanish (advanced)

[LinkedIn](https://www.linkedin.com/in/guilherme-cagide-fialho/)
