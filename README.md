# Apache Hudi (apache-hudi)
Apache Hudi is a data lake platform that provides incremental data processing primitives including upserts and incremental queries. It manages storage of large analytical datasets on distributed file systems with ACID transactions, timeline-based versioning, and integrations for Spark, Flink, and Hive.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-hudi/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - ACID, Apache, Big Data, Data Lake, Incremental Processing, Lakehouse, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Hudi Timeline Server API
REST API for the Apache Hudi Timeline Server providing table timeline management, commit metadata inspection, and table administration for Hudi data lake tables.

**Human URL:** [https://hudi.apache.org/docs/timeline](https://hudi.apache.org/docs/timeline)

#### Tags:

 - Commits, Data Lake, REST, Tables, Timeline

#### Properties

- [Documentation](https://hudi.apache.org/docs/timeline)
- [OpenAPI](openapi/apache-hudi-timeline-openapi.yml)
- [JSONSchema](json-schema/hudi-huditableconfig-schema.json)
- [JSON-LD](json-ld/apache-hudi-timeline-context.jsonld)

### Apache Hudi Java API
Java API for writing Hudi tables with upserts, inserts, and deletes, plus timeline management, compaction, and Spark/Flink DataSource integration APIs.

**Human URL:** [https://hudi.apache.org/docs/writing_data](https://hudi.apache.org/docs/writing_data)

#### Tags:

 - Flink, Java, SDK, Spark

#### Properties

- [Documentation](https://hudi.apache.org/docs/writing_data)
- [Java SDK (Maven Central)](https://search.maven.org/artifact/org.apache.hudi/hudi-spark3.5-bundle_2.12)

## Common Properties

- [Documentation](https://hudi.apache.org/docs/overview)
- [GettingStarted](https://hudi.apache.org/docs/quick-start-guide)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/hudi)

## Features

| Name | Description |
|------|-------------|
| ACID Upserts | Atomically insert or update records in data lake tables with ACID guarantees using record keys. |
| Hudi Timeline | Immutable commit timeline tracking all mutations for time travel, rollback, and incremental queries. |
| Incremental Queries | Query only the data changed since a given commit timestamp for efficient streaming ingestion. |
| Copy-On-Write Tables | COW table type rewrites entire Parquet files on upsert for read-optimized query performance. |
| Merge-On-Read Tables | MOR table type appends delta logs for fast writes with compaction-based read optimization. |
| Table Services | Built-in cleaning, compaction, clustering, and indexing services for table maintenance. |
| Multi-Engine Support | Read and write Hudi tables from Apache Spark, Flink, Hive, Presto, Trino, and Athena. |
| Schema Evolution | Support for adding, renaming, and dropping columns with backward-compatible schema evolution. |

## Use Cases

| Name | Description |
|------|-------------|
| CDC Pipeline Ingestion | Ingest change data capture (CDC) events from databases into data lake tables with upsert support. |
| Streaming Data Lake | Build near-real-time data lake pipelines with Spark Structured Streaming or Flink. |
| Data Lake Maintenance | Manage storage costs with automated cleaning, compaction, and clustering of Hudi tables. |
| Incremental ETL | Build incremental ETL pipelines that process only changed data since the last run. |
| Regulatory Data Retention | Implement GDPR right-to-erasure by deleting records from Hudi tables with delete operations. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Spark | Primary write and read engine with Hudi DataSource and Spark SQL extensions. |
| Apache Flink | Flink sink and source connectors for streaming writes and incremental reads. |
| Apache Hive | Hive Metastore sync for making Hudi tables queryable from HiveQL. |
| Presto / Trino | Native Hudi input format support for querying Hudi tables from Presto and Trino. |
| AWS Athena | Athena supports reading Hudi COW and MOR tables stored in Amazon S3. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Hudi Timeline Server API](openapi/apache-hudi-timeline-openapi.yml)

### JSON Schema

- 6 schema files in [json-schema/](json-schema/)

### JSON Structure

- 6 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache Hudi Timeline Context](json-ld/apache-hudi-timeline-context.jsonld)

### Examples

- 6 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Hudi Timeline Server API](capabilities/shared/hudi-timeline.yaml) — 5 operations for table and timeline management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Hudi Lakehouse Management](capabilities/hudi-lakehouse-management.yaml) | hudi-timeline | 5 | Data Engineer |

## Vocabulary

- [Apache Hudi Vocabulary](vocabulary/apache-hudi-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 5 actions, 1 workflow, and 1 persona across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Hudi Spectral Rules](rules/apache-hudi-spectral-rules.yml) — 8 rules across 4 categories enforcing Apache Hudi API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
