# Awesome-Serverless-Search-Log-Analytics

## Top Serverless Search & Log Analytics Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Log Aggregation, Search Analytics & Self-Hosted Observability Backends*  

**Last updated: October 2026**



This repository tracks notable **commercial search and log analytics platforms** and **open-source projects** that ingest, index, search, and visualize logs and events at scale. These tools power observability, security analytics, and operational intelligence — with serverless options that scale without infrastructure management.



**Examples** include Amazon OpenSearch Serverless, Elastic Cloud Serverless, Logz.io, Better Stack, Axiom, Mezmo, Baselime, Quickwit Cloud, Coralogix, and Hydrolix (the category leaders).



**Open-source emphasis**: Log analytics is one of the strongest open-source domains. **OpenSearch** leads as the Apache-licensed fork of Elasticsearch. **Quickwit** brings Rust-based sub-second search on object storage. **OpenObserve** delivers a single-binary observability platform with 140x lower storage costs. **Grafana Loki** provides cost-effective log aggregation. **Apache Doris**, **SigNoz**, and **Uptrace** round out the ecosystem. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon OpenSearch Serverless](https://aws.amazon.com/opensearch-service/)**  

  **AWS's serverless search and log analytics** — automatically scales for unpredictable workloads . **No cluster management** — pay for what you use . **Best for AWS-native log analytics** .



- **[Elastic Cloud Serverless](https://www.elastic.co/)**  

  **Elastic's serverless offering** — managed Elasticsearch, Kibana, and observability . **Best for Elastic ecosystem users** .



- **[Logz.io](https://logz.io/)**  

  **Cloud observability platform** — log management, metrics, and tracing on OpenSearch . **Best for unified observability** .



- **[Better Stack](https://betterstack.com/)**  

  **Log management and uptime monitoring** — SQL-compatible log querying with live tail . **Best for modern log analytics** .



- **[Axiom](https://axiom.co/)**  

  **Serverless log analytics** — unlimited ingest, fast queries, and cost-effective storage . **Best for high-volume log analytics** .



- **[Mezmo](https://www.mezmo.com/)**  

  **Telemetry data pipeline and log analytics** — control, enrich, and route observability data . **Best for telemetry pipelines** .



- **[Baselime](https://baselime.io/)**  

  **Serverless observability platform** — logs, metrics, and traces for serverless applications . **Best for serverless-first teams** .



- **[Quickwit Cloud](https://quickwit.io/)**  

  **Managed Quickwit** — sub-second search on object storage . **Best for cost-effective log search** .



- **[Coralogix](https://coralogix.com/)**  

  **Observability platform with streaming analytics** — logs, metrics, and traces with cost optimization . **Best for enterprise observability** .



- **[Hydrolix](https://hydrolix.io/)**  

  **High-density data platform** — cost-effective log retention at scale . **Best for long-term log retention** .



## Open-Source GitHub Projects



### Search & Log Analytics Engines



- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**  

  **The leading open-source search and analytics suite**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Apache-licensed fork of Elasticsearch 7.10** — community-driven . **Full-text search, log analytics, and security analytics** . **The de facto open-source Elasticsearch alternative** — used by AWS, SAP, and thousands of organizations . **Best for search and log analytics at scale** .



- **[Quickwit](https://github.com/quickwit-oss/quickwit)**  

  **Sub-second search on object storage**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Rust-based search engine for logs** — decoupled compute and storage . **10x cheaper than Elasticsearch** for log storage on S3 . **The best open-source alternative for cost-effective log search** . **Best for long-term log retention on object storage** .



- **[OpenObserve](https://github.com/openobserve/openobserve)**  

  **Open-source observability platform**, AGPL-3.0 licensed with **15,000+ GitHub stars** . **Single binary for logs, metrics, and traces** . **140x lower storage costs than Elasticsearch** using Parquet columnar format and S3-native architecture . **Native OTLP support, SQL and PromQL query languages** . **Best for cost-effective unified observability** .



- **[Grafana Loki](https://github.com/grafana/loki)**  

  **Horizontally scalable log aggregation**, AGPL-3.0 licensed with **24,000+ GitHub stars** . **Cost-effective log storage** — indexes labels, not full text . **Integrates with Grafana for visualization** . **The standard for Kubernetes log aggregation** . **Best for cloud-native log aggregation** .



- **[Apache Solr](https://github.com/apache/solr)**  

  **The veteran open-source search platform**, Apache-2.0 licensed . **Full-text search, faceting, and analytics** . **The original enterprise search engine** . **Best for enterprise search** .



- **[Meilisearch](https://github.com/meilisearch/meilisearch)**  

  **Lightning-fast search engine**, MIT licensed with **45,000+ GitHub stars** . **Typo-tolerant, faceted search with instant results** . **The leading open-source Algolia alternative** . **Best for application search** .



- **[Typesense](https://github.com/typesense/typesense)**  

  **Open-source typo-tolerant search engine**, GPL-3.0 licensed with **20,000+ GitHub stars** . **Fast, relevant, and easy to deploy** . **Best for site search and e-commerce** .



### Log Management & Observability



- **[SigNoz](https://github.com/SigNoz/signoz)**  

  **Open-source observability platform**, Apache-2.0 licensed with **23,000+ GitHub stars** . **Logs, traces, and metrics in one application** — OpenTelemetry-native . **Best for unified observability** .



- **[Uptrace](https://github.com/uptrace/uptrace)**  

  **Open-source APM and observability**, AGPL-3.0 licensed . **Distributed tracing, metrics, and logs** . **Best for cost-effective APM** .



- **[Apache Doris](https://github.com/apache/doris)**  

  **Real-time analytical database**, Apache-2.0 licensed with **12,000+ GitHub stars** . **Log analytics and real-time dashboards** . **Best for real-time analytics** .



- **[Graylog](https://github.com/Graylog2/graylog2-server)**  

  **Centralized log management**, SSPL licensed . **Search, streams, and alerting** . **Best for log management with SIEM capabilities** .



- **[OpenSearch Dashboards](https://github.com/opensearch-project/OpenSearch-Dashboards)**  

  **Visualization for OpenSearch**, Apache-2.0 licensed . **Kibana-compatible dashboards** . **Best for OpenSearch visualization** .



### Additional Strong Open-Source Options



- **Apache Lucene** — The foundation for search engines (Elasticsearch, Solr, OpenSearch) .

- **Bleve** — Go-based search library .

- **Vespa** — Yahoo's search and recommendation engine .

- **ZincSearch** — Lightweight Elasticsearch alternative in Go .

- **Typesense** — Typo-tolerant search engine .

- **Meilisearch** — Fast search engine .

- **Sonic** — Lightweight search backend in Rust .

- **Apache Cassandra** — Distributed storage for log analytics .



**Frameworks for building custom search and log analytics solutions**: Combine **OpenSearch** for full-featured search and log analytics . Use **Quickwit** for cost-effective log search on object storage . Deploy **OpenObserve** for unified observability with minimal storage costs . Choose **Grafana Loki** for Kubernetes-native log aggregation . Integrate **Meilisearch** or **Typesense** for application search . Use **SigNoz** for OpenTelemetry-native observability . Note that true serverless search and log analytics with managed infrastructure, automatic scaling, and vendor-supported SLAs (Amazon OpenSearch Serverless, Elastic Cloud, Axiom) remains primarily commercial territory; open-source stacks provide strong search, aggregation, and visualization foundations that require integration for complete observability.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Log analytics platforms ingest sensitive operational data including application logs, security events, and potentially PII. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **License considerations**: OpenSearch uses Apache-2.0, OpenObserve uses AGPL-3.0, Loki uses AGPL-3.0, and Graylog uses SSPL. Verify licensing against your use case before committing .

- **Storage costs dominate log analytics** — Elasticsearch is expensive for long-term retention. Quickwit and OpenObserve offer 10-140x lower storage costs by using object storage and columnar formats .

- **Full-text search vs. label-based indexing** — OpenSearch indexes full text for powerful search; Loki indexes only labels for cost efficiency. Choose based on query patterns .

- The open-source ecosystem provides strong search, aggregation, and visualization foundations, but **managed infrastructure, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for SREs, observability engineers, and organizations seeking log analytics sovereignty.**  

Let's make serverless search and log analytics more open, transparent, and cost-effective.
