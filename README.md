# Awesome-Managed-Graph-Database

## Top Managed Graph Database Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Managed Graph Databases, Self-Hosted Graph Engines & Open-Source Graph Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial managed graph databases** and **open-source projects** that store and query highly connected data — from fully managed cloud graph services to self-hosted property graphs, RDF triple stores, and distributed graph engines.



**Examples** include Amazon Neptune, Neo4j AuraDB, TigerGraph Cloud, Memgraph Cloud, ArangoDB Oasis, DataStax Astra DB Graph, Azure Cosmos DB Gremlin API, Katana Graph Cloud, Cambridge Semantics AnzoGraph, and Dgraph Cloud (the category leaders).



**Open-source emphasis**: Managed graph databases are anchored by **Neo4j** as the most widely adopted property graph database, with **JanusGraph**, **NebulaGraph**, and **Apache HugeGraph** providing distributed, horizontally scalable alternatives. **Kùzu** brings embedded graph analytics with vector search, **Memgraph** delivers in-memory real-time performance, and **Apache AGE** adds graph capabilities directly to PostgreSQL. **FalkorDB** and **CozoDB** round out the ecosystem with LLM-focused GraphRAG and multi-model capabilities. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon Neptune](https://aws.amazon.com/neptune/)**  

  **AWS's fully managed graph database service** — supports both property graph (Gremlin, openCypher) and RDF (SPARQL) models . **Purpose-built, high-performance storage engine** optimized for storing billions of relationships with millisecond latency . **ACID-compliant with index-free adjacency** for efficient traversals . **Neptune Serverless** for automatic on-demand scaling . **Neptune Analytics** for vector search and graph algorithms . **Best for AWS-native graph workloads** .



- **[Neo4j AuraDB](https://neo4j.com/cloud/aura/)**  

  **The managed Neo4j cloud service** — the strongest developer-experience alternative for property graph applications . **Managed property-graph service with Python driver and import tooling** . **AuraDB Serverless** for automatic scaling . **Best for developer-friendly managed graph databases** .



- **[TigerGraph Cloud](https://www.tigergraph.com/)**  

  **Enterprise graph analytics platform** — distributed MPP architecture with GSQL query language . **Best for large-scale graph analytics** .



- **[Memgraph Cloud](https://memgraph.com/cloud)**  

  **Managed in-memory graph database** — Cypher-compatible with real-time streaming analytics . **Best for real-time graph applications** .



- **[ArangoDB Oasis](https://www.arangodb.com/)**  

  **Managed multi-model database** — graphs, documents, and key-value in one engine . **Best for multi-model applications** .



- **[DataStax Astra DB Graph](https://www.datastax.com/)**  

  **Managed graph capabilities on Astra DB** — built on Cassandra with Gremlin support . **Best for Cassandra-native graph workloads** .



- **[Azure Cosmos DB Gremlin API](https://azure.microsoft.com/en-us/products/cosmos-db/)**  

  **Microsoft's globally distributed multi-model database** — Gremlin API for graph workloads . **Turnkey global distribution with multi-region writes** . **Best for globally distributed graph applications** .



- **[Katana Graph Cloud](https://katanagraph.com/)**  

  **High-performance graph analytics platform** — designed for large-scale graph processing . **Best for graph analytics at scale** .



- **[Cambridge Semantics AnzoGraph](https://www.cambridgesemantics.com/)**  

  **RDF graph database with parallel processing** — in-memory architecture for high performance . **Best for semantic graph analytics** .



- **[Dgraph Cloud](https://dgraph.io/)**  

  **Managed Dgraph** — GraphQL-native graph database with distributed architecture . **Best for GraphQL-driven graph applications** .



## Open-Source GitHub Projects



### Property Graph Databases



- **[Neo4j Community Edition](https://github.com/neo4j/neo4j)**  

  **The most widely adopted graph database**, GPL-3.0 licensed . **Native property graph storage with Cypher query language** . **ACID-compliant transactions** . **Graph Data Science library with 65+ algorithms** . **Vector search and GraphRAG capabilities** . **The reference implementation for property graphs** . **Best for relationship-heavy applications** .



- **[Memgraph](https://github.com/memgraph/memgraph)**  

  **In-memory graph database tuned for dynamic analytics**, BSL licensed (free for most uses) . **Cypher-compatible with Neo4j ecosystem** . **Real-time streaming data processing** . **Built for low-latency, high-throughput workloads** . **Best for real-time graph applications** .



- **[JanusGraph](https://github.com/JanusGraph/janusgraph)**  

  **Highly scalable distributed graph database**, Apache-2.0 licensed with **5,800+ GitHub stars** . **Optimized for storing and querying graphs with billions of vertices and edges** across multi-machine clusters . **Apache TinkerPop 3 compliant with Gremlin** . **Storage backends: Cassandra, HBase, BerkeleyDB, FoundationDB** . **Index backends: Elasticsearch, Solr, Lucene** . **Used in production by Netflix, Uber, eBay, and Red Hat** . **Best for massive distributed graphs** .



- **[NebulaGraph](https://github.com/vesoft-inc/nebula)**  

  **Distributed, fast open-source graph database**, Apache-2.0 licensed with **12,000+ GitHub stars** . **Handles large volumes of data with millisecond latency** . **Symmetrically distributed with storage and computing separation** . **Strong data consistency via RAFT protocol** . **openCypher-compatible query language** . **Used for social media, recommendation systems, knowledge graphs, and security** . **Best for super large-scale graph workloads** .



- **[Apache HugeGraph](https://github.com/apache/incubator-hugegraph)**  

  **Fast-speed and highly-scalable graph database**, Apache-2.0 licensed . **Billions of vertices and edges with excellent OLTP ability** . **Apache TinkerPop 3 compliant with Gremlin and Cypher** . **Backend storage: RocksDB, Cassandra, HBase, ScyllaDB, MySQL, PostgreSQL** . **Integration with Flink/Spark/HDFS** . **Best for enterprise-scale graph workloads** .



- **[Kùzu](https://github.com/kuzudb/kuzu)**  

  **Embedded property graph database built for query speed and scalability**, MIT licensed . **Runs in-process with no external servers** . **Columnar storage, vectorized processing, and novel join algorithms** . **Cypher query language support** . **Graph-native full-text search and HNSW vector index** . **Works with LangChain, PyTorch Geometric, LlamaIndex, Pandas, Parquet, Iceberg** . **Kuzu-Wasm brings graph database to every browser** . **Best for embedded graph analytics and knowledge graphs** .



- **[FalkorDB](https://github.com/FalkorDB/FalkorDB)**  

  **Super fast graph database using GraphBLAS**, open-source . **Sparse adjacency matrix graph representation** . **Goal: best Knowledge Graph for LLM (GraphRAG)** . **Cypher-compatible with Redis module architecture** . **Free cloud tier with 100MB RAM** . **Best for GraphRAG and LLM applications** .



- **[CozoDB](https://github.com/cozodb/cozo)**  

  **Transactional, relational-graph-vector database using Datalog**, open-source with **3,400+ GitHub stars** . **Multi-model: relational, graph, and vector** . **Datalog query language** . **Two-hop graph traversal in less than 1ms for 1.6M vertices and 31M edges** . **PageRank in ~50ms for 10K vertices and 120K edges** . **Best for AI and knowledge graph applications** .



### RDF & Semantic Graph Databases



- **[Apache Jena](https://github.com/apache/jena)**  

  **Java framework for RDF and SPARQL**, Apache-2.0 licensed . **TDB and Fuseki for RDF storage and SPARQL endpoints** . **Best for semantic web applications** .



- **[Eclipse RDF4J](https://github.com/eclipse/rdf4j)**  

  **Java framework for RDF and SPARQL**, EDL licensed . **Best for RDF-based applications** .



- **[Oxigraph](https://github.com/oxigraph/oxigraph)**  

  **SPARQL graph database in Rust**, Apache-2.0/MIT licensed . **Best for embedded RDF storage** .



- **[Blazegraph](https://github.com/blazegraph/database)**  

  **High-performance graph database for RDF and property graphs**, GPL-2.0 licensed . **Best for large-scale RDF workloads** .



### PostgreSQL Graph Extensions



- **[Apache AGE](https://github.com/apache/age)**  

  **Graph database extension for PostgreSQL**, Apache-2.0 licensed . **Adds native graph database functionality to PostgreSQL** . **openCypher queries side-by-side with SQL** . **Supports PostgreSQL 11-17** . **Best for PostgreSQL users wanting graph capabilities** .



- **[AgensGraph](https://github.com/bitnine-oss/agensgraph)**  

  **Transactional graph database based on PostgreSQL**, Apache-2.0 licensed . **Multi-model with graph and relational** . **Best for enterprise PostgreSQL graph** .



### Additional Strong Open-Source Options



- **Apache TinkerPop** — Graph computing framework and Gremlin .

- **Gaffer** — Large-scale entity and relation database from GCHQ .

- **TerminusDB** — Distributed database with collaboration model .

- **TypeDB** — Knowledge graph database with type system .

- **RedisGraph** — Graph database as Redis module (deprecated) .

- **Raphtory** — Scalable graph analytics database in Rust .

- **IndraDB** — Graph database in Rust .

- **HelixDB** — Graph-vector database in Rust .

- **PuppyGraph** — Graph query engine for data lakes .

- **DuckPGQ** — Graph queries in DuckDB .



**Frameworks for building custom managed graph database solutions**: Combine **Neo4j** for the most mature property graph database with Cypher and Graph Data Science . Use **JanusGraph** or **NebulaGraph** for distributed, horizontally scalable graphs across billions of vertices . Deploy **Kùzu** for embedded graph analytics with vector search and AI ecosystem integration . Choose **Memgraph** or **FalkorDB** for real-time and GraphRAG applications . Integrate **Apache AGE** for adding graph capabilities to existing PostgreSQL . Use **Apache HugeGraph** for enterprise-scale graph workloads with flexible storage backends . Note that true managed graph databases with global infrastructure, automatic scaling, and vendor-supported SLAs (Amazon Neptune, Neo4j AuraDB, TigerGraph Cloud) remain primarily commercial territory; open-source stacks provide strong property graph, distributed, and embedded graph foundations that require integration for complete graph database deployments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Graph databases handle highly connected data and may process sensitive relationship information. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **License considerations**: Neo4j Community uses GPL-3.0, Memgraph uses BSL (free for most uses), JanusGraph uses Apache-2.0, Kùzu uses MIT, and NebulaGraph uses Apache-2.0. Verify licensing against your use case before committing .

- **Graph model choice matters** — property graphs (Cypher/Gremlin) vs. RDF (SPARQL) are fundamentally different. Property graphs excel at rich-edge attributes and traversal performance; RDF excels at semantic interoperability and ontology reasoning .

- **Distributed graphs add operational complexity** — JanusGraph and NebulaGraph scale to billions of edges but require expertise in storage backends, indexing, and cluster management. A single beefy node handles more than most teams expect .

- The open-source ecosystem provides strong property graph, distributed, and embedded graph foundations, but **managed infrastructure, global scale, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for data engineers, knowledge graph architects, and organizations seeking graph database sovereignty.**  

Let's make managed graph databases more open, transparent, and connected.
