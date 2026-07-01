<div align="center">

# Mounib Nasr
### AI Engineer · NLP & LLM Systems · Agentic Pipelines · Applied Research

[![Portfolio](https://img.shields.io/badge/Portfolio-mounibnasr.com-1d4ed8?style=flat&logo=firefox)](https://funny-peony-01c787.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077b5?style=flat&logo=linkedin)](https://www.linkedin.com/in/mounib-nasr-073899244/)
[![Email](https://img.shields.io/badge/Email-mounibnasr123@gmail.com-ea4335?style=flat&logo=gmail)](mailto:mounibnasr123@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=mounibnasr45&color=1d4ed8&style=flat)

</div>

---

## About

I build production AI systems — multi-agent pipelines, RAG architectures, NLP tooling, and computer vision solutions. Currently working as a Junior AI Engineer at AstroLab (Sousse, Tunisia), where I ship the full stack from LLM orchestration to containerised deployment.

My background spans generative AI, applied NLP (extraction, retrieval, multilingual processing), computer vision, and independent research on ANN indexing. I care about systems that are reliable, observable, and actually used.

-  Final-year Software Engineering student at ISIMM (Intelligent & Distributed Systems), expected Jul 2026
-  Native Arabic · French B2 · English B2
-  Open to AI/NLP engineering roles in Tunisia and remotely

---

## Tech Stack

**LLMs & GenAI**

![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat&logo=google)
![Claude](https://img.shields.io/badge/Anthropic_Claude-d97706?style=flat)
![OpenAI](https://img.shields.io/badge/OpenAI_GPT-412991?style=flat&logo=openai)
![Groq](https://img.shields.io/badge/Groq-000000?style=flat)

**Agent Frameworks**

![LangGraph](https://img.shields.io/badge/LangGraph-1d4ed8?style=flat)
![LangChain](https://img.shields.io/badge/LangChain-1c3c3c?style=flat)
![CrewAI](https://img.shields.io/badge/CrewAI-ef4444?style=flat)
![BeeAI](https://img.shields.io/badge/BeeAI-f59e0b?style=flat)
![MCP](https://img.shields.io/badge/MCP-6366f1?style=flat)

**ML & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv)

**RAG & Vector Stores**

![Qdrant](https://img.shields.io/badge/Qdrant-dc2626?style=flat)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat&logo=neo4j)
![FAISS](https://img.shields.io/badge/FAISS-412991?style=flat)
![ChromaDB](https://img.shields.io/badge/ChromaDB-10b981?style=flat)

**Backend & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**DevOps & MLOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow)
![Langfuse](https://img.shields.io/badge/Langfuse-1d4ed8?style=flat)

---

## Projects

### Agentic Systems & LLM Pipelines

| Project | Description | Stack |
|---|---|---|
| **[SkillBridge AI](https://github.com/mounibnasr45)** *(production — AstroLab)* | Multi-agent LLM pipeline (11 nodes) that ingests CVs and job descriptions, detects skill gaps, and generates personalised learning roadmaps via SSE streaming. Redis-checkpointed crash recovery. | LangGraph · Gemini · Qdrant · FastAPI · Docker |
| **[Deep Research System](https://github.com/mounibnasr45/Agentic-Deep-Research-Mechanism)** | Distributed multi-agent research platform: Planner, Expert (ReAct + MCP tool-calling), Writer communicating via A2A protocols. FastMCP server exposes tools at runtime to generate citation-grounded long-form reports. | LangGraph · BeeAI · FastMCP · Neo4j |
| **[Intelligent Medical Agent](https://github.com/mounibnasr45/medical_agentic_system)** | Enterprise clinical-decision-support system with hierarchical task delegation, ReAct reasoning, and hybrid retrieval (Neo4j graph traversal + dense search + Graphiti temporal tracking). | CrewAI · GraphRAG · Neo4j · Graphiti |
| **[Tunisian Legal AI Assistant](https://github.com/mounibnasr45/Agentic_Tn_law)** | ReAct agent over bilingual (Arabic/French) legislation with hybrid BM25 + vector retrieval. End-to-end Dockerised deployment. | LangChain · ChromaDB · BM25 · Docker |

### NLP, Language & Knowledge Systems

| Project | Description | Stack |
|---|---|---|
| **Arabic Poetry LLM Fine-tuning** | Fine-tuned AraGPT2-base on ~60K Arabic poems for conditional text generation. Full pipeline: fp16 mixed precision, gradient accumulation, Hugging Face Trainer API. | Hugging Face · PyTorch · AraGPT2 |
| **Memory-Efficient Whisper Streaming** | Real-time audio transcription with constant memory footprint (sliding buffer) and controlled latency (decoder state cache). Client-server WebSocket architecture. | Whisper · PyTorch · WebSocket |

### Recommender Systems & Semantic Search

| Project | Description | Stack |
|---|---|---|
| **[MovieLens Hybrid Recommender](https://github.com/mounibnasr45/recommender_system)** | Matrix factorization (SVD-inspired, 15 latent factors) + genre Jaccard content filtering + SentenceTransformer semantic search. RMSE 0.86 / MAE 0.66 on 90K+ ratings. Served via FastAPI + React + Docker. | PyTorch · SentenceTransformer · FastAPI · React |

### Computer Vision & ML

| Project | Description | Stack |
|---|---|---|
| **[ESRGAN Super-Resolution](https://github.com/mounibnasr45/SrGan)** | Enhanced Super-Resolution GAN with Residual Dense Blocks and fp16 mixed-precision training on DIV2K. Evaluated with PSNR and SSIM. | PyTorch · ESRGAN · DIV2K |
| **[Autonomous Wheelchair Navigation](https://github.com/mounibnasr45/Autonomous-Wheelchair)** | AI-powered navigation system combining deep learning, path planning, and intelligent control for autonomous wheelchair guidance. | PyTorch · OpenCV |
| **[RL Agent for Sepsis Detection](https://github.com/mounibnasr45/sepsis-)** | PPO reinforcement learning agent for early sepsis detection from ICU time-series data. | PyTorch · Stable-Baselines3 |

### Applied Research

| Project | Description |
|---|---|
| **ANN Indexing Manuscript** *(in preparation, 2026)* | Novel large-scale ANN index addressing limitations of FreshDiskANN / HNSW under high-rotation workloads. Theoretical contribution: complexity analysis + analytic derivation of optimal parameters, Python prototype validated on synthetic benchmarks. |

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mounibnasr45&show_icons=true&theme=tokyonight&hide_border=true" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mounibnasr45&layout=compact&theme=tokyonight&hide_border=true" height="170"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=mounibnasr45&theme=tokyonight&hide_border=true"/>
</div>

---

<div align="center">

*Building AI systems that ship, not just demos.*

</div>
