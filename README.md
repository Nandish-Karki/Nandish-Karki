# Hi, I'm Nandish Karki 👋

### Software Engineer · Data & AI Engineer · AI Systems Builder

I build **data and AI systems that are designed to be useful, measurable, and reliable** — from production data pipelines and retrieval systems to agentic applications, real-time AI services, and evaluation infrastructure.

I have **4.2+ years of engineering experience across industry and applied research**, including **3.2+ years at Clarivate Analytics** building and optimizing production data/ETL pipelines and **~1 year as a Research Assistant at OvGU** working on real-time AI systems in industry collaboration.

Currently completing my **M.Sc. in Data & Knowledge Engineering at Otto von Guericke University Magdeburg (OvGU)**, with graduation expected in **October 2026**. I am actively seeking **full-time Data Engineering, AI/ML Engineering, Software Engineering, and AI Infrastructure roles starting November 2026**.

---

## What I Build

- **AI Evaluation & Reliability** — evaluation frameworks, regression detection, LLM-as-a-Judge, retrieval evaluation, calibration and reproducibility
- **RAG & Agentic Systems** — retrieval-augmented applications, multi-agent workflows, structured validation and tool-based reasoning
- **Data Engineering** — ETL pipelines, distributed processing, data transformation and cloud-based data workflows
- **AI/ML Systems** — deep learning, NLP, speech processing, model inference and AI microservices
- **Production Engineering** — Dockerized services, APIs, testing, monitoring and deployment workflows

---

## Featured Projects

### 🔍 Proof — AI Evaluation & Regression Detection Framework

An open-source framework for evaluating AI systems and detecting regressions across **answer quality, retrieval quality, judges, cost, latency and reproducibility**.

**Highlights**
- Deterministic and configurable evaluation
- Recall@K, MRR, nDCG and graded retrieval relevance
- LLM-as-a-Judge with structured validation
- Judge caching and provenance tracking
- Human calibration
- Python and HTTP target adapters
- Baseline comparison and configurable regression gates
- JSON/Markdown reporting and CLI workflows

**External validation**

I built an independent RAG system and changed retrieval from **TOP_K=5 → TOP_K=1**. The generated answers remained byte-identical across all 26 cases, while retrieval quality dropped:

- Recall@3: **0.979 → 0.917**
- Recall@5: **0.979 → 0.917**
- nDCG: **0.997 → 0.970**

Proof detected the regression even though the final answers did not change.

[View Proof →](https://github.com/Nandish-Karki/proof)  
[View external RAG validation →](https://github.com/Nandish-Karki/proof-demo-rag)  
[View v0.3.10 release →](https://github.com/Nandish-Karki/proof/releases/tag/v0.3.10)

---

### 🤖 Agentic Study Planner

A multi-agent planning system for generating study plans from programme rules, course information and student constraints.

**Highlights**
- Multi-agent analysis and planning
- Parallel specialist agents
- Structured programme-rule reasoning
- Deterministic Python-side validation for constraints and calculations
- FastAPI backend and React/TypeScript frontend
- Dockerized deployment

🔗 [Live Demo →](https://agentic-study-planner.vercel.app)  
💻 [View project →](https://github.com/Nandish-Karki/Agentic-Study-Planner)

---

### 🔎 LexiQuery — Natural Language SQL Analytics SaaS

A full-stack analytics platform that lets users query CSV files and live PostgreSQL/MySQL databases using natural language, translating questions into SQL and turning results into interactive visualizations.

**Highlights**
- FastAPI + React/TypeScript + PostgreSQL + DuckDB with OpenAI GPT-4o for NL→SQL
- Deterministic 18-type chart inference engine without additional LLM calls
- Multi-tenant guest isolation, quotas and ephemeral dataset management
- Secure read-only live database connections with encrypted credentials
- bcrypt, JWT refresh-token rotation, rate limiting and security headers
- Dockerized CI/CD with GitHub Actions
- 89-test suite with 100% passing tests

🔗 [Live Demo →](https://natural-language-data-analyst.vercel.app/)

---

### 📚 AI-Based Learning Assistant

A full-stack RAG-based learning assistant combining document retrieval, semantic search and generative AI.

**Highlights**
- Retrieval-Augmented Generation
- Vector search
- Semantic embeddings
- Full-stack application architecture
- AI-assisted learning workflows
- Multiple model/service integrations

💻 [View project →](https://github.com/Nandish-Karki/AI-Based-Learning-Assistant)

---

### 🧠 Audio Steganalysis

A deep-learning project for detecting and removing LSB-based audio steganography.

**Highlights**
- PyTorch
- WaveCNN
- Autoencoders / denoising autoencoders
- Audio preprocessing and reconstruction
- Steganalysis experiments
- Docker / Gradio workflow

💻 [View project →](https://github.com/Nandish-Karki/stego-detection)

---

## Technical Focus

### Data Engineering

`Python` `SQL` `PySpark` `AWS` `Glue` `Redshift` `Airflow` `ETL`

### AI / ML

`PyTorch` `NLP` `RAG` `LLM` `LLM-as-a-Judge` `Information Retrieval` `Deep Learning`

### AI Systems

`Multi-Agent Systems` `FastAPI` `Microservices` `Docker` `Evaluation` `Regression Testing`

### Engineering

`Git` `Testing` `REST APIs` `Linux` `Cloud` `CI/CD`

---

## Professional Experience

### Software Engineer — Clarivate Analytics

**3.5+ years**

Built and optimized production data and ETL systems, with work spanning data processing, pipeline performance and cloud-oriented workflows.

### Research Assistant — OvGU Magdeburg

**Oct 2025 – Oct 2026**

Working on real-time AI systems and speech-to-speech translation in collaboration with industry, with a focus on AI inference, microservices, deployment and system performance.

---

## Education

### M.Sc. Data & Knowledge Engineering — OvGU Magdeburg

**Oct 2024 – Oct 2026 (Expected)**

### B.E. Computer Science — Ramaiah Institute of Technology

**Aug 2017 – Jul 2021**

---

## A Few Things I Care About

**Correctness over demos.**  
I like building systems where important behavior can be tested and measured instead of assumed.

**Deterministic logic around probabilistic systems.**  
When an LLM is involved, I prefer keeping critical validation, constraints and measurable checks outside the model wherever practical.

**Evaluation as part of engineering.**  
An AI system isn't finished when it produces an answer. I want to know whether it continues to produce good answers after the next change.

**Simple systems that can be understood.**  
I prefer clear interfaces, explicit contracts and small components over unnecessary complexity.

---

## Currently

🎓 **M.Sc. Data & Knowledge Engineering — OvGU Magdeburg**  
📅 **Expected completion: October 2026**  
📍 **Magdeburg, Germany**

### Seeking

**Full-time Data Engineering · AI/ML Engineering · Software Engineering · AI Infrastructure roles**

**Available from November 2026**

Open to opportunities across **Germany and the EU**.

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/nandish-karki/)

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-black?style=flat-square&logo=google-chrome)](https://nandish-portfolio-two.vercel.app/)

[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat-square&logo=github)](https://github.com/Nandish-Karki)

---

> **Build it. Measure it. Improve it.**
