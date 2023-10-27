# Awesome Infrastructure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/criccomini/awesome-infra/)

A collection of awesome software infrastructure projects and companies.

* [Awesome Infrastructure](#awesome-javascript)
  * [AI/ML](#ai-ml)
  * [Change Data Capture](#change-data-capture)
  * Databases
    * [Graph Databases](#graph)
    * [Key-Value Stores](#key-value)
    * [OLTP Databases](#oltp)
    * [OLAP Databases](#olap)
    * [Search Engines](#search)
    * [Vector Stores](#vector)
    * [Data Lakes](#data-lakes)
  * [Durable Execution](#durable-execution)
  * [File Formats](#file-formats)
  * [Functions as a Service](#functions-as-a-service)
  * Orchestration
    * [Workflow](#workflow)
  * [Query Engines](#query-engines)
  * [Service Mesh](#service-mesh)
  * Streaming
    * [Message Brokers](#message-brokers)
    * [Stream Processing](#stream-processing)
* [Miscellaneous](#miscellaneous)
* [Contributing](#contributing)
* [License](#license)

----

## AI/ML
*Machine learning and artificial intelligence infrastructure.*

## Change Data Capture
*Change data capture.*

* [Arcion](https://arcion.io/) - Arcion is a change data capture platform that enables you to stream data from your database to your data warehouse in real-time.
* [Debezium](https://debezium.io/) - Debezium is an open source distributed platform for change data capture.

## Graph Databases
*Graph databases.*

* [Dgraph](https://dgraph.io/) - Dgraph is an open source, low latency, high throughput, native and distributed graph database.
* [Neo4j](https://neo4j.com/) - Neo4j is a native graph database, built from the ground up to leverage not only data but also data relationships.
* [TigerGraph](https://www.tigergraph.com/) - TigerGraph is a native parallel graph database platform for enterprise applications.
* [Neptune](https://aws.amazon.com/neptune/) - Amazon Neptune is a fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets.

## Key-Value Stores
*Key-value stores.*

* [Venice](https://venicedb.org/) - Venice is a derived data platform providing high throughput ingestion from batch, streams, and lambda/kappa architectures, and low latency online reads, for ML feature storage, etc.

## OLTP Databases
*Online transaction processing databases.*

* [Neon](https://neon.tech) - Serverless Postgres. Neon separates storage and compute to offer autoscaling, branching, and bottomless storage.
* [TigerBeetle](https://github.com/tigerbeetle/tigerbeetle) - TigerBeetle is a financial accounting database designed for mission critical safety and performance to power the future of financial services.

## OLAP Databases
*Online analytical processing databases.*

* [Materialize](https://materialize.com/) - Materialize is a data warehouse purpose-built for operational workloads where an analytical data warehouse would be too slow, and a stream processor would be too complicated.
* [Pinot](https://pinot.apache.org/) - Apache Pinot is a distributed OLAP datastore, designed to answer OLAP queries with low latency.

## Search Engines
*Search engines.*

## Vector Stores
*Vector stores.*

* [LanceDB](https://github.com/lancedb/lancedb) - LanceDB is an open-source database that uses the Lance fileformat for vector-search.
* [Turbopuffer](https://turbopuffer.com/) - A serverless database for low latency vector search.

## Data Lakes
*Data lakes.*

* [Bauplan](https://www.bauplanlabs.com/) - A serverless lakehouse for complex data workloads.

## Durable Execution
*Durable execution systems.*

## File Formats
*File formats.*

* [GraphAR](https://github.com/alibaba/GraphAr) - An open source, standard data file format for graph data storage and retrieval.
* [Lance](https://github.com/lancedb/lance) - Modern columnar data format for ML and LLMs implemented.
* [ORC](https://orc.apache.org/) - Apache ORC is a self-describing, type-aware columnar file format designed for Hadoop workloads.
* [Parquet](https://parquet.apache.org/) - Apache Parquet is an open source, column-oriented data file format designed for efficient data storage and retrieval.

## Functions as a Service
*Functions as a service.*

* [Lambda](https://aws.amazon.com/lambda/) - AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume.
* [Google Cloud Functions](https://cloud.google.com/functions) - Google Cloud Functions is a serverless execution environment for building and connecting cloud services. With Cloud Functions you write simple, single-purpose functions that are attached to events emitted from your cloud infrastructure and services.
* [Azure Functions](https://azure.microsoft.com/en-us/services/functions/) - Azure Functions is a serverless compute service that lets you run event-triggered code without having to explicitly provision or manage infrastructure.
* [OpenFaaS](https://www.openfaas.com/) - OpenFaaS makes it easy for developers to deploy event-driven functions and microservices to Kubernetes without repetitive, boiler-plate coding.
* [Knative](https://knative.dev/) - Kubernetes-based platform to build, deploy, and manage modern serverless workloads.
* [Fission](https://fission.io/) - Fission is a framework for serverless functions on Kubernetes. It allows you to easily create HTTP services on Kubernetes from functions.
* [OpenLambda](https://github.com/open-lambda/open-lambda) - OpenLambda is an Apache-licensed serverless computing project, written (mostly) in Go and based on Linux containers.

## Workflow
*Workflow.*

* [Airflow](https://airflow.apache.org/) - Airflow is a platform to programmatically author, schedule and monitor workflows.
* [Prefect](https://prefect.io) - Prefect is a workflow management system, designed for modern infrastructure and powered by the open-source Prefect Core workflow engine.
* [Dagster](https://dagster.io/) - Dagster is a data orchestrator for machine learning, analytics, and ETL.

## Query Engines

* [Calcite](https://calcite.apache.org/) - Apache Calcite is a dynamic data management framework. It contains many of the pieces that comprise a typical database management system but omits the storage primitives.
* [Data Fusion](https://arrow.apache.org/datafusion/) - DataFusion is a very fast, extensible query engine for building high-quality data-centric systems.
* [Substrait](https://github.com/substrait-io/substrait) - A cross platform way to express data transformation, relational algebra, standardized record expression and plans.
* [Velox](https://velox-lib.io/) - A C++ vectorized database acceleration library aimed to optimizing query engines and data processing systems.

## Service Mesh
*Service mesh.*

* [Istio](https://istio.io/) - IstIstio is an open platform for providing a uniform way to integrate microservices, manage traffic flow across microservices, enforce policies, and aggregate telemetry data.
* [Linkerd](https://linkerd.io/) - Linkerd is an ultralight, security-first service mesh for Kubernetes. Linkerd adds critical security, observability, and reliability features to your Kubernetes stack with no code change required.

## Message Brokers
*Message brokers.*

* [WarpStream](https://warpstream.com) - WarpStream is a Kafka compatible data streaming platform built directly on top of S3.

## Stream Processing
*Stream processing.*

* [Apache Flink](https://flink.apache.org/) - Stateful computations over bounded and unbounded data Streams.
* [Decodable](https://www.decodable.co/) - A managed platform for stream processing and real-time ETL, powered by Apache Flink and Debezium.
* [Kafka Streams](https://kafka.apache.org/documentation/streams/) - A stateful stream processing library for Kafka.
* [Responsive](https://responsive.dev) - Responsive is the platform for developers building stateful reactive applications on the modern cloud. Focused on Kafka streams.

# Miscellaneous

* [Bacalhau](https://github.com/bacalhau-project/bacalhau) - Compute over Data framework for public, transparent, and optionally verifiable computation.

# Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [criccomini](https://github.com/criccomini) has waived all copyright and related or neighboring rights to this work.
