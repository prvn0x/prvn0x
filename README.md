# Hi there, I'm Praveen Kumar Singh 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prvn0x/)
[![GitHub followers](https://img.shields.io/github/followers/prvn0x?style=social)](https://github.com/prvn0x)
[![Email](https://img.shields.io/badge/Email-praveen230102%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:praveen230102@gmail.com)
<img src="https://komarev.com/ghpvc/?username=prvn0x&label=Profile%20views&color=0e75b6&style=flat" alt="Profile Views" align="right" />

## 🚀 About Me

**Backend Engineer · SDE II | 4+ Years | Distributed Systems & LLM/RAG**

I build backend systems that handle real load — ML-based ETA prediction at **50M+ events/day**, real-time vessel tracking at **700 TPS**, and LLM-powered tools for Fortune 500 customers. Lately I focus on **RAG and LLM evaluation**: retrieval quality, grounded answers, and knowing when the numbers can be trusted.

📍 Based in Chennai, India

## ⭐ Featured Project — [RAGForge](https://github.com/prvn0x/ragforge)

A multi-tenant RAG system over my own Notion notes. Every answer carries a **verified / partial** badge, and the eval layer says how far that badge can be trusted.

- 🔎 **Retrieval:** hybrid keyword + vector search (Postgres/pgvector), RRF fusion, cross-encoder rerank; abstains when the notes don't cover the question.
- 🔒 **Grounding:** answers come only from retrieved notes; a verifier checks citation coverage before the badge shows.
- 🏢 **Multi-tenant:** isolation enforced in the DB via Postgres row-level security, not app code.
- 📊 **Evaluation layer:** frozen snapshots, confidence intervals (Wilson, cluster bootstrap), paired regression gate, planted-error tests.
- 🛡️ **Ops & security:** Prometheus + Grafana alerts, log redaction, secret scanning, CI with Trivy.
- 🧩 **Interfaces:** FastAPI, Streamlit UI, CLI, and an MCP server for Claude Code.

`Python` · `LangGraph` · `FastAPI` · `PostgreSQL/pgvector` · `MCP` · `Prometheus` · `18 ADRs` · `5,500+ tests` · `mypy strict`

## 💼 What I Do (@ FourKites)

- 🔭 **ETA/ETD prediction platform** — Java/Python services at **50M+ events/day, 400–500 TPS**, sub-500ms p99; accuracy **55% → 99%**
- 🤖 **LLM incident intelligence** — retrieval over operational logs with schema-validated outputs & guardrails; resolution **45 min → 60 s**
- 🚢 **Maritime Intelligence platform** — designed from scratch (HLD+LLD), **10,000+ vessels at 700 TPS**, led 5 microservices
- ⚡ **Kafka pipeline** — strict ordering, idempotent consumers, two-tier dedup (Redis+DB), DLQ; **zero message loss**
- 📊 **Observability** — 20+ microservices (Chronosphere, Prometheus, tracing); **MTTR 2h → 30min**

## 🛠️ Tech Stack

**Languages:**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Backend & Architecture:**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat&logo=google&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)
![CQRS](https://img.shields.io/badge/CQRS-512BD4?style=flat)
![DDD](https://img.shields.io/badge/DDD-0D1117?style=flat)
![Event--Driven](https://img.shields.io/badge/Event--Driven-FF6600?style=flat)

**AI & LLM:**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![RAG](https://img.shields.io/badge/RAG-5C4EE5?style=flat)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=flat&logo=postgresql&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat)
![LLM--Eval](https://img.shields.io/badge/LLM_Evaluation-412991?style=flat&logo=openai&logoColor=white)

**Data & Streaming:**

![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![Confluent](https://img.shields.io/badge/Confluent-0074A2?style=flat&logo=apache-kafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Cloud & DevOps:**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat&logo=argo&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

## 📂 Featured Repositories

| Repository | What it is |
|------------|------------|
| [**ragforge**](https://github.com/prvn0x/ragforge) | 🔮 Multi-tenant RAG with verified citations, Postgres RLS, and a statistical eval layer |
| [**agent-eval-pipeline**](https://github.com/prvn0x/agent-eval-pipeline) | 🤖 Evaluation system for AI agents: multi-turn scoring, human annotation (Cohen's κ), failure-pattern detection |
| [**lld-interview-problem**](https://github.com/prvn0x/lld-interview-problem) | 🧩 Low-level design interview problems as Spring Boot modules |
| [**design-patterns-java**](https://github.com/prvn0x/design-patterns-java) | 🎯 20+ Gang of Four design patterns in Java with practical examples |
| [**algorithm-vault**](https://github.com/prvn0x/algorithm-vault) | 📚 DSA solutions organised by topic and difficulty |

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=prvn0x&show_icons=true&theme=tokyonight&hide_border=true" alt="stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prvn0x&layout=compact&theme=tokyonight&hide_border=true" alt="top langs" />
</p>

## 🏅 Achievements & Education

- 🏆 **CodeChef 4-Star** (Rating 1850) · Rank **555 / 10,000+** in Inter-NIT Coding Competition
- 🎓 **B.E. Computer Science**, Chandigarh University (2019–2023) · CGPA **8.6/10**
- 📜 Python Data Structures (Coursera) · HackerRank Problem Solving & Python

## 🤝 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prvn0x/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:praveen230102@gmail.com)

💬 Ask me about: **Distributed Systems · Kafka · RAG & LLM Evaluation · System Design · Kubernetes**

---

<p align="center"><i>Turning complex distributed problems into elegant solutions — one microservice at a time 🚀</i></p>
