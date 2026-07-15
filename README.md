# Venkata Deepak Reddy Penubaka

**AI/ML Engineer** — building production systems around LLMs, retrieval, and agents.

I'm interested in the part of ML that starts after the model works on a laptop: grounding answers in real sources, measuring whether they're actually correct, and catching the moment a system quietly stops working in production.

📍 San Francisco, CA · [LinkedIn](https://linkedin.com/in/deepakreddy08) · pvdeepakreddy08@gmail.com

---

## Projects

### 🔍 [RAG Document Q&A](https://github.com/deepakreddy0811/rag-document-qa)
Ask questions about your own documents and get answers grounded in their actual content.
Chunking with overlap → sentence-transformer embeddings → FAISS similarity search → grounded prompting.

`Python` `FastAPI` `FAISS` `sentence-transformers`

### 🤖 [Multi-Agent Assistant](https://github.com/deepakreddy0811/multi-agent-assistant)
Planner, researcher, and writer agents collaborating on a task through a shared-state orchestrator.
The researcher selects and invokes tools from a registry using a reason-then-act (ReAct) loop.

`Python` `Tool Calling` `Agent Orchestration` `FastAPI`

### 📊 [LLM Evaluation Harness](https://github.com/deepakreddy0811/llm-eval-harness)
Measures LLM answer quality — correctness, hallucination, and abstention — and fails CI when it regresses.
Built around a finding worth internalising: a model that refuses every question can outscore one that hallucinates, on the same metric. No single number is trustworthy alone.

`Python` `LLM-as-Judge` `Hallucination Detection` `CI/CD`

### ⚙️ [MLOps Pipeline](https://github.com/deepakreddy0811/mlops-pipeline)
The lifecycle after `model.fit()`: MLflow-tracked training, containerised serving, and PSI drift monitoring validated against both a control sample and a deliberately shifted distribution.
Also a good reminder that the simpler model sometimes just wins — logistic regression edged out random forest here.

`scikit-learn` `MLflow` `FastAPI` `Docker` `Drift Detection`

---

## Stack

**Languages** · Python, Java, SQL

**AI/ML** · PyTorch, TensorFlow, Hugging Face Transformers, scikit-learn, LangChain, LangGraph

**LLM & Retrieval** · RAG, vector search, embeddings, tool calling, multi-agent systems, prompt engineering, LLM evaluation

**Data & Infra** · Apache Spark, Kafka, Databricks, Ray

**MLOps & Cloud** · MLflow, Docker, Kubernetes, AWS (SageMaker, S3, EKS), CI/CD, Prometheus, Grafana

**Databases** · PostgreSQL, Redis, FAISS, Pinecone, Weaviate

---

## Certifications

- AWS Certified Machine Learning Engineer – Associate
- Databricks Certified Generative AI Engineer Associate
- DeepLearning.AI — Multi AI Agent Systems with CrewAI

---

## Education

**M.S. Computer Science and Engineering** — University at Buffalo

**B.Tech Computer Science and Engineering** — Puducherry Technological University
