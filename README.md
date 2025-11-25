# Nikhil Nigam

**Machine Learning Engineer** | Systems over Scripts.

I engineer the infrastructure that makes AI reliable. My focus is on the "messy middle" of ML—taking research concepts and hardening them into high-availability production systems. I specialize in low-latency Retrieval Systems, Privacy-First Architectures, and Agentic Platforms.

---

### Engineering Philosophy
* **Systems > Models:** A SOTA model is useless if inference latency is 4 seconds. I optimize for throughput and reliability first.
* **Type Safety:** I write strictly typed Python. If it's not in the schema, it doesn't exist.
* **Data Sovereignty:** I prefer architectures that keep data local (on-device inference) over blind API calls.

---

### Selected Engineering

**[Distributed LLM Lab](https://nnigam96.github.io/projects/distributed-llm-lab)**
A production-grade monorepo for distributed AI systems. Implements **Speculative Decoding** (Mac/Windows hybrid inference) and **Federated Learning** (privacy-preserving training) using raw TCP sockets and custom binary protocols.

**[Machine Translation System](https://nnigam96.github.io/projects/de_to_en_translator)**
Built a Transformer from scratch (PyTorch) to translate German to English. Implemented custom multi-head attention and positional encodings to understand the architecture from first principles.

**[Doc-Assist RAG](https://nnigam96.github.io/projects/doc_assist)**
Architected a privacy-first document Q&A system. Combines **FAISS** vector search with local quantized **LLaMA 2** inference to ensure zero data egress for sensitive documents.

**[Generative MRI Restoration](https://nnigam96.github.io/projects/DDM2)**
Adapted Stable Diffusion to replace slow, iterative MRI correction with single-pass generative inference. Achieved a **68% reduction in structural error** (SSIM) on medical imaging data.

---

### Technical Stack
* **Core:** Python, PyTorch, Lightning, SQL
* **Agentic:** LangChain, Ollama, MCP (Model Context Protocol)
* **Infra:** AWS (EC2, S3), Docker, Milvus, MLflow

---

[Portfolio](https://nnigam96.github.io) | [LinkedIn](https://linkedin.com/in/nikhil-nigam-31131b12a) | [Email](mailto:niknigam96@gmail.com)
