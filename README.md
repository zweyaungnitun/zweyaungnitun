# Zwe Yaung Ni Tun
**AI Engineer | AI & Multi-Agent Systems Builder | Cloud Architect**

Hello! I am a software engineer focused on designing intelligent, agentic workflows and architecting scalable, high-performance cloud infrastructure. With a background in full-stack development and a deep interest in advanced AI engineering, I build systems that are both conceptually ambitious and practically cost-effective. 

Beyond coding, I am passionate about mentoring junior developers and streamlining technical workflows.

---

## 🚀 Featured Engineering Projects

### 1. Agentic AI Job Matcher & CV Review System
[**🔗 View Repository**](https://github.com/zweyaungnitun/AI-Resume-Job-Matching-Agent.git)

An intelligent pipeline designed to automate and enhance technical recruitment processes through advanced natural language understanding and multi-agent coordination.
* **Architecture:** Built utilizing **FastAPI** for robust backend routing, seamlessly integrated with **LangGraph** to orchestrate complex, multi-agent workflows.
* **Core Mechanics:** Leverages advanced Retrieval-Augmented Generation (RAG) and vector database indexing to parse, analyze, and query unstructured CV data against dynamic job requirement matrices.

### 2. AI Astrologer System
[**🔗 View Repository**](https://github.com/zweyaungnitun/AI-Astrology-chatbot-api)

An analytical engine combining traditional event prediction systems with modern AI capabilities to automate and translate complex birth chart interpretations.
* **Architecture:** Utilizes **Python** libraries and specialized external APIs to retrieve, compute, and parse astronomical data, focusing heavily on Vedic and Krishnamurti Padhdhati (KP) astrological frameworks.
* **Core Mechanics:** Processes raw chart mechanics—such as precise planetary strength ratios, significators, and dasha sequences—and leverages LLMs to generate comprehensive, narrative-driven readings and compatibility analyses.

### 3. Agent Evaluation Suite
[**🔗 View Repository**](https://github.com/zweyaungnitun/agent-eval-suite)

A reusable evaluation harness for **LangChain** and **LangGraph** agents that automates quality scoring and gates CI builds on metric thresholds.
* **Architecture:** Adapter pattern normalizes any agent flavor — plain callable, LangChain Runnable, or LangGraph compiled graph — into a unified interface, with concurrent test execution via `ThreadPoolExecutor`.
* **Core Mechanics:** Stacks three metric layers — **RAGAS** for RAG quality, **DeepEval** for assertion-style checks, and custom **trajectory analysis** — and emits per-run traces to **LangSmith** or **Arize Phoenix** for failure inspection.


### 4. Agentic Nutrition Analyst
[**🔗 View Repository**](https://github.com/zweyaungnitun/AI-Nutrition-Analyst)

A multimodal AI agent that acts as a personal nutrition coach, analyzing meal photos to deliver accurate calorie breakdowns, macro estimates, and conversational health advice backed by verified nutritional data.
* **Architecture:** A LangGraph-orchestrated multi-node pipeline routes each input through a Router Node that dynamically decides between visual analysis and conversational response, with persistent memory across turns enabling context-aware follow-up questions.
* **Core Mechanics:** Combines GPT-4o / Gemini 1.5 Flash vision models for ingredient detection and portion estimation with USDA FoodData Central API cross-referencing for data-verified calorie counts, all surfaced through a Gradio chat interface via OpenRouter.


### 5. Vector Store Service
[**🔗 View Repository**](https://github.com/zweyaungnitun/vector-store-service)

A production-ready semantic ingestion and search platform for HR analytics, enabling intelligent resume screening, job-to-skill matching, and talent discovery by converting unstructured HR documents into searchable vector embeddings across pluggable cloud and local backends.
* **Architecture:** A layered FastAPI service separates concerns across five clean tiers — API routing, ingestion orchestration, embedding computation, vector store I/O, and a drag-and-drop frontend — with a Factory pattern dynamically wiring the correct embedding provider and vector database backend at startup based on environment configuration.
* **Core Mechanics:** Domain-specific ingestors (Resume, Job, Skill, Knowledge) normalize and batch-chunk multi-format inputs (PDF, CSV, Excel, TXT) before routing through a Strategy-patterned EmbeddingProvider — Local Sentence-Transformers, OpenAI text-embedding-3, or Pinecone Inference — then persist vectors with metadata into the configured store (Chroma for local dev, Qdrant for distributed, Pinecone for serverless cloud), all served over async FastAPI endpoints with structured JSON logging throughout.

---

## 🧰 Technical Arsenal

**AI & Machine Learning Engineering**
> LangGraph | RAG Architectures | Vector Database Indexing | LLM Orchestration & Prompting

**Backend & Cloud Infrastructure**
> Python | Node.js | AWS | Google Cloud Platform | Alibaba Cloud 

**Database Systems**
> MongoDB Atlas | CockroachDB | DynamoDB

## 🏆 Certifications

- 🥇 Fundamental Information Technology Engineer (FE)
- ☁️ Oracle Generative AI Professional
- 🤖 IBM RAG & Agentic AI Professional
- 📊 Practical Machine Learning
- 🇯🇵 Japanese Language Proficiency Test (JLPT N3)
---

## 📫 Let's Connect

Whether it is discussing the future of agentic observability, cloud database scaling, or software architecture, I am always open to connecting.

[LinkedIn Profile](https://www.linkedin.com/in/zwe-yaung-ni-tun-476979211) | [Email Address](mailto:zweyaungnitun2020@gmail.com)
