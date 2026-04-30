# anny — Embedding Evaluation Toolkit (WIP)

**anny** is an upcoming open-source project focused on evaluating and benchmarking embedding models in a simple, reliable, and scalable way.

The goal of anny is to make it easy for developers and researchers to compare different embedding models based on real-world retrieval tasks without worrying about model setup, memory constraints, or system failures.

> Project Status: Early stage — currently in planning and design phase. No production-ready code yet.

---

## Vision

Modern AI applications, especially RAG systems and semantic search, heavily depend on embedding quality. However, evaluating embeddings is often:

* Inconsistent
* Hard to reproduce
* Resource-intensive
* Lacking standard tooling

anny aims to address these challenges by becoming a plug-and-play evaluation framework for embedding models.

---

## Planned Features

* Model-agnostic evaluation supporting multiple open-source embedding models
* Automated model discovery, download, and management
* Memory-aware execution to handle RAM and VRAM constraints
* Failure resilience with fallback and retry mechanisms
* Evaluation metrics such as Top-K accuracy, recall, similarity scoring, and latency
* CLI-first design for simple experimentation workflows

---

## Intended Use Cases

* Benchmark embedding models for RAG pipelines
* Compare embedding strategies across different models
* Evaluate retrieval quality on custom datasets
* Experiment with semantic versus lexical retrieval approaches

---

## Roadmap

* Define evaluation pipeline
* Implement CLI interface
* Integrate embedding model providers (e.g., Ollama)
* Add memory management layer
* Implement fallback and retry logic
* Add benchmarking metrics
* Release first working prototype

---



Stay tuned.
