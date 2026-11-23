# Ansh Taneja

<p align="left">
  <b>Senior Tech Lead & Systems Architect</b> · 12+ Years Experience<br/>
  Distributed Java 21 · Cloud Platforms (AWS / Azure) · Agentic AI & RAG · DevSecOps
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ansh_Taneja-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ansh-taneja-22b5a124/)
[![AWS Certified](https://img.shields.io/badge/AWS-Solutions_Architect-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](#certifications)
[![AZ-400](https://img.shields.io/badge/Azure-DevOps_Engineer_Expert-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](#certifications)
[![AZ-204](https://img.shields.io/badge/Azure-Developer_Associate-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](#certifications)
[![Patents](https://img.shields.io/badge/Patents-2_Filed_(Automotive_Cloud)-6f42c1?style=flat-square)](#patents)
[![M.Tech](https://img.shields.io/badge/M.Tech-Cyber_Security_(IIT_Kanpur)-b31b1b?style=flat-square)](#education)

---

## 👨‍💻 About Me

I am a Senior Tech Lead and Systems Architect with 12+ years of experience engineering high-throughput, mission-critical distributed platforms across automotive, IoT, and enterprise cloud software.

- 🚗 **Current Focus:** Senior Java Developer & Tech Lead at **Mercedes-Benz R&D** on **Guard360** — a connected-car telemetry platform processing millions of events per day under strict 99.8% uptime SLAs on Azure Kubernetes.
- 🤖 **Agentic AI & LLMOps:** Pioneer of production-grade agentic architectures combining **Java 21**, **Spring AI**, **LangChain4j**, **MCP (Model Context Protocol)** servers, and **pgvector** hybrid RAG.
- 🛡️ **Security-First Architecture:** Background in **M.Tech Cyber Security from IIT Kanpur** with 2 automotive patents filed in connected vehicle telemetry and security.

---

## 🌟 Featured Production Architecture

### 🚀 [spring-ai-mcp-agent](https://github.com/Toansh/spring-ai-mcp-agent)
> **Production-grade Diagnostic Triage Agent built with Java 21, Spring AI, MCP, Claude API, and pgvector.**

- **The Challenge (v1):** Direct streaming of raw vehicle telemetry into LLM context resulted in 180k+ token sessions, 4× cost explosions, and hallucinations on noisy sensor anomalies.
- **The Solution (v2):** Re-engineered with a **deterministic SQL pre-aggregation layer**, schema-validated MCP endpoints, prompt caching, and an automated **LLM-as-judge evaluation harness**.
- **Impact:**
  - ⚡ **55% P50 Latency Reduction** (4.2s → 1.9s)
  - 💰 **65% Token Cost Reduction** per triage session
  - 🎯 **98.6% Root-Cause Accuracy** against a 200-scenario gold-standard dataset

### ☸️ [k8s-mlops-platform](https://github.com/Toansh/k8s-mlops-platform)
> **Production Kubernetes MLOps platform featuring Terraform EKS, Helm 3, ArgoCD GitOps, FastAPI serving with custom HPA, and statistical drift detection.**

- **GitOps Control Plane:** Declarative ArgoCD App-of-Apps pattern managing multi-tenant namespaces (`mlops-infra`, `mlops-serving`, `mlops-monitoring`) with zero configuration drift.
- **High-Throughput Serving:** Sub-15ms P99 latency FastAPI inference runtime autoscaling via Prometheus custom metrics (`http_requests_per_second`).
- **Autonomous Drift Governance:** Automated Kolmogorov-Smirnov (KS) test ($p < 0.05$) and Population Stability Index (PSI $\ge 0.20$) CronJob alerting on covariate and concept drift.
- **Zero-Trust Security:** Default-deny NetworkPolicies, non-root containers, and IRSA least-privilege cloud IAM.

### ☕ [cloud-native-java-blueprint](https://github.com/Toansh/cloud-native-java-blueprint)
> **Production-grade Spring Boot 3.3 & Java 21 enterprise microservices blueprint demonstrating the Transactional Outbox Pattern, Apache Kafka, and Testcontainers.**

- **Dual-Write Mitigation:** Atomic local ACID persistence coupling domain state mutations with outbox events, guaranteeing zero event loss under crash failure.
- **High-Throughput Outbox Relay:** Background worker with pessimistic row-level locking dispatching at 3,500+ ops/sec with <70ms relay lag.
- **Observability & Fault Tolerance:** Full W3C TraceContext propagation across HTTP and Kafka headers via OpenTelemetry, paired with Resilience4j circuit breaking.
- **Production Testing:** End-to-end integration test suite running on live PostgreSQL 16 and Kafka KRaft Testcontainers.

---

## 🛠️ Technical Competency

### Core Languages & Enterprise Frameworks
![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.x-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Quarkus](https://img.shields.io/badge/Quarkus-4695EB?style=for-the-badge&logo=quarkus&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### AI, LLMOps & Vector Retrieval
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![LangChain4j](https://img.shields.io/badge/LangChain4j-1C3C3C?style=for-the-badge&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API_(Anthropic)-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol_(MCP)-4A154B?style=for-the-badge&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector_(HNSW)-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)

### Cloud Infrastructure & GitOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes_(EKS/AKS)-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm_3-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Observability, Data & DevSecOps
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_16-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![HashiCorp Vault](https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

## 🏆 Certifications & Education

<a name="certifications"></a>
### Industry Certifications
- **AWS Certified Solutions Architect – Associate** (Amazon Web Services)
- **Microsoft Certified: DevOps Engineer Expert** (AZ-400)
- **Microsoft Certified: Azure Developer Associate** (AZ-204)
- **Microsoft Certified: Azure Fundamentals** (AZ-900)

<a name="education"></a>
### Education & Patents
- **M.Tech in Cyber Security** — *Indian Institute of Technology (IIT) Kanpur*
- **B.Tech in Computer Science** — *Visvesvaraya Technological University (VTU)*
- <a name="patents"></a>**2 Automotive Cloud & Telemetry Patents Filed** (Mercedes-Benz R&D)

---

## 💡 Engineering Philosophy

1. **LLMs reason; databases aggregate.** Don't spend token budgets doing in-context data engineering that a PostgreSQL query or streaming filter does in 20ms for free.
2. **Observability is part of 'Definition of Done'.** OpenTelemetry spans, metrics, and structured logs are first-class architecture deliverables. If it can't be debugged at 3 AM via Grafana, it shouldn't be in production.
3. **Security is a design constraint, not a compliance checkbox.** With a background from IIT Kanpur Cyber Security, zero-trust, automated dependency audits (OWASP), and least-privilege RBAC are built into every microservice by default.
4. **Cloud-native means disposable infrastructure.** Declarative GitOps, immutable Docker images, and automated CI/CD pipelines cut deployment friction and operational toil.

---

## 📬 Connect

- **LinkedIn:** [linkedin.com/in/ansh-taneja-22b5a124](https://www.linkedin.com/in/ansh-taneja-22b5a124/)
- **GitHub:** [github.com/Toansh](https://github.com/Toansh)
