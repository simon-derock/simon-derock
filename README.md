<div align="center">

# Philip Simon Derock

### AI Engineer — Agentic AI · RAG Systems · LLM Fine-Tuning

Building production LLM systems: multi-agent orchestration, retrieval pipelines, and fine-tuned models that ship to real hardware, not just notebooks.

[![Portfolio](https://img.shields.io/badge/Portfolio-philipsimonderock.com-000?style=flat-square&logo=safari&logoColor=white)](https://philipsimonderock.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-simon--derock-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/simon-derock/)
[![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-philip11-FFD21E?style=flat-square)](https://huggingface.co/philip11)
[![Email](https://img.shields.io/badge/Email-contact%40philipsimonderock.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:contact@philipsimonderock.com)

</div>

---

### 🔭 Currently

- Open to new opportunities in Agentic AI, RAG systems, and LLM fine-tuning
- Most recently built production **Agentic RAG infrastructure for legal research** — LangGraph ReAct pipelines, Zilliz hybrid retrieval, served via a dedicated **FastMCP** server so external agents can invoke legal intelligence as native tools
- Exploring efficient fine-tuning (QLoRA/DoRA) for low-resource-language, low-cost hardware deployment
- Always shipping something async, agentic, and slightly over-engineered on purpose

---

### 🧠 Featured Work

**[xphil — Governed Clinical-Reasoning AI](https://huggingface.co/philip11/xphil-gemma-4-E4B)**
Fine-tuned Gemma 4 E4B via QDoRA (QLoRA + DoRA) on 37,892 truth-grounded clinical samples across 11 real-patient dataset families. A 3-layer data pipeline (raw truth → deterministic structured extraction → grounded generation) keeps the teacher model from inventing clinical claims. Quantized to GGUF for fully offline inference on an ₹8,000 Android phone. Built for the Kaggle × Google DeepMind Gemma hackathon, with native Tamil/Tanglish support and calibrated confidence outputs.
`Gemma 4 E4B` `QLoRA/DoRA` `Unsloth` `GGUF` `llama.cpp` `Ollama`

**[DEX JOBS — Autonomous Job Discovery Agent](https://github.com/simon-derock/dex-jobs)**
A framework-free async ReAct engine — no LangChain, LangGraph, or CrewAI — built to avoid abstraction overhead. 7 specialized agents (Orchestrator, Scout, Analyst, Writer, Reporter, Oracle, Optimizer) share 20 tools, backed by a 3-tier memory system (Qdrant semantic + Supabase structured + sliding-window context). Multi-provider LLM routing with automatic failover across Cerebras, Mistral, and Cloudflare Workers AI keeps it running when any single provider degrades. Delivered end-to-end via Telegram.
`Python` `Qdrant` `Jina Embeddings v3` `Supabase` `Asyncio`

**[Multi-Agent RAG Chatbot](https://github.com/simon-derock/Agentic-RAG-Chatbot)**
A decoupled multi-agent RAG system coordinated through a custom async message bus, ingesting PDF/PPTX/CSV/DOCX/MD/TXT into ChromaDB for retrieval. Live on Hugging Face Spaces.
`Python` `ChromaDB` `Sentence-Transformers` `Gemini API` `Streamlit`

**[Advanced GenAI Server](https://github.com/simon-derock/ADVANCED_GENERATIVE_AI_SERVER_FOR_EFFICIENT_AI_DEPLOYMENT)**
Repurposed an idle laptop into a wireless, headless Ubuntu AI server — end-to-end RAG with LangChain, Ollama, Nomic embeddings, and MySQL-backed conversational memory, deployed via Streamlit.
`Python` `Ollama` `LangChain` `MySQL`

<details>
<summary><b>More builds</b></summary>
<br>

- **[Business Document Processing Workflow](https://github.com/simon-derock/Business-Document-Processing-Workflow-with-n8n)** — n8n automation pipeline routing PDFs through 7 specialized Mistral agents for structured document analysis, output to Google Docs
- **[Email Classification API](https://github.com/simon-derock/email-class)** — Naive Bayes classifier served as a FastAPI REST service on Hugging Face Spaces
- **[Computer Vision Player Tracker](https://github.com/simon-derock/football-player-tracker)** — Real-time YOLOv5 multi-object tracking with Kalman filtering and Hungarian optimization for occlusion-resistant re-identification
- **[Portable Server](https://github.com/simon-derock/Portable-Server)** — Dual-boot Linux server built from a repurposed laptop for wireless, always-on hosting

</details>

---

### 🧰 Stack

**LLM & Agentic AI**
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square)
![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square)
![OpenAI](https://img.shields.io/badge/-OpenAI%20SDK-412991?style=flat-square&logo=openai&logoColor=white)

**Retrieval & Vector Search**
![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square)
![ChromaDB](https://img.shields.io/badge/-ChromaDB-121212?style=flat-square)
![Milvus](https://img.shields.io/badge/-Milvus%2FZilliz-00A1EA?style=flat-square)
![Pinecone](https://img.shields.io/badge/-Pinecone-000000?style=flat-square)

**Core**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Google Cloud](https://img.shields.io/badge/-Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=simon-derock&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=simon-derock&layout=compact&hide_border=true)

</div>

<div align="center">

**contact@philipsimonderock.com** · [philipsimonderock.com](https://philipsimonderock.com)

</div>
