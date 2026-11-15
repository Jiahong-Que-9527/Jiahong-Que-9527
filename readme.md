<h1 align="center">Jiahong Que</h1>

<p align="center"><strong>Data &amp; AI Platform Engineer · Aviation &amp; Air Cargo</strong><br>
Frankfurt am Main, Germany · <a href="https://www.linkedin.com/in/jiahong-que-215428258/">LinkedIn</a> · <a href="mailto:jiahong.que@fra-uas.de">Email</a></p>

<!-- [房玄龄·2026-11-15] Update project descriptions and links to current engineering evidence. -->

I build data pipelines and AI services for aviation, air cargo, and other complex operations. I focus on data quality, traceable outputs, and recovery when a pipeline fails.

## SoloLakehouse

[SoloLakehouse](https://github.com/Jiahong-Que-9527/SoloLakehouse) is my personal data and AI engineering project. I version code, data contracts, and tests in Git. The current implementation runs locally, with projects planned for Google Cloud and Databricks.

### Fraport ADS-B Intelligence

I'm building a historical dataset of aircraft observations around Frankfurt Airport. The [OpenSky ingestion tool](https://github.com/Jiahong-Que-9527/SoloLakehouse/tree/main/Fraport-adsb-intelligence/01-opensky-acquisition) writes hourly ADS-B state vectors to Parquet, records checksums in manifests, and resumes from the last committed hour.

- **Pilot and recovery results.** All 168 hours of the pilot week matched the source during reconciliation. After an interruption, the recovered Parquet file matched the original SHA-256 checksum. A repeat run left the day's manifests unchanged. [Acquisition status and benchmarks](https://github.com/Jiahong-Que-9527/SoloLakehouse/blob/11995b0ca4063e9babdaa0eeabba065ecec49cf7/Fraport-adsb-intelligence/01-opensky-acquisition/README.md#status-2026-11-14)
- **Next milestone.** Add batch validation, acceptance records, and backup verification before the first monthly backfill. Curated aviation datasets, Databricks integration, and taxi-in prediction and serving on Google Cloud are planned. [Project plan](https://github.com/Jiahong-Que-9527/SoloLakehouse/blob/main/Fraport-adsb-intelligence/docs/project-plan.md)

The research data stays private. Public examples use synthetic or approved data.

### Self-hosted finance reference

The [versioned finance implementation](https://github.com/Jiahong-Que-9527/SoloLakehouse/tree/741e6da82cdc2cad207aa6ee707b8fb157b0174a/projects/finance) shows how I used Dagster, Apache Iceberg, and Trino to process ECB policy rates, exchange rates, and EWG ETF data, with dataset contracts and quality checks across Bronze, Silver, and Gold.

## RecordChat

[RecordChat](https://github.com/Jiahong-Que-9527/Recordchat) is a citation-first assistant for IATA ONE Record and NE:ONE. It uses Next.js, FastAPI, and Qdrant to answer questions about air-cargo data exchange and link readers to the relevant specifications and examples.

## Background

I am a Research Assistant at Frankfurt University of Applied Sciences. My work in the [Digital Testbed Air Cargo](https://www.digital-testbed-air-cargo.com/) context includes air-cargo movement classification and explainable ML for airport ground operations. My broader background spans more than ten years in aviation technology, software-enabled systems, and logistics. My doctoral research at Maastricht University focused on natural language processing.

**Credentials** · Google Cloud Professional Cloud Architect · Databricks Certified AI Engineer Associate

I am interested in data, AI, and ML platform engineering roles that combine hands-on delivery with complex operational problems.
