# Architecture

Architecture notes, design reviews, platform comparisons, scalability studies, and cloud-native data platform patterns.

This section focuses on practical architecture decisions encountered in large-scale Data Engineering, AI Engineering, Streaming, IoT, Lakehouse, and Utility industry environments.

---

## Topics

### Lakehouse Architectures

| Article | Description |
|----------|-------------|
| [Iceberg vs Delta Lake](./iceberg-vs-delta-lake/) | Comparison of Apache Iceberg and Delta Lake architectures, metadata handling, scalability characteristics, and cloud deployment considerations. |

---

## Core Architecture Domains

### Data Platforms

Topics include:

- Data Lake Architecture
- Lakehouse Architecture
- Medallion Architecture
- Data Mesh
- Data Fabric
- Metadata-Driven Frameworks
- Data Governance
- Catalog Services

---

### Streaming Platforms

Topics include:

- Kafka
- Confluent Platform
- Spark Structured Streaming
- Apache Flink
- CDC Architectures
- Event-Driven Design
- Real-Time Analytics

---

### AI Platforms

Topics include:

- RAG Architectures
- Vector Databases
- Agentic AI
- MCP Architectures
- LLM Infrastructure
- AI Governance
- Model Serving

---

### Industrial IoT Platforms

Topics include:

- SCADA
- OSI PI
- Aspen IP21
- Industrial Historian Platforms
- Sensor Data Architectures
- Time-Series Analytics
- Edge Computing

---

### Cloud Platforms

Topics include:

#### Azure

- Azure Databricks
- Azure Data Factory
- Synapse Analytics
- ADLS Gen2
- Microsoft Fabric

#### AWS

- S3
- Glue
- EMR
- Kinesis
- Bedrock
- Lambda

#### GCP

- BigQuery
- Dataflow
- Pub/Sub
- Dataproc
- Vertex AI

---

## Architecture Principles

The following principles guide the architecture articles in this repository:

### Simplicity

Prefer systems that are easy to understand, operate, test, and maintain.

### Observability

Failures should explain themselves through logging, metrics, tracing, diagnostics, and metadata.

### Extensibility

New functionality should be added through extension points rather than continual modification of core frameworks.

### Scalability

Architectures should support growth in:

- Data volume
- Number of users
- Number of pipelines
- Number of teams
- Number of environments

### Cost Efficiency

Cloud-native architectures should minimize:

- Storage costs
- Compute costs
- Network costs
- Operational overhead

---

## Diagrams

Many architecture articles include:

- High-level architecture diagrams
- Data flow diagrams
- Metadata flow diagrams
- Sequence diagrams
- Deployment diagrams
- Infrastructure diagrams

---

## Intended Audience

This section is designed for:

- Data Engineers
- AI Engineers
- Data Architects
- Cloud Architects
- Platform Engineers
- Technical Leads
- Engineering Managers

---

## Related Sections

- [Data Engineering](../data-engineering/)
- [Streaming](../streaming/)
- [AI](../ai/)
- [Industrial IoT](../industrial-iot/)
- [Databricks](../databricks/)
- [Energy](../energy/)
