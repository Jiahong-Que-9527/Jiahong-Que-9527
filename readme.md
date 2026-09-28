<h1 align="center">Jiahong Que</h1>

<p align="center"><strong>AI &amp; Data Platform Engineer · Aviation &amp; Air Cargo</strong><br>
Frankfurt am Main, Germany · <a href="https://www.linkedin.com/in/jiahong-que-215428258/">LinkedIn</a> · <a href="mailto:jiahong.que@fra-uas.de">Email</a></p>

I work at the intersection of **operational logistics, applied AI, and data-platform engineering**. At Frankfurt University of Applied Sciences, I build AI and data workflows for German air-cargo and airport operations. My broader background spans more than ten years in aviation technology, software-enabled systems, and logistics.

The question behind my work is practical: **how do we move from a promising model or industry data standard to a system that other people can reproduce, inspect, and use?** I focus on the data contracts, orchestration, evaluation, APIs, lineage, and operational evidence needed along that path.

## From air-cargo data exchange to AI-ready platforms

| Layer | Representative work | What it demonstrates |
|---|---|---|
| **Operational AI** | Air-cargo movement classification and explainable airport ground-operations ML within the [Digital Testbed Air Cargo](https://www.digital-testbed-air-cargo.com/) context | Domain understanding, sensor/operational data processing, model evaluation, and communication with logistics workflows. |
| **Industry knowledge interface** | [RecordChat](https://github.com/Jiahong-Que-9527/Recordchat) | A citation-first assistant for IATA ONE Record and NE:ONE, connecting public specifications and ontology to usable, source-linked answers. |
| **Platform foundations** | [SoloLakehouse](https://github.com/Jiahong-Que-9527/SoloLakehouse) | A self-hosted reference platform for governed data flows, reproducible analytics, ML tracking, lineage, and operational evidence. |

These are **complementary pieces of one engineering direction**, not a claim that they already form a single deployed enterprise platform. SoloLakehouse's current reference pipeline uses **ECB and EWG financial-market data**; the air-cargo work and RecordChat are separate domain applications.

## Explore the engineering

### [SoloLakehouse](https://github.com/Jiahong-Que-9527/SoloLakehouse) — governed Data & AI platform

- Docker Compose runtime integrating **Apache Iceberg, Trino, Dagster, MLflow, OpenMetadata, MinIO, and Superset**.
- A Bronze → Silver → Gold data path, versioned dataset contracts, quality checks, and evidence that links orchestration runs to table snapshots and metadata.
- Documented architecture decisions and operational checks, with the boundary between what runs today and the planned Kubernetes migration made explicit in the [README](https://github.com/Jiahong-Que-9527/SoloLakehouse#readme).

### [RecordChat](https://github.com/Jiahong-Que-9527/Recordchat) — source-grounded air-cargo AI

- A **Next.js + FastAPI + Qdrant** application for questions about ONE Record concepts, JSON-LD, APIs, and NE:ONE.
- Reviewed public sources, retrieval evaluation, source citations, and template-based JSON-LD examples keep answers inspectable rather than merely fluent.
- The [README](https://github.com/Jiahong-Que-9527/Recordchat#readme) shows the interface, local run path, and current limits.

## Background and direction

I am a Research Assistant / Doctoral Researcher at Frankfurt University of Applied Sciences, working on applied AI in aviation and logistics. Earlier work includes aviation engineering, software-enabled systems, and research; my doctoral work at Maastricht University focused on natural language processing.

**Core tools:** Python · Docker · Apache Iceberg · Trino · Dagster · MLflow · FastAPI · Qdrant

**Credentials:** Google Cloud Professional Cloud Architect · Databricks Certified AI Engineer Associate

I am interested in **AI Platform, Data Platform, and ML Platform Engineering** roles where domain understanding and reliable delivery matter together—particularly in aviation, logistics, and other complex operational environments.
