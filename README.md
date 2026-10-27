# Hi, I'm Himanshu Vishwakarma 👋

**Backend & Generative AI Engineer** | Python · FastAPI · Django · LangGraph · GraphRAG

I architect low-latency Python microservices and production-grade LLM systems. My focus is multi-agent orchestration (LangGraph, LangChain), hybrid vector-graph retrieval (Qdrant, Neo4j), and high-throughput async data pipelines. I've brought production p95 API latencies below 300ms, cut 5xx error rates to under 0.8%, and validated RAG pipelines against recall and entailment benchmarks.

📍 Noida, Uttar Pradesh (open to relocation)  
📧 hi.himanshu21@gmail.com

## 🌐 Socials

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-vishwakarma-tech/)
[![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/Himanshu_21vi)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white)](mailto:hi.himanshu21@gmail.com)

## 💼 Experience

- **Founding Backend & AI Engineer (SDE)**, Kaizen Art & Craft (Remote), Feb 2026 – Present
  - Built the core backend for a D2C furniture e-commerce platform (500+ SKUs) using Django REST Framework and PostgreSQL.
  - Cut catalog API p95 latency from ~450ms to ~290ms by eliminating N+1 ORM queries.
  - Built an LLM catalog ingestion pipeline (Pydantic structured outputs) automating SEO metadata, taxonomy tagging and search indexing.
  - Set up zero-downtime deployments on Render with Docker and GitHub Actions CI/CD.
- **Software Development Engineer**, Circle Chess (Bangalore), Jul 2025 – Jan 2026
  - Reduced p95 latency from ~600ms to ~380ms for a platform serving 10,000+ active users (composite PostgreSQL indexes, Redis caching).
  - Dropped production 5xx rates from 3.2% to <0.8% by fixing connection pool exhaustion, using Grafana telemetry and alerts.
  - Designed a fault-tolerant LLM service layer with output validation, exponential backoff retries and model fallback routing.
- **Full Stack Developer Intern**, Softpro (Lucknow), Jun 2024 – Aug 2024
  - Cut dashboard data refresh latency from ~1.8s to ~650ms; built webhook integrations and ETL cron pipelines.

## 🚀 Featured Projects

### 🔍 Incident Root Cause Analysis (RCA) Assistant: Multi-Agent GraphRAG
`Python` `LangGraph` `FastAPI` `Qdrant` `Neo4j` `Drain3` `Docker`
- Autonomous debugging pipeline combining Qdrant (incident history) with Neo4j to traverse microservice dependency graphs and Git commit lineage.
- Drain3 log clustering compresses 10,000+ raw logs into ~150 templates, cutting prompt tokens by 90%.
- Hybrid retrieval (BM25 + BGE-M3 with RRF and BGE cross-encoder reranker) raised Top-5 root-cause recall from 64% to 86% on 100+ simulated incidents.

### 🧪 Veritas: Autonomous Multi-Agent Research & Fact-Checking Engine
`Python` `FastAPI` `Asyncio` `Pydantic` `SQLite` `SSE`
- 5-agent cyclic workflow (Planner, Scout, Reader, Skeptic, Writer) where the Skeptic agent checks claims against source abstracts using structured entailment scoring and citation verification.
- Async ingestion fetches and deduplicates 40+ papers across arXiv, Semantic Scholar, OpenAlex and Crossref in under 3.8s.
- Multi-LLM router (OpenAI, Gemini, Ollama) with real-time SSE streaming and export to JSON, Markdown and HTML.

## 💻 Tech Stack

![Python](https://img.shields.io/badge/python-3776AB.svg?style=plastic&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/fastapi-009688.svg?style=plastic&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=plastic&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000.svg?style=plastic&logo=django&logoColor=white)
![LangChain](https://img.shields.io/badge/langchain-1C3C3C.svg?style=plastic&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/langgraph-1C3C3C.svg?style=plastic&logoColor=white)
![OpenAI](https://img.shields.io/badge/openai-412991.svg?style=plastic&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/gemini-8E75B2.svg?style=plastic&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/ollama-000000.svg?style=plastic&logo=ollama&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-4169E1.svg?style=plastic&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/qdrant-DC244C.svg?style=plastic&logoColor=white)
![Neo4j](https://img.shields.io/badge/neo4j-4581C3.svg?style=plastic&logo=neo4j&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=plastic&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=plastic&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=plastic&logo=sqlite&logoColor=white)
![ChromaDB](https://img.shields.io/badge/chromadb-FF6446.svg?style=plastic&logoColor=white)
![Docker](https://img.shields.io/badge/docker-2496ED.svg?style=plastic&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-2088FF.svg?style=plastic&logo=githubactions&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-F46800.svg?style=plastic&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/linux-FCC624.svg?style=plastic&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/git-F05032.svg?style=plastic&logo=git&logoColor=white)
![Render](https://img.shields.io/badge/render-000000.svg?style=plastic&logo=render&logoColor=white)
![Streamlit](https://img.shields.io/badge/streamlit-FF4B4B.svg?style=plastic&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=plastic&logo=pandas&logoColor=white)

**GenAI & LLMs:** LangGraph, LangChain, GraphRAG, Multi-Agent Systems, Tool Calling, Structured Outputs (Pydantic), LLM Evaluation & Guardrails, Prompt Engineering  
**Search & Models:** Hybrid Search (BM25 + Dense), Cross-Encoder Reranking (BGE-Reranker), BGE-M3 Embeddings, Token Optimization (Drain3)

## 🎓 Education

B.Tech in Computer Science & Engineering, Dr. A.P.J. Abdul Kalam Technical University (2021 – 2025), CGPA 8.33 / 10

## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=Himanshu-2122&theme=dark&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=Himanshu-2122&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Himanshu-2122&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)
