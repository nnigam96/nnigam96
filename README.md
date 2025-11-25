# Nikhil R. Nigam

**Machine Learning Engineer** | Building production-grade AI infrastructure that bridges research prototypes and enterprise-scale systems.

---

## Core Competencies

**Languages & Frameworks**
- Python (PyTorch, PyTorch Lightning, TensorFlow)
- LangChain, Hugging Face Transformers, ONNX
- Flask, SQLAlchemy, ReactPy
- Vector Databases: Milvus, FAISS, pgvector

**Infrastructure & MLOps**
- AWS (EC2, S3, EFS, RDS), Docker, Gunicorn, Nginx
- MLflow, Weights & Biases, experiment tracking
- MySQL, PostgreSQL, SQLite
- Git, pytest, systemd, cron orchestration

**Specialized Domains**
- Vector Search & Recommendation Systems
- Agentic AI & MCP (Model Context Protocol) Servers
- Privacy-First ML & HIPAA-Compliant Systems
- Multi-Modal Learning & Computer Vision
- Production MLOps & Artifact Management

---

## Major System Accomplishments

### Vector Search & Recommendation Engine
Architected a real-time, multi-modal vector search system using Milvus that analyzes 240+ meta-features to recommend optimal models. Implemented two-stage retrieval (ANN + re-ranking) with logical partition isolation for multi-tenant privacy. **Impact**: Sub-second latency (<800ms), 5x experiment catalog expansion, now serves as backbone for automated modeling workflow.

**Tech Stack**: Milvus, PyTorch, Python SDK, automated fingerprinting pipeline

### Enterprise Agentic Framework
Designed a reusable Model Context Protocol (MCP) server architecture with schema-driven agent definitions. Built a data aggregator agent that normalizes real-time feeds (APIs, CSV, webhooks) into SQL backends using LangChain orchestration. **Impact**: Reduced agent deployment time from weeks to days, enabled type-safe text-to-SQL capabilities without direct database access.

**Tech Stack**: LangChain, MCP, PostgreSQL, JSON schema validation, SQL templating

### Privacy-First OCR Pipeline
Built a hybrid compliance workflow combining EasyOCR with local Ollama models for zero-PHI document processing. Achieved 100% data sovereignty with no external data egress while maintaining production-quality structured extraction. **Impact**: Enabled compliance-heavy workflows that couldn't use cloud APIs, automated manual data entry for sensitive documents.

**Tech Stack**: Ollama, EasyOCR, local LLM inference, agent orchestration

### Local RAG System with Hybrid Retrieval
Architected a production-ready document Q&A system using FAISS embeddings, sentence-transformers, and hybrid semantic-keyword retrieval. Integrated quantized LLaMA 2 models (Q4_K_M) for sub-second inference on consumer hardware. **Impact**: 40% improvement in answer relevance vs semantic-only search, zero data egress for sensitive documents.

**Tech Stack**: FAISS, llama-cpp-python, sentence-transformers, BM25, real-time indexing

### Historical ML Artifact Migration
Built a retroactive continuity pipeline that migrated 1000+ historical experiment runs from Weights & Biases to MLflow. Rehydrated models, regenerated metadata, and unified artifacts with full lineage. **Impact**: Enabled Day 1 launch of recommendation system with fully populated database, preserved years of R&D data.

**Tech Stack**: W&B API, MLflow, PyTorch, ONNX, batch processing engine

---

## Research & Production Projects

**Neural Machine Translation System**
End-to-end transformer-based German-to-English translation model trained from scratch. Custom encoder-decoder architecture (3 layers, 8 attention heads, 512-dim embeddings) with BLEU evaluation and Flask API deployment. Demonstrates core ML fundamentals: attention mechanisms, sequence data management, production deployment.

**Generative MRI Restoration**
Adapted Stable Diffusion for MRI denoising, replacing iterative N4ITK correction with single-pass generative inference. Achieved 68% reduction in structural error (SSIM) and 1.7x signal clarity improvement. Physics-based training with synthetic RF coil artifacts.

**Multi-Modal Healthcare ML**
Biological age prediction from CT imaging and clinical variables. Multi-modal fusion architecture combining imaging features with clinical data for regression and mortality risk classification. Production ML practices for sensitive medical data.

**Context-Aware Emotion Recognition**
Multi-modal emotion recognition combining body pose and scene context. Dual-branch ResNet architecture predicting 26 discrete emotions and continuous VAD dimensions. YOLO integration for person detection in complex scenes.

**Wireless CSI Compression**
Custom CNN autoencoders for channel state information feedback with novel attention mechanisms (CBAM). Achieved 40% bandwidth reduction over SOTA baselines during research internship at InterDigital.

---

## Experience

**Machine Learning Engineer @ Modlee** (Sept 2023 - Nov 2025)
- System Architect: Deployed real-time vector search engine (Milvus), driving 5x catalog expansion and sub-second predictions
- Agentic AI: Built modular data aggregator framework for SQL/REST data extraction and LLM orchestration
- Privacy Engineering: Designed full-stack, privacy-first OCR pipeline (EasyOCR + Local Ollama) with zero data egress
- Infrastructure & MLOps: Standardized experiment tracking with MLflow, built API verification pipelines for data integrity

**Research & Innovation Intern @ InterDigital** (May 2022 - Aug 2022)
- Developed custom CNN autoencoders for wireless CSI compression
- Achieved 40% bandwidth reduction over SOTA baselines with novel attention mechanisms

**Software Engineer @ Vodafone** (Jul 2018 - Jul 2021)
- Led end-to-end development of FinX financial API serving 5,000+ employees
- Designed "Lazy Approval" UX integrated with Outlook, cutting approval times by 50%
- Maintained 99.9% uptime as Subject Matter Expert for internal financial stack

---

## Education

**M.S. ECE (Machine Learning)** - University of Wisconsin-Madison (GPA: 3.6/4.0)
Focus Areas: Generative AI, Computer Vision, LLMs

**B.Eng. Electronics & Telecom** - MIT Pune, India (First Class with Distinction)
Executive Founding Member, MIT IEEE Student Branch

**Certifications**
- DeepLearning.AI: Natural Language Processing Specialization
- DeepLearning.AI: Advanced Computer Vision with TensorFlow

---

## Connect

**Website**: [nnigam96.github.io](https://nnigam96.github.io)  
**LinkedIn**: [linkedin.com/in/nikhil-nigam-31131b12a](https://linkedin.com/in/nikhil-nigam-31131b12a)  
**GitHub**: [github.com/nnigam96](https://github.com/nnigam96)

---

**Status**: Based in USA (F1 Visa) | Open to opportunities

*"I build the infrastructure that makes AI reliable. From sub-second vector search to privacy-first RAG systems, I bridge the gap between research prototypes and production durability."*
