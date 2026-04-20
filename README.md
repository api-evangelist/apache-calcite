# Apache Calcite (apache-calcite)
Apache Calcite is a dynamic data management framework developed by the Apache Software Foundation that provides SQL parsing, query planning and optimization, and data federation capabilities. It serves as the SQL engine and query optimizer for many big data systems including Apache Hive, Druid, Flink, Kafka Streams, and others. Calcite provides a Java API for embedding SQL capabilities into applications, a JDBC adapter for connecting heterogeneous data sources, and an extensible relational algebra framework for building custom query optimizers.

**URL:** [https://calcite.apache.org/](https://calcite.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Apache, Data Federation, Framework, Open Source, Query Optimization, SQL

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Calcite Java API
The Apache Calcite Java API provides SQL parsing, validation, query planning, and optimization capabilities for embedding in JVM applications. It exposes a relational algebra framework and pluggable optimizer rules for building custom query engines.

**Human URL:** [https://calcite.apache.org/docs/](https://calcite.apache.org/docs/)

#### Tags

 - Java, Query Engine, SQL

#### Properties

- [Documentation](https://calcite.apache.org/docs/)
- [APIReference](https://calcite.apache.org/javadocAggregate/)
- [GettingStarted](https://calcite.apache.org/docs/tutorial.html)

### Apache Calcite JDBC API
The Apache Calcite JDBC adapter provides a standard JDBC interface over heterogeneous data sources. Applications use it to issue SQL queries across multiple data formats and storage systems through a unified SQL interface.

**Human URL:** [https://calcite.apache.org/docs/adapter.html](https://calcite.apache.org/docs/adapter.html)

#### Tags

 - JDBC, SQL

#### Properties

- [Documentation](https://calcite.apache.org/docs/adapter.html)

### Apache Calcite Avatica API
Apache Avatica is a framework for building database drivers derived from Apache Calcite. It provides a JSON/Protobuf-over-HTTP remote protocol for JDBC clients to connect to Calcite-based query engines.

**Human URL:** [https://calcite.apache.org/avatica/docs/](https://calcite.apache.org/avatica/docs/)

#### Tags

 - Avatica, HTTP, JDBC

#### Properties

- [Documentation](https://calcite.apache.org/avatica/docs/)
- [APIReference](https://calcite.apache.org/avatica/javadocAggregate/)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/calcite)
- [Documentation](https://calcite.apache.org/)
- [GettingStarted](https://calcite.apache.org/docs/tutorial.html)
- [Support](https://calcite.apache.org/community/)
- [TermsOfService](https://www.apache.org/licenses/)
- [ChangeLog](https://github.com/apache/calcite/releases)
- [Java SDK (Maven)](https://search.maven.org/artifact/org.apache.calcite/calcite-core)

## Features

| Name | Description |
|------|-------------|
| SQL Parsing and Validation | Parse and validate SQL queries using an extensible SQL grammar with support for SQL:2003 and beyond. |
| Query Optimization | Cost-based and rule-based query optimization using a volcano-style optimizer with pluggable optimization rules. |
| Relational Algebra | Extensible relational algebra framework for representing and transforming query plans as expression trees. |
| Data Federation | Federate queries across heterogeneous data sources including CSV, JSON, JDBC databases, and Elasticsearch. |
| Adapter Framework | Pluggable adapter API for connecting new data sources to the Calcite SQL engine. |
| Materialized Views | Automatic materialized view recognition and query rewriting for query acceleration. |
| Streaming SQL | SQL extensions for querying streaming data sources with window functions and temporal predicates. |
| Lattices and Tiles | Summary table recommendation and query rewriting using lattice structures for OLAP workloads. |
| JDBC Driver | Standard JDBC driver for issuing SQL queries against Calcite-connected data sources. |
| Avatica Remote Protocol | JSON/Protobuf-over-HTTP remote JDBC protocol for connecting clients to Calcite-based query servers. |

## Use Cases

| Name | Description |
|------|-------------|
| Embedding SQL in Applications | Add SQL querying capability to Java applications using the Calcite Java API without a full database. |
| Building Query Engines | Use Calcite as the SQL parsing and optimization layer in custom query engine implementations. |
| Data Virtualization | Federate queries across multiple heterogeneous data sources using Calcite adapters. |
| OLAP Query Optimization | Accelerate analytical queries using materialized view rewriting and lattice-based summary tables. |
| SQL Dialect Translation | Parse SQL in one dialect and transpile it to another using Calcite's SQL generation framework. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Flink | Flink uses Calcite for SQL parsing and query optimization in Flink SQL and Table API. |
| Apache Hive | Hive uses Calcite for cost-based query optimization in HiveQL query planning. |
| Apache Druid | Druid uses Calcite for SQL query parsing and planning against its time-series data store. |
| Apache Kafka | ksqlDB and Kafka Streams use Calcite for SQL stream processing query planning. |
| Apache Beam | Beam SQL uses Calcite for query planning on PCollection-based streaming and batch pipelines. |
| Elasticsearch | Calcite provides a SQL adapter for querying Elasticsearch indices using standard SQL. |
| Apache Kylin | Kylin uses Calcite as its SQL engine for OLAP cube query planning and execution. |

## Vocabulary

- [Apache Calcite Vocabulary](vocabulary/apache-calcite-vocabulary.yaml) — Domain taxonomy mapping 8 resources, 7 actions, and 2 personas for SQL query engine development

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
