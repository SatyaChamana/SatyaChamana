# Hi, I'm Satya Chamana

> The engineering between the model and the user: RAG pipelines, agentic workflows, and the production infrastructure that holds them together.

**MS in Data Science (3.9 GPA)** · **8+ years shipping production systems** · **Anthropic-certified (Apr 2026)**

---

### Tech stack

**AI / ML:** Python · PyTorch · TensorFlow · Scikit-learn · XGBoost · HuggingFace · OpenCV · YOLOv8

**LLM & Agents:** LangChain · LangGraph · Ollama · MCP · Fine-tuning (LoRA, QLoRA) · Structured Outputs · RAGAS

**Vector & Retrieval:** Qdrant (HNSW) · ChromaDB · PGVector · Hybrid Retrieval (Dense + BM25) · Cross-Encoder Reranking · Sentence-Transformers

**Backend:** Python · Java (Spring Boot) · Go · TypeScript · FastAPI · gRPC · REST APIs · Node.js

**Data:** PostgreSQL · MongoDB · SQL Server · Apache Spark · Kafka · Airflow · ETL Pipelines

**Cloud & MLOps:** AWS (SageMaker, Lambda, S3, CloudWatch) · Azure (Synapse, Data Factory, Entra ID) · GCP (BigQuery, Vertex AI) · Docker · Kubernetes · MLflow · GitHub Actions · On-prem HPC (Ollama)

**Analytics & BI:** Power BI (DAX, DirectQuery) · Tableau · Statistical Modeling · A/B Testing · Cox Proportional Hazards · SHAP · Hypothesis Testing

---

### Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[CodeLens](https://github.com/SatyaChamana/Codelens)** | Multi-model RAG over GitHub repositories. Hybrid HNSW + BM25 retrieval on 768-dim embeddings with sub-100ms p95 latency. Multi-model routing through LangChain. | Python · LangChain · Qdrant · FastAPI · Ollama |
| **[FinSight](https://github.com/SatyaChamana/FinSight)** | Multi-tenant LSTM stock forecasting fused with real-time news sentiment. Event-driven architecture with per-tenant isolation. | Python · PyTorch (LSTM) · FastAPI · Yahoo Finance API |
| **[graphify](https://github.com/SatyaChamana/graphify)** | Knowledge-graph compiler that turns any folder of code, docs, papers, or images into a queryable index. 687 nodes across 45 communities. Companion to my agentic PKM system. | Python (stdlib) · Knowledge Graphs · TF-IDF |
| **[Hospital Readmission Analytics](https://github.com/SatyaChamana/hospital-readmission-analytics)** | End-to-end healthcare analytics on Mass General data: 30-day readmissions, star schema, 24+ DAX measures, 4-page Power BI dashboard aligned with CMS HRRP. | Azure SQL · Power BI · DAX |
| **[Polyp Detection](https://github.com/SatyaChamana/Colonoscopy-Image-Processing)** | Real-time CNN polyp detection on colonoscopy video. Full-stack: TensorFlow backend, React frontend, D3.js diagnostic viz. 93% accuracy on 2,000+ images. | TensorFlow · React · Express · D3.js · OpenCV |

---

### Building in public

> **FinSight Phase 1** // Go + gRPC + portfolio risk
>
> Rewriting the FinSight forecasting layer in Go with gRPC streaming for low-latency multi-tenant inference. PyTorch / ONNX for the model layer. Building from the ground up: health checks, CI/CD, observability, Terraform on AWS. Public progress on the repo.

---

### Impact

- **Sub-50ms p95** RAG retrieval on Qdrant (HNSW indexing, chosen over PGVector)
- **30% hallucination reduction** via RAGAS-eval-driven LLM config selection
- **$25K+ annual LLM cost** eliminated by hosting Ollama on the on-prem HPC cluster
- **99.5% uptime** for 10,000+ daily users on overhauled Spring Boot APIs
- **92% accuracy** XGBoost classifier (Student Early Warning System), enabling 4–6 week earlier intervention
- **70%+ query performance gain** from MS Access to MySQL relational schema migration
- **22% RMSE improvement** over baseline through MLflow + Docker MLOps pipelines for charter-school enrollment forecasting
- **Open-source PR merged** to the RISmed R package (PubMed automation), now used by 200+ researchers

---

### Recognition

- **Anthropic credentials** (Apr 2026): Claude Code in Action · Introduction to Model Context Protocol · AI Fluency: Framework & Foundations
- **Vector Space Day SF** (Jun 2026): attending on personal invite from Andre Zayarni, Qdrant CEO
- **AI Awareness Lunch & Learn** (Aug 2025): 60+ healthcare professionals on LLMs, Agentic AI, RAG, and MCP. 95% positive feedback
- **Dean's Scholarship**, Grand Valley State University (M.S. Data Science, 3.9 GPA)

---

### Writing

I write about Production AI Engineering on [LinkedIn](https://linkedin.com/in/satya-chamana). Recent threads:

- *Why gRPC Over REST for ML Model Serving*: schema evolution under pressure
- *ML Is Not All of AI*: the mental model under the math
- *The Tiny Scale Decision Hiding Inside LinkedIn*: the best engineering is the work you choose not to do
- *Inside the Inference Path, One Layer Said No*: harness engineering vs the model

---

### Currently

FinSight Phase 1 (Go + gRPC + portfolio risk) · Karpathy's neural networks zero-to-hero series · Tracking the open-source LLM landscape weekly

---

### Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=react&logoColor=white)](https://satyachamana.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/satya-chamana)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:satyachamana@gmail.com)
