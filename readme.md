<div align="center">


  <h1 style="margin-bottom: 0.2em;">Hi, I'm <span style="color: #3962c1;">Jiahong Que</span></h1>
  <h3 style="font-weight:500; color:#4f5a6a;">Applied AI · Aviation & Logistics · Data Platform Engineering</h3>

  <p style="font-size: 1.1em; color: #363c48; margin-top:0.5em;">
    📍 Based in <b>Frankfurt am Main, Germany</b><br>
    I turn operational and sensor data into <b>explainable, governance-ready AI solutions</b><br>
    for aviation and logistics — from research prototypes to platform-oriented delivery.
  </p>

  <div style="margin-top:18px; margin-bottom: 0;">
    <img src="https://img.shields.io/badge/Aviation%20%26%20Logistics-Applied%20Domain-1F6FEB?style=for-the-badge" alt="Aviation and Logistics" />
    <img src="https://img.shields.io/badge/Applied%20ML-Explainability-87CEFA?style=for-the-badge&logo=python&logoColor=white" alt="Applied ML and Explainability" />
    <img src="https://img.shields.io/badge/Data%20Platform-Engineering-87CEFA?style=for-the-badge&logo=databricks&logoColor=white" alt="Data Platform Engineering" />
    <img src="https://img.shields.io/badge/GenAI-RAG-1F6FEB?style=for-the-badge&logo=openai&logoColor=white" alt="GenAI and RAG" />
  </div>
</div>

---

## What I am building toward

