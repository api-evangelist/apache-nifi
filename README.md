# Apache NiFi (apache-nifi)
Apache NiFi is a dataflow management system designed to automate the flow of data between systems. It provides a web-based user interface for designing, controlling, and monitoring data flows with real-time operational control, data provenance tracking, and support for hundreds of processors. NiFi Version 2 is the current major version with enhanced security and performance.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-nifi/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Data Integration, Data Pipeline, Dataflow, ETL, IoT, Streaming

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache NiFi REST API
The NiFi REST API provides comprehensive JWT-authenticated endpoints for managing processors, connections, controller services, process groups, reporting tasks, provenance, flow versions, system diagnostics, access control, parameter contexts, and data transfer. Base URL is http://nifi-host:8080/nifi-api. OpenAPI spec available at /nifi-docs/swagger.yaml.

**Human URL:** [https://nifi.apache.org/components/](https://nifi.apache.org/components/)

#### Tags:

 - Dataflow, Flow Management, JWT, REST

#### Properties

- [Documentation](https://nifi.apache.org/components/)
- [OpenAPI](https://nifi.apache.org/nifi-docs/swagger.yaml)
- [GettingStarted](https://nifi.apache.org/documentation/guides/)
- [GitHubRepository](https://github.com/apache/nifi)

### Apache NiFi Registry
NiFi Registry provides a central location for storage and management of shared NiFi flow resources, enabling versioned flows across NiFi environments. It provides its own REST API for managing buckets, flows, versions, and users.

**Human URL:** [https://nifi.apache.org/documentation/](https://nifi.apache.org/documentation/)

#### Tags:

 - Flow Versioning, Registry, REST

#### Properties

- [Documentation](https://nifi.apache.org/documentation/)
- [GitHubRepository](https://github.com/apache/nifi)

### Apache MiNiFi
MiNiFi is a lightweight agent for edge data collection that is a subproject of NiFi. MiNiFi C++ (nifi-minifi-cpp) provides a small-footprint agent for IoT edge data collection with local processing and a remote NiFi parent instance for management.

**Human URL:** [https://nifi.apache.org/minifi/](https://nifi.apache.org/minifi/)

#### Tags:

 - Edge Computing, IoT, Lightweight Agent

#### Properties

- [Documentation](https://nifi.apache.org/minifi/)
- [GitHubRepository](https://github.com/apache/nifi-minifi-cpp)

## Common Properties

- [Portal](https://nifi.apache.org/)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/nifi)
- [GitHubRepository](https://github.com/apache/nifi-minifi-cpp)
- [GitHubRepository](https://github.com/apache/nifi-api)
- [GitHubRepository](https://github.com/apache/nifi-site)
- [Wiki](https://cwiki.apache.org/confluence/display/NIFI)
- [IssueTracker](https://issues.apache.org/jira/browse/NIFI)
- [Slack](https://join.slack.com/t/apachenifi/shared_invite/zt-11njbtkdx-ZRU8FKYSWoEHRJetidy0zA)
- [Blog](https://nifi.apache.org/blog/)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)

## Features

| Name | Description |
|------|-------------|
| Visual Dataflow Designer | Browser-based drag-and-drop interface for designing, controlling, and monitoring data flows without coding. |
| Data Provenance Tracking | Complete lineage tracking of every piece of data that flows through the system from ingestion to destination. |
| Hundreds of Built-in Processors | Extensive library of processors for data ingestion, transformation, routing, and delivery to diverse systems and cloud platforms. |
| Guaranteed Delivery | Loss-tolerant and guaranteed delivery options with configurable prioritization and backpressure control. |
| REST API | Comprehensive JWT-authenticated REST API for programmatic management of all NiFi resources and operations. |
| Flow Versioning | Version control for data flows via NiFi Registry, enabling flow promotion across development, test, and production environments. |
| Multi-Tenant Security | Fine-grained multi-tenant authorization with HTTPS, TLS, and SSH support for secure deployments. |
| Clustering | Zero-master cluster architecture for high-availability and load-balanced dataflow execution. |
| Parameter Contexts | Externalize configuration using parameter contexts that can be applied across multiple processors and process groups. |
| MiNiFi Edge Agents | Lightweight MiNiFi agents for edge data collection at IoT endpoints, managed centrally from NiFi. |

## Use Cases

| Name | Description |
|------|-------------|
| Data Ingestion Pipelines | Build pipelines ingesting data from files, databases, message queues, cloud storage, and APIs into data lakes and warehouses. |
| Cybersecurity Data Collection | Collect and route security telemetry, logs, and threat intelligence feeds for SIEM and analytics platforms. |
| IoT Edge Data Collection | Deploy MiNiFi agents at IoT edge locations to collect, filter, and forward sensor data to central NiFi clusters. |
| Real-Time Event Streaming | Build event streaming pipelines consuming from Kafka, Kinesis, and other message brokers for real-time data processing. |
| Generative AI Data Pipelines | Build data preparation and vector database ingestion pipelines for generative AI and RAG applications. |
| Cloud Data Integration | Move and transform data between AWS, Azure, and GCP services with built-in cloud processor libraries. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Native ConsumeKafka and PublishKafka processors for streaming data between NiFi and Kafka topics. |
| Amazon S3 | PutS3Object and FetchS3Object processors for reading and writing data to AWS S3 buckets. |
| Azure Blob Storage | PutAzureBlobStorage and FetchAzureBlobStorage processors for Azure cloud storage integration. |
| Google Cloud Storage | Native GCS processors for reading and writing Google Cloud Storage objects. |
| MongoDB | PutMongo and GetMongo processors for reading and writing documents to MongoDB collections. |
| Elasticsearch | PutElasticsearchRecord and FetchElasticsearch processors for indexing and querying Elasticsearch. |
| Salesforce | Native Salesforce processors for querying and publishing data to Salesforce CRM. |
| Apache MQTT | ConsumeMQTT and PublishMQTT processors for IoT messaging protocol support. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
