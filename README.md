# Apache Hudi (apache-hudi)

Apache Hudi is a data lake platform that provides incremental data processing primitives including upserts and incremental queries. It manages storage of large analytical datasets on distributed file systems with ACID transactions, timeline-based versioning, and integrations for Spark, Flink, and Hive.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-hudi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-hudi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- ACID
- Apache
- Big Data
- Data Lake
- Incremental Processing
- Lakehouse
- Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache Hudi Timeline Server API

REST API for the Apache Hudi Timeline Server providing table timeline management, commit metadata inspection, and table administration for Hudi data lake tables.

- **Human URL:** [https://hudi.apache.org/docs/timeline](https://hudi.apache.org/docs/timeline)
- **Base URL:** `http://localhost:9090`

#### Tags

- Commits
- Data Lake
- REST
- Tables
- Timeline

#### Properties

- [Documentation](https://hudi.apache.org/docs/timeline)
- [OpenAPI](openapi/apache-hudi-timeline-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-hudi-timeline.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-hudi-timeline.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hudi-huditableconfig-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/apache-hudi-timeline-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Apache Hudi Java API

Java API for writing Hudi tables with upserts, inserts, and deletes, plus timeline management, compaction, and Spark/Flink DataSource integration APIs.

- **Human URL:** [https://hudi.apache.org/docs/writing_data](https://hudi.apache.org/docs/writing_data)

#### Tags

- Java
- SDK
- Spark
- Flink

#### Properties

- [Documentation](https://hudi.apache.org/docs/writing_data)
- [SDK](https://search.maven.org/artifact/org.apache.hudi/hudi-spark3.5-bundle_2.12)
- [Postman Collection](collections/apache-hudi-timeline.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-hudi-timeline.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/apache-hudi)
- [Documentation](https://hudi.apache.org/docs/overview)
- [Getting Started](https://hudi.apache.org/docs/quick-start-guide)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/hudi)
- [Spectral Rules](rules/apache-hudi-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-hudi-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://hudi.apache.org/ecosystem/)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
