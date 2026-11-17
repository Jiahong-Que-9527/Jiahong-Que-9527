<h1 align="center">Jiahong Que</h1>

<p align="center"><strong>Data/AI Platform Engineer for complex operational domains</strong><br>
Aviation and air cargo · Frankfurt am Main, Germany · <a href="https://www.linkedin.com/in/jiahong-que-215428258/">LinkedIn</a> · <a href="mailto:jiahong.que@fra-uas.de">Email</a></p>

<!-- [房玄龄·2026-11-17] Align the profile with platform responsibilities, verifiable evidence, and career positioning. -->

<!-- [房玄龄·2026-11-17] Update portfolio scope and measured results. -->

I build data pipelines and domain AI services for operational teams. In aviation, a missing observation and a quiet hour can look alike in the output. I work on making that distinction visible and on giving the next person a way to trace a result back to its source.

## Selected engineering work

SoloLakehouse is my personal portfolio of independent Data and AI platform engineering projects. Its two flagship cases follow different engineering responsibilities, building a reliable operational dataset and delivering a recoverable software service. [Portfolio map and project status](https://github.com/Jiahong-Que-9527/SoloLakehouse#readme)

**Fraport ADS-B Intelligence · Operational data engineering.** I built a local collector for aircraft observations around Frankfurt Airport. It reconciles hourly OpenSky data, writes Parquet with checksummed manifests, and resumes after an interruption. By November 2026, I had accepted and backed up **17 monthly batches**. In the pilot week, **168 of 168 hours** matched source aggregates. Recollecting an interrupted hour reproduced its checksum, and a subsequent rerun preserved the manifests. The next stage is to derive airport events with explicit rules for incomplete observations. [Acquisition results](https://github.com/Jiahong-Que-9527/SoloLakehouse/blob/main/Fraport-adsb-intelligence/01-opensky-acquisition/README.md) · [Recovery tests](https://github.com/Jiahong-Que-9527/SoloLakehouse/blob/main/Fraport-adsb-intelligence/01-opensky-acquisition/tests/test_run.py)

**DevOps Engineering · Software delivery and recovery.** I designed a seven-stage path for an independent service that reads synthetic electricity-meter audit reports. The first implementation milestone is a reproducible API with tested behavior for both an incomplete dataset and an unreadable report. Later stages follow the same service through image publication, release and rollback, GitOps, incident recovery, and onboarding a second service. [Development plan and acceptance criteria](https://github.com/Jiahong-Que-9527/SoloLakehouse/tree/main/Devops-engineering)

## Platform series

- **Google Cloud · Energy data delivery.** My local SMARD pipeline normalizes German electricity-load observations across daylight-saving changes. Its 2025 audit verified **35,040 continuous quarter-hour intervals** across 12 months. Two annual exports produced the same SHA-256 checksum. The series builds from this local baseline toward scheduled cloud delivery, APIs and events, governed data products, forecasting, and repeatable environment setup. [Annual audit](https://github.com/Jiahong-Que-9527/SoloLakehouse/blob/main/gcp/01-european-energy-pipeline/docs/year-2025-verification.md) · [Cloud roadmap](https://github.com/Jiahong-Que-9527/SoloLakehouse/tree/main/gcp)
- **Databricks · Financial lakehouse engineering.** Six planned cases use financial time series to explore Delta tables, scheduled ETL, change data capture, Unity Catalog governance, model delivery and reusable lakehouse environments. [Project briefs](https://github.com/Jiahong-Que-9527/SoloLakehouse/tree/main/databricks)

## Other work

**Finance engineering reference.** A [versioned self-hosted implementation](https://github.com/Jiahong-Que-9527/SoloLakehouse/tree/741e6da82cdc2cad207aa6ee707b8fb157b0174a/projects/finance) uses Dagster, Apache Iceberg, and Trino for ECB rates, exchange rates, and EWG ETF data. It shows dataset contracts, quality checks, and Bronze/Silver/Gold processing. This link is a historical implementation snapshot.

**Air-cargo knowledge interface.** [RecordChat](https://github.com/Jiahong-Que-9527/Recordchat) is a separate interface for IATA ONE Record and NE:ONE knowledge, built with Next.js, FastAPI, and Qdrant. It retrieves relevant material and presents source-linked answers. Source provenance and answer quality require their own evaluation; a citation alone does not establish correctness.

## Background and direction

I am a Research Assistant at Frankfurt University of Applied Sciences. My work in the [Digital Testbed Air Cargo](https://www.digital-testbed-air-cargo.com/) context includes air-cargo movement classification and explainable ML for airport ground operations. I bring more than ten years of experience across aviation technology, software-enabled systems, and logistics. My doctoral research at Maastricht University focused on natural language processing.

**Credentials:** Google Cloud Professional Cloud Architect · Databricks Certified AI Engineer Associate

I am interested in hands-on data, AI, and ML platform roles in Germany and the EU. If you work on data reliability, aviation, logistics, or practical AI systems, [let's connect](https://www.linkedin.com/in/jiahong-que-215428258/).
