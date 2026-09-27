# Awesome-Application-Monitoring

## Top Application Monitoring Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Observability, Error Tracking & Infrastructure Monitoring*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Application Monitoring**. These tools monitor, analyze, and optimize application performance, error rates, infrastructure health, distributed traces, and user experience across cloud-native, hybrid, and on-premises environments.



**Examples** include New Relic, Datadog, Dynatrace, AppDynamics, Elastic APM, Sentry, Instana, Raygun, Scout APM, and SolarWinds AppOptics (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom instrumentation, and transparent observability pipelines — ideal for engineering teams, SREs, and developers building vendor-neutral monitoring solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[New Relic](https://newrelic.com/)**  

  Full-stack observability platform with APM, infrastructure monitoring, logs, errors, and 780+ integrations for end-to-end application visibility.



- **[Datadog](https://www.datadoghq.com/)**  

  Unified observability and security platform with APM, infrastructure monitoring, log management, RUM, and 750+ turnkey integrations.



- **[Dynatrace](https://www.dynatrace.com/)**  

  AI-driven observability platform with automatic topology discovery, code-level profiling, and enterprise-scale application monitoring.



- **[Cisco AppDynamics](https://www.appdynamics.com/)**  

  Hybrid application observability with auto-discovery, business transaction monitoring, and Cognition Engine for anomaly detection.



- **[Elastic APM](https://www.elastic.co/observability/application-performance-monitoring)**  

  Part of the Elastic Stack, providing distributed tracing, service maps, and OpenTelemetry/Jaeger ingestion with native Kibana visualization.



- **[Sentry](https://sentry.io/)**  

  Application monitoring and error tracking platform with performance monitoring, session replay, and support for 100+ platforms.



- **[IBM Instana](https://www.ibm.com/products/instana)**  

  Enterprise observability with AutoProfile™ continuous production profiling and Dynamic Graph dependency modeling.



- **[Raygun](https://raygun.com/)**  

  Application monitoring and error tracking with crash reporting, real user monitoring, and deployment tracking.



- **[Scout APM](https://scoutapm.com/)**  

  Lightweight, production-grade monitoring focused on line-of-code visibility, N+1 query detection, and memory bloat tracking.



- **[SolarWinds AppOptics](https://www.solarwinds.com/appoptics)**  

  Infrastructure and application performance monitoring with distributed tracing and custom metrics.



## Open-Source GitHub Projects



- **[SigNoz](https://github.com/SigNoz/signoz)**  

  Open-source observability platform native to OpenTelemetry with logs, traces, and metrics in a single application. A leading open-source alternative to Datadog and New Relic, featuring APM with p99 latency, error rate, Apdex, distributed tracing with Flamegraphs, log management powered by ClickHouse, and alerting on all telemetry signals. Over 23,000 stars on GitHub. 



- **[Apache SkyWalking](https://github.com/apache/skywalking)**  

  Application performance monitor designed for microservices, cloud-native, and container-based architectures. Provides distributed tracing, service mesh telemetry, metrics aggregation, and alerting. One of the most widely adopted open-source APM solutions.



- **[Uptrace](https://github.com/uptrace/uptrace)**  

  Open-source APM with distributed tracing, metrics, and logs based on OpenTelemetry. Supports ClickHouse, PostgreSQL, and SQLite backends with a modern Vue.js UI, SQL-like query language for traces, and PromQL-compatible metrics queries. AGPL-licensed and self-hostable via Docker Compose. 



- **[Coroot](https://github.com/coroot/coroot)**  

  Open-source observability and APM tool with AI-powered root cause analysis. Combines metrics, logs, traces, continuous profiling, and SLO-based alerting with predefined dashboards and inspections. Powered by eBPF for zero-instrumentation observability. Apache-2.0 licensed. 



- **[OpenObserve](https://github.com/openobserve/openobserve)**  

  Open-source observability platform offering logs, metrics, traces, dashboards, and alerts in a single binary. Features native OTLP support, SQL and PromQL query languages, and 140x lower storage costs than Elasticsearch through Parquet columnar format and S3-native architecture. AGPL-3.0 licensed. 



- **[Jaeger](https://github.com/jaegertracing/jaeger)**  

  Distributed tracing platform originally built by Uber, now a CNCF graduated project. Provides end-to-end distributed tracing, root cause analysis, service dependency analysis, and native OpenTelemetry support.



- **[GlitchTip](https://github.com/glitchtip/glitchtip-backend)**  

  Open-source, Sentry-compatible error tracking and uptime monitoring platform. Collect error reports, monitor application performance, and track uptime using standard Sentry SDKs. Lightweight and container-native with PostgreSQL and Redis dependencies. 



- **[Scouter](https://github.com/scouter-project/scouter)**  

  Open-source APM similar to New Relic and AppDynamics. Features Java Agent for web applications, Host Agent for Linux/Windows/Unix, and Telegraf support for Redis, nginx, Kafka, MySQL, MongoDB, and more. Provides XLog scatter charts, method profiles, SQL profiles, and resource metrics. 



- **[OpenObserve](https://github.com/openobserve/openobserve)**  

  Datadog/Splunk alternative with single-platform architecture for logs, metrics, and traces. SOC 2 Type II and ISO 27001 certified, GDPR compliant, and HIPAA ready. 



- **[Prometheus](https://github.com/prometheus/prometheus)**  

  The de facto standard for Kubernetes monitoring. Pull-based metrics collection with PromQL query language and Alertmanager integration. Often paired with Grafana for dashboards. 



- **[Grafana](https://github.com/grafana/grafana)**  

  Leading open-source visualization and dashboarding platform. Pulls data from Prometheus, Loki, Tempo, ClickHouse, and 100+ other sources for unified observability views. 



- **[Grafana Tempo](https://github.com/grafana/tempo)**  

  High-volume, minimal dependency distributed tracing backend. Integrates with Grafana for trace visualization and correlates with Prometheus metrics and Loki logs. 



- **[Grafana Loki](https://github.com/grafana/loki)**  

  Horizontally scalable, multi-tenant log aggregation system inspired by Prometheus. Designed for cost-effective log storage and integrates with Grafana for visualization. 



- **[OpenTelemetry](https://github.com/open-telemetry)**  

  Vendor-neutral collection of APIs, SDKs, and tools for instrumenting, generating, collecting, and exporting telemetry data (metrics, logs, traces). The de facto standard for modern monitoring instrumentation with agents for every major language. 



- **[Netdata](https://github.com/netdata/netdata)**  

  Open-source infrastructure monitoring with per-second granularity. Zero-configuration agent auto-detects services like Nginx, Docker, MySQL, and MongoDB. Highly rated on CNCF landscape. 



- **[Zabbix](https://github.com/zabbix/zabbix)**  

  Popular open-source solution for monitoring network, cloud, servers, Windows, logs, and applications. Long-standing enterprise-grade monitoring platform. 



- **[Elasticsearch + Kibana](https://github.com/elastic/elasticsearch)**  

  Open-source search and analytics engine (Elasticsearch) paired with visualization (Kibana). Forms the ELK stack with Logstash for log management and observability. 



- **[quickwit](https://github.com/quickwit-oss/quickwit)**  

  Cloud-native search engine for observability. Open-source alternative to Datadog, Elasticsearch, Loki, and Tempo with sub-second search on massive datasets. 



- **[Netdata](https://github.com/netdata/netdata)**  

  Real-time performance and health monitoring with per-second granularity and auto-discovery. Lightweight agent consuming ~1% of a single CPU core. 



- **[Checkmate](https://github.com/bluewave-labs/checkmate)**  

  Open-source, self-hosted monitoring tool for uptime, response times, server hardware, and incidents. Features HTTP/HTTPS/Ping/Docker/Port/Game/gRPC/WebSocket monitoring, Lighthouse page speed measurement, status pages, and beautiful visualizations. 



- **[WGCLOUD](https://github.com/tianshiyeben/wgcloud)**  

  Lightweight distributed operations monitoring platform supporting Linux/Windows/macOS. Covers hosts, Docker, K8s, Redis, RocketMQ, IPMI, and more with Web SSH, intelligent alerting, and AI analysis. 



- **[Fodaris](https://github.com/goodhallsolutions/fodaris)**  

  Self-hosted monitoring and observability platform for homelabs and small businesses. Monitors servers, Docker containers, network devices (SNMP), websites, APIs, databases, and applications from a single dashboard. 



- **[Argus](https://github.com/oluwatobicode/argus)**  

  Open-source error tracking and performance monitoring across browser, Node.js, and React Native. Captures errors, groups them into issues, tracks performance, and alerts before users do. Features SDKs for React, Vue, Angular, Next.js, Svelte, and NestJS. 



- **[Rails Error Dashboard](https://github.com/AnjanJ/rails_error_dashboard)**  

  Fully open-source, self-hosted error tracking Rails engine. Exception monitoring with dashboard UI, multi-channel notifications (Slack, Email, Discord, PagerDuty), and 5-minute setup. Self-hosted Sentry alternative for Rails 7.0-8.1. 



- **[Proof](https://github.com/scr34m/proof)**  

  Minimal Sentry alternative / drop-in replacement for development and local use. Supports Sentry protocols 4 and 7 with easy installation without extra dependencies. 



- **[HttpReports](https://github.com/dotnetcore/HttpReports)**  

  APM system for .NET Core applications. Provides request tracking, performance monitoring, and distributed tracing for .NET ecosystems. 



### Additional Strong Open-Source Options



- **OpenAPM Node.js** — APM for Node.js using Prometheus for metrics collection and exposition.

- **Kamon** — Distributed tracing, metrics, and context propagation for JVM applications.

- **Brave** — Java distributed tracing implementation compatible with Zipkin backend services.

- **SkyWalking Java Agent** — Java agent for Apache SkyWalking with automatic instrumentation.

- **SkyWalking .NET** — .NET/.NET Core instrument agent for Apache SkyWalking.

- **OpenCensus** — Legacy stats collection and distributed tracing framework (predecessor to OpenTelemetry).

- **Zipkin** — Distributed tracing system with instrumentation for multiple languages.



**Frameworks for building custom monitoring solutions**: Combine **OpenTelemetry** for instrumentation, **Prometheus** for metrics, **Loki** for logs, **Tempo** or **Jaeger** for traces, and **Grafana** for visualization. For integrated open-source APM, **SigNoz**, **Uptrace**, or **OpenObserve** offer self-hosted alternatives to SaaS platforms. For eBPF-based zero-instrumentation monitoring, **Coroot** provides automatic service mapping and root cause analysis.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Monitoring tools must comply with data privacy regulations (GDPR, CCPA, etc.) and industry-specific compliance requirements.

- Self-hosted open-source solutions require proper infrastructure, security hardening, and ongoing maintenance.



---



**Made for SREs, DevOps engineers, platform teams, and application developers.**  

Let's make application monitoring more open, observable, and vendor-neutral.
