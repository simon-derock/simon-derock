<div align="center">

<img src="./a.jpg" alt="A stylized mountain landscape beneath a full moon" width="100%" height="160" style="display:block; width:100%; height:160px; object-fit:cover; object-position:center top;" />

# Philip Simon Derock

### AI Engineer · Agentic Systems · GraphRAG · LLM Engineering

I build AI systems that move from evidence to decisions: governed agents,
retrieval systems, graph intelligence, fine-tuned models, and APIs that are
tested, observable, and deployable.

[![Portfolio](https://img.shields.io/badge/Portfolio-philipsimonderock.com-000?style=flat-square&logo=safari&logoColor=white)](https://philipsimonderock.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-simon--derock-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/simon-derock/)
[![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-philip11-FFD21E?style=flat-square)](https://huggingface.co/philip11)
[![Email](https://img.shields.io/badge/Email-contact%40philipsimonderock.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:contact@philipsimonderock.com)
[![Resume](https://img.shields.io/badge/Resume-view%20PDF-111827?style=flat-square&logo=adobeacrobatreader&logoColor=white)](https://philipsimonderock.com/resume.pdf)

</div>

---

## What I build

My work sits at the intersection of applied AI and dependable software
engineering. I care about the hard parts that make systems useful in the real
world: provenance, retrieval quality, deterministic validation, stateful
orchestration, failure recovery, privacy boundaries, and deployment on
constrained hardware.

## Current focus

- Open to AI Engineer opportunities spanning Agentic AI, GraphRAG, retrieval
  systems, LLM platforms, and efficient model deployment.
- Building production Agentic RAG infrastructure for legal research with
  LangGraph ReAct workflows, Zilliz hybrid retrieval, and a dedicated FastMCP
  server that exposes legal intelligence as native tools.
- Exploring QLoRA/DoRA fine-tuning and low-cost inference for capable models on
  constrained hardware.

## Featured systems

### [Lunarbit — Evidence-Verifiable Commerce GraphRAG](https://github.com/simon-derock/Lunarbit)

Reconstructing six years of food commerce into an auditable personal economic-
intelligence graph. Lunarbit turns invoices, order histories, and email orders
into a temporal Neo4j knowledge graph, then answers financial questions with
hybrid retrieval and citation-level evidence.

- **454 reconstructed orders · 53k+ graph nodes · 85k+ relationships**
- Neo4j GraphRAG with exact matching, Lucene/BM25, HNSW vector search, RRF,
  Cohere embeddings/reranking, and bounded graph traversal
- LangGraph stateful workflows with durable conversation checkpoints, guarded
  tool use, deterministic Decimal-safe reconciliation, and privacy-safe public
  projections
- FastAPI contracts, streaming answers, source provenance, typed validation,
  container smoke tests, CodeQL, and CI-enforced test-driven development

Lunarbit is designed to answer questions such as: *Which restaurants account
for the most orders? How has a dish price changed over time? How much did fees,
discounts, and membership economics change my actual spend?* Every answer is
constrained by the graph and its evidence rather than generated from plausible
text.

### [Xphil — Governed Multimodal Edge Model](https://huggingface.co/philip11/xphil-gemma-4-E4B)

A 4.5B multimodal model fine-tuned with QDoRA on **37k+ grounded training
samples** across 11 real-patient dataset families. The pipeline separates raw
truth, deterministic structure, and grounded generation to reduce unsupported
clinical claims. Quantized GGUF artifacts run fully offline through
`llama.cpp`/Ollama on low-cost hardware, with Tamil/Tanglish support and
calibrated confidence outputs.

### [TITAN — Self-Correcting AI Resume Compiler](https://github.com/simon-derock/Titan-resume)

An evidence-grounded document compiler for truthful, tailored, exactly
one-page resumes. TITAN converts a job description and verified career
evidence into typed JSON, renders a locked LaTeX template, compiles a PDF with
Tectonic, and validates the artifact recruiters and ATS systems actually see.

- Provenance attached to claims, projects, skills, and experience
- Template-aware space planning, ATS reading-order checks, hyperlink checks,
  geometry measurement, and page-utilization gates
- Bounded, element-level repair loops instead of unconstrained regeneration
- Three reviewed A4 templates, deterministic validators, provider fallback,
  and a test-first Python architecture ready for LangGraph/HITL expansion

### [DEX Jobs — Autonomous Job Discovery Agent](https://github.com/simon-derock/dex-jobs)

A framework-independent asynchronous ReAct system for end-to-end job
discovery. Seven specialized agents coordinate twenty tools through a custom
runtime, with multi-provider routing, automatic failover, Qdrant semantic
memory, Supabase structured memory, and Telegram delivery.

## Additional engineering work

- [Multi-Agent RAG Chatbot](https://github.com/simon-derock/Agentic-RAG-Chatbot) —
  async message-bus orchestration over heterogeneous document ingestion and
  retrieval.
- [Business Document Processing Workflow](https://github.com/simon-derock/Business-Document-Processing-Workflow-with-n8n) —
  specialized-agent document automation with structured outputs.
- [Computer Vision Player Tracker](https://github.com/simon-derock/football-player-tracker) —
  YOLOv5 tracking with Kalman filtering and Hungarian assignment for robust
  re-identification under occlusion.
- [Advanced GenAI Server](https://github.com/simon-derock/ADVANCED_GENERATIVE_AI_SERVER_FOR_EFFICIENT_AI_DEPLOYMENT) —
  a headless Ubuntu AI server with Ollama, LangChain, Nomic embeddings, and
  MySQL-backed conversational memory.
- [Portable Server](https://github.com/simon-derock/Portable-Server) —
  dual-boot Linux infrastructure built from a repurposed laptop for wireless,
  always-on hosting.

## Technical focus

`Python` · `LangGraph` · `GraphRAG` · `Neo4j` · `FastAPI` · `FastMCP` ·
`Cohere` · `BM25` · `HNSW` · `RRF` · `Qdrant` · `Zilliz/Milvus` · `PyTorch` ·
`QLoRA/DoRA` · `GGUF` · `llama.cpp` · `Docker` · `CI/CD` · `TDD`

## Engineering principles

- **LLMs propose; deterministic systems decide.** Money, graph truth,
  provenance, privacy, and release gates are code-owned.
- **Evidence before eloquence.** Unsupported claims are rejected or surfaced
  for review.
- **Production behavior starts with tests.** Contracts, integration paths,
  failure modes, and security boundaries are continuously exercised.
- **Design for failure.** Provider fallback, bounded retries, checkpointing,
  sanitized errors, and explicit abstention are first-class behavior.

<div align="center">

**Building systems that can explain where an answer came from—and still work
when the model, network, or input is imperfect.**

**[Download my resume](https://philipsimonderock.com/resume.pdf)** ·
**[Explore my portfolio](https://philipsimonderock.com)**

contact@philipsimonderock.com

</div>
