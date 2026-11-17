<h1 align="center">Jiahong Que</h1>

<p align="center"><strong>Data/AI Platform Engineer for complex operational domains</strong><br>
Aviation and air cargo · Frankfurt am Main, Germany · <a href="https://www.linkedin.com/in/jiahong-que-215428258/">LinkedIn</a> · <a href="mailto:jiahong.que@fra-uas.de">Email</a></p>

<!-- [房玄龄·2026-11-17] Align the profile with platform responsibilities, verifiable evidence, and career positioning. -->

I build data pipelines and domain-specific AI services that people can inspect, rerun, and recover. Aviation is my main proof domain: aircraft observations are incomplete, operational terms are easy to misread, and a successful run means little unless its output can be checked later.

My work connects **source meaning → reliable data → usable AI → operating evidence**. I am interested in Data/AI Platform Engineering roles where I can own that path from an operational problem to a trustworthy result.

## My engineering approach

| Responsibility | What I work on | Review the evidence |
|---|---|---|
| **Understand the source** | Define observation meaning, coverage, time windows, and known gaps. | [OpenSky acquisition design](https://github.com/Jiahong-Que-9527/SoloLakehouse/blob/main/Fraport-adsb-intelligence/01-opensky-acquisition/docs/design.md) |
| **Engineer the data path** | Build Python ingestion, contracts, validation, Parquet outputs, and batch acceptance. | [Aviation implementation](https://github.com/Jiahong-Que-9527/SoloLakehouse/tree/main/Fraport-adsb-intelligence/01-opensky-acquisition) |
| **Own reliability** | Reconcile source and output, record checksums, resume work, verify backups, and test reruns. | [Recovery tests](https://github.com/Jiahong-Que-9527/SoloLakehouse/blob/main/Fraport-adsb-intelligence/01-opensky-acquisition/tests/test_run.py) · [benchmark](https://github.com/Jiahong-Que-9527/SoloLakehouse/blob/main/Fraport-adsb-intelligence/01-opensky-acquisition/docs/benchmark-report.md) |
| **Make AI accountable** | Separate domain knowledge, cited sources, answer quality, and service availability. | [RecordChat](https://github.com/Jiahong-Que-9527/Recordchat) |

This is the design principle behind **[SoloLakehouse](https://github.com/Jiahong-Que-9527/SoloLakehouse)**: start with data meaning, preserve evidence through each step, and make failure and recovery part of the architecture. It is a personal platform engineering reference with separate workloads and explicit delivery boundaries.

## Selected work

**Frankfurt aviation data foundation.** In [Fraport ADS-B Intelligence](https://github.com/Jiahong-Que-9527/SoloLakehouse/tree/main/Fraport-adsb-intelligence), I am building a historical dataset of aircraft observations around Frankfurt Airport. The implemented OpenSky path collects state vectors and flight records, writes checksummed Parquet manifests, distinguishes source gaps from empty observations, and accepts batches after validation. A pilot-week reconciliation matched **168 of 168 hours**. An interruption and repeat-run check reproduced the committed checksum and preserved the manifests. [Status and evidence](https://github.com/Jiahong-Que-9527/SoloLakehouse/blob/main/Fraport-adsb-intelligence/01-opensky-acquisition/README.md)

The raw research data stays private. Local Silver/Gold processing, cloud analytics, and model serving are staged work.

**Finance engineering reference.** A [versioned self-hosted implementation](https://github.com/Jiahong-Que-9527/SoloLakehouse/tree/741e6da82cdc2cad207aa6ee707b8fb157b0174a/projects/finance) uses Dagster, Apache Iceberg, and Trino for ECB rates, exchange rates, and EWG ETF data. It shows dataset contracts, quality checks, and Bronze/Silver/Gold processing. This link is a historical implementation snapshot.

**Air-cargo knowledge interface.** [RecordChat](https://github.com/Jiahong-Que-9527/Recordchat) is a separate interface for IATA ONE Record and NE:ONE knowledge, built with Next.js, FastAPI, and Qdrant. It retrieves relevant material and presents source-linked answers. Source provenance and answer quality require their own evaluation; a citation alone does not establish correctness.

## Background and direction

I am a Research Assistant at Frankfurt University of Applied Sciences. My work in the [Digital Testbed Air Cargo](https://www.digital-testbed-air-cargo.com/) context includes air-cargo movement classification and explainable ML for airport ground operations. I bring more than ten years of experience across aviation technology, software-enabled systems, and logistics. My doctoral research at Maastricht University focused on natural language processing.

**Credentials:** Google Cloud Professional Cloud Architect · Databricks Certified AI Engineer Associate

I am interested in hands-on data, AI, and ML platform roles in Germany and the EU. If you work on data reliability, aviation, logistics, or practical AI systems, [let's connect](https://www.linkedin.com/in/jiahong-que-215428258/).