I am a **PhD Candidate** in AI and Logistics and **Research Assistant / Doctoral Researcher** at Frankfurt University of Applied Sciences (Jan 2024 – Present). Within the [Digital Testbed Air Cargo (DTAC)](https://www.digital-testbed-air-cargo.com/) project, I develop applied AI and ML workflows for real aviation and logistics use cases — including SmartPouch-based cargo movement classification, ADS-B data processing, and explainable ML for airport ground operations.

My engineering direction is to grow into a strong **AI Engineer / Data Platform Engineer**, combining aviation domain experience with governed, production-oriented data and ML platforms.

> I care about data and AI systems that are not only accurate, but also explainable, operable, and useful for domain experts under real operational constraints.

---

## Featured Projects

### [SoloLakehouse](https://github.com/Jiahong-Que-9527/SoloLakehouse)

<div align="left">
  <img src="https://img.shields.io/badge/SoloLakehouse-Governance%20First%20Open%20Lakehouse-87CEFA?style=for-the-badge&logo=databricks&logoColor=white" alt="SoloLakehouse" />
  <img src="https://img.shields.io/badge/Self--Hosted-Cloud%20Neutral-1F6FEB?style=for-the-badge" alt="Self Hosted Cloud Neutral" />
  <img src="https://img.shields.io/badge/Lineage%20Driven-Audit%20Friendly-1F6FEB?style=for-the-badge" alt="Lineage Driven Audit Friendly" />
</div>

**SoloLakehouse (SLH)** is a self-hosted, cloud-neutral, governance-first lakehouse prototype. It connects aviation data standards, ML workflows, and metadata/lineage management — demonstrating how one engineer can design and operate an auditable data platform without depending on managed SaaS lakehouse vendors.

| Area | Design |
|:---|:---|
| **Core stack** | Apache Iceberg · Delta Lake · Trino · Dagster · MLflow · MinIO / SeaweedFS · Superset · OpenMetadata |
| **Data path** | Bronze → Silver → Gold → ML, with explicit governance and lineage boundaries |
| **Governance posture** | Architecture decisions documented for lineage, access control, and audit-friendly operations |
| **Differentiation** | Most open lakehouses optimize for scale. SLH optimizes for **governed, explainable workflows** where architecture decisions need to survive review |

<div align="center">
  <a href="https://github.com/Jiahong-Que-9527/SoloLakehouse"><strong>Repository</strong></a>
  ·
  <a href="https://github.com/Jiahong-Que-9527/SoloLakehouse"><strong>Architecture</strong></a>
  ·
  <a href="https://github.com/Jiahong-Que-9527/SoloLakehouse"><strong>ADRs</strong></a>
</div>

### [RecordChat](https://github.com/Jiahong-Que-9527/RecordChat)

<div align="left">
  <img src="https://img.shields.io/badge/RecordChat-ONE%20Record%20AI%20Assistant-87CEFA?style=for-the-badge&logo=openai&logoColor=white" alt="RecordChat" />
  <img src="https://img.shields.io/badge/IATA%20ONE%20Record-Aviation%20Standards-1F6FEB?style=for-the-badge" alt="IATA ONE Record Aviation Standards" />
  <img src="https://img.shields.io/badge/Citation--First-Source%20Grounded-1F6FEB?style=for-the-badge" alt="Citation First Source Grounded" />
  <img src="https://img.shields.io/badge/Open%20Source-Community%20Helper-87CEFA?style=for-the-badge&logo=github&logoColor=white" alt="Open Source Community Helper" />
</div>

**RecordChat** is an open-source, domain-specific AI assistant that makes **IATA ONE Record** easier to learn and explore. ONE Record spans specifications, ontology, REST API, JSON-LD payloads, and server implementations like **NE:ONE** — RecordChat shortens that learning path with **grounded, source-cited answers** instead of generic chatbot behavior.

| Area | Design |
|:---|:---|
| **Core stack** | FastAPI · Next.js · Qdrant · pluggable LLM / embedding providers · Docker Compose |
| **Knowledge scope** | ONE Record specs · ontology (classes, properties, relationships) · JSON-LD · NE:ONE server guidance |
| **Domain tools** | Ontology-aware retrieval & reranking · JSON-LD example generation · Mermaid diagrams for flows and relationships |
| **Differentiation** | Most AI chatbots optimize for fluency. RecordChat optimizes for **traceability**, helping developers and logistics teams understand ONE Record with auditable, source-linked answers |

**Try asking:** *What is a LogisticsObject?* · *How do Shipment, Piece, and Waybill relate?* · *Generate a JSON-LD example for a Piece* · *How do I run NE:ONE locally?*

<div align="center">
  <a href="https://github.com/Jiahong-Que-9527/RecordChat"><strong>Repository</strong></a>
  ·
  <a href="https://github.com/Jiahong-Que-9527/RecordChat/blob/main/SPEC.md"><strong>SPEC</strong></a>
  ·
  <a href="https://github.com/Jiahong-Que-9527/RecordChat/blob/main/docs/data_compliance_report.md"><strong>Data Compliance</strong></a>
</div>


---

## Stack I Ship With

<div align="left">
  <img src="https://img.shields.io/badge/Apache%20Iceberg-87CEFA?style=for-the-badge&logo=apacheiceberg&logoColor=white" alt="Apache Iceberg" />
  <img src="https://img.shields.io/badge/Delta%20Lake-87CEFA?style=for-the-badge&logo=databricks&logoColor=white" alt="Delta Lake" />
  <img src="https://img.shields.io/badge/Trino-87CEFA?style=for-the-badge&logo=trino&logoColor=white" alt="Trino" />
  <img src="https://img.shields.io/badge/Dagster-87CEFA?style=for-the-badge&logo=dagster&logoColor=white" alt="Dagster" />
  <img src="https://img.shields.io/badge/MLflow-87CEFA?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow" />
  <img src="https://img.shields.io/badge/FastAPI-87CEFA?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/MinIO-87CEFA?style=for-the-badge&logo=minio&logoColor=white" alt="MinIO" />
  <img src="https://img.shields.io/badge/PySpark-87CEFA?style=for-the-badge&logo=apachespark&logoColor=white" alt="PySpark" />
  <img src="https://img.shields.io/badge/PostgreSQL-87CEFA?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Superset-87CEFA?style=for-the-badge&logo=apachesuperset&logoColor=white" alt="Superset" />
  <img src="https://img.shields.io/badge/OpenMetadata-87CEFA?style=for-the-badge&logo=openmetadata&logoColor=white" alt="OpenMetadata" />
  <img src="https://img.shields.io/badge/Prometheus-87CEFA?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-87CEFA?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
  <img src="https://img.shields.io/badge/Docker-87CEFA?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-87CEFA?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Terraform-87CEFA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-87CEFA?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</div>

**Platform layers:** sensor & operational data · open table formats · SQL & metadata · orchestration · ML lifecycle & explainability · GenAI/RAG APIs · observability · IaC

---

## Selected Talks

- **HICL 2026** — *Taxi-In Time Prediction for Airport Ground Operations Using Explainable Machine Learning*
- **LM25 2025**, Milan — *Comparing and Predicting Taxi-In Times for Passenger and Cargo Flights at Frankfurt Airport*
- **ATRS World Conference 2025**, Hong Kong — *An Enhanced System for Air Cargo Movement Detection Using Deep Learning and Explainable AI*

---

## GitHub Activity

<div align="center">
  <img src="https://gh-stats.work/api?username=Jiahong-Que-9527&show_icons=true&hide_border=true&theme=default" alt="Jiahong Que GitHub stats" height="165" />
  <img src="https://gh-stats.work/api/top-langs/?username=Jiahong-Que-9527&layout=compact&hide_border=true&theme=default" alt="Jiahong Que top languages" height="165" />
</div>

---

## Connect

<p>
  <a href="mailto:jiahong.que@fra-uas.de">
    <img src="https://img.shields.io/badge/Email-Jiahong%20Que-1F6FEB?style=for-the-badge&logo=google&logoColor=white" alt="Email jiahong.que@fra-uas.de" />
  </a>
  <a href="https://www.linkedin.com/in/jiahong-que-215428258/">
    <img src="https://img.shields.io/badge/LinkedIn-Jiahong%20Que-1F6FEB?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/Jiahong-Que-9527">
    <img src="https://img.shields.io/badge/GitHub-Jiahong--Que--9527-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

Open to **collaboration on aviation & logistics digitalization**, **research conversations**, and **AI / Data Platform Engineer** roles at the intersection of applied ML, governed data workflows, and production-oriented platform engineering.
