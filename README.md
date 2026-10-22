# Hi, I'm Praveen 👋

**Backend Engineer (SDE II) · 4+ years · distributed systems and LLM systems**
Chennai, India · [LinkedIn](https://www.linkedin.com/in/prvn0x/) · praveen230102@gmail.com

I build backend systems that handle real load: ML-based ETA prediction at 50M+ events/day,
real-time vessel tracking at 700 TPS, and LLM-powered tools for Fortune 500 customers.
Lately I focus on **RAG and LLM evaluation**: retrieval quality, grounded answers, and knowing
when the numbers can be trusted.

---

## ⭐ Featured project: [RAGForge](https://github.com/prvn0x/ragforge)

A multi-tenant RAG system over my own Notion notes, which I use every day for interview prep.
Every answer carries a **verified / partial** badge, and the eval layer says how far that badge
can be trusted.

- **Retrieval:** hybrid keyword + vector search in Postgres/pgvector, fused with RRF, reranked by a cross-encoder; abstains when the notes don't cover the question.
- **Grounding:** answers come only from retrieved, fenced notes; a verifier checks citation coverage and runs a model ground check before the badge is shown.
- **Multi-tenant by design:** tenant isolation enforced in the database with Postgres row-level security and per-role grants, not in application code.
- **Evaluation layer:** frozen snapshots, confidence intervals (Wilson, cluster bootstrap), a paired regression gate, and planted-error tests that measure whether a wrong fact really takes the badge off. Results tables are generated from run files, never typed.
- **Ops and security:** Prometheus + Grafana with alert rules, structured log redaction, secret scanning, an egress-guard test plugin, CI with Trivy.
- **Interfaces:** FastAPI, a Streamlit UI, a CLI, and an MCP server for Claude Code. Local-first with Ollama, or Gemini by choice.

`Python` `LangGraph` `FastAPI` `PostgreSQL` `pgvector` `MCP` `Prometheus` `Grafana` `Docker` · 18 ADRs · 5,500+ tests · mypy strict

---

## 💼 At work (FourKites)

- **ETA/ETD prediction platform:** Java and Python services processing **50M+ events/day at 400–500 TPS**, sub-500 ms p99; prediction accuracy from **55% to 99%**.
- **LLM incident intelligence:** retrieval over operational logs with schema-validated outputs and guardrails; resolution time from **45 min to 60 s**.
- **Maritime Intelligence platform:** designed from scratch (HLD + LLD); real-time tracking of **10,000+ vessels at 700 TPS**, leading 5 microservices end to end.
- **Kafka pipeline:** strict ordering, idempotent consumers, two-tier dedup (Redis + DB), DLQ, manual offset commits; zero message loss.
- **Observability:** 20+ microservices instrumented (Chronosphere, Prometheus, tracing); **MTTR from 2 h to 30 min**.

Earlier: AI Research Intern at Samsung R&D Institute India (NLP data pipelines, TensorFlow).

---

## 📂 More repositories

| Repository | What it is |
|---|---|
| [ragforge](https://github.com/prvn0x/ragforge) | Multi-tenant RAG with verified citations and a statistical eval layer |
| [agent-eval-pipeline](https://github.com/prvn0x/agent-eval-pipeline) | Evaluation system for AI agents: multi-turn scoring, human annotation with Cohen's kappa, failure-pattern detection, evaluator calibration |
| [lld-interview-problem](https://github.com/prvn0x/lld-interview-problem) | Low-level design interview problems as Spring Boot modules (Java 25) |
| [design-patterns-java](https://github.com/prvn0x/design-patterns-java) | 20+ Gang of Four design patterns in Java with practical examples |
| [algorithm-vault](https://github.com/prvn0x/algorithm-vault) | DSA solutions organised by topic and difficulty |

---

## 🛠️ Tech

**Languages:** Python · Java (8–21) · Go · SQL
**Backend:** Spring Boot 3 · FastAPI · REST · gRPC · GraphQL · CQRS · DDD · event-driven design
**Data and streaming:** Kafka (Confluent) · PostgreSQL / pgvector · Redis · Elasticsearch · MySQL · MongoDB · Redshift
**AI and LLM:** RAG · hybrid search and reranking · LangChain / LangGraph · MCP · tool calling · LLM evaluation (CIs, LLM-as-judge calibration, regression gates)
**Cloud and ops:** AWS · Azure · GCP · Kubernetes · Docker · ArgoCD / GitOps · Prometheus · Grafana

---

🏆 CodeChef 4★ (1850) · Rank 555 / 10,000+ in Inter-NIT Coding Competition
🎓 B.E. Computer Science, Chandigarh University (2019–2023), CGPA 8.6

Also update in the GitHub UI:
- Bio (Edit profile): Backend Engineer · Distributed systems & LLM/RAG systems · Java · Python · Go · Kafka · Kubernetes. Set Location to Chennai.
- RAGForge repo (gear icon next to "About"):
  - description: Multi-tenant RAG over Notion with verified citations, Postgres RLS, and a statistical eval layer;
  - topics: rag, llm, pgvector, langgraph, fastapi, mcp, llm-evaluation, postgresql, python.
- Pins (Customize your pins): ragforge, agent-eval-pipeline, lld-interview-problem, design-patterns-java.

---
