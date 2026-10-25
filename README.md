<h1 align="center">Hi there, I'm Sandesh Awate</h1>

<h3 align="center">AI & ML Engineer | Building LLM-powered systems that ship</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/sandesh-awate-206478291/"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://x.com/Sandesh59830"><img src="https://img.shields.io/badge/X-181717?style=for-the-badge&logo=X&logoColor=black"/></a>
  <a href="https://leetcode.com/u/Sandeshawate6055/?utm=codolio"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
  <a href="https://codolio.com/profile/sandeshawate6055"><img src="https://img.shields.io/badge/Codolio-6C63FF?style=for-the-badge"/></a>
  <a href="https://huggingface.co/sandeshawate6055"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/></a>
  <a href="mailto:sandeshawate106@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

### About Me

B.Tech in Artificial Intelligence & Data Science at Vishwakarma Institute of Information Technology, Pune (CGPA: 8.55, Class of 2027). Passionate about building production-grade AI systems using LLMs, RAG, multimodal retrieval, and scalable backend architectures. I enjoy solving real-world engineering challenges by designing high-efficiency AI pipelines and optimizing hardware throughput rather than just training models.

---

### Tech Stack

**Languages**
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
</p>

**AI, LLMs & Retrieval**
<p align="left">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/LoRA%20%2F%20PEFT-FF4088?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/FAISS-005571?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/RAG%20%26%20Hybrid%20Search-FF6F00?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LangChain%20%2F%20LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/CLIP%20%26%20BGE-7928CA?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
</p>

**Backend, Data & Infra**
<p align="left">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>

---

### Featured Projects

**[Intelligent Multimodal E-Commerce Search Engine](https://github.com/SandeshAwate6055/E-Commerce-Search-Engine-Optimization-)** — `Python · PyTorch · LoRA (Qwen2.5) · BGE-Large · CLIP (ViT-B/32) · FAISS · FastAPI · React`
Production-grade Two-Stage Multimodal Search Engine combining Dense Semantic Recall (`BAAI/bge-large-en-v1.5` + FAISS) with In-Memory Cross-Modal Visual Reranking (`CLIP ViT-B/32`). Fine-tuned `Qwen2.5-0.5B` using LoRA ($r=8, \alpha=16$) on 8,500+ triplets (val loss 3.13 → 0.62) for real-time structured entity extraction. Optimized to run 100% on a consumer 4 GB GPU (2.75 GB VRAM footprint with zero CPU spill), slashing latency from ~35s to ~1.1s (97% reduction) and cutting reranking latency from 1,500ms to <5ms (>300× speedup).

**[Concise.AI](https://github.com/SandeshAwate6055)** — `Python · FastAPI · Celery · Redis · PostgreSQL · faster-whisper · OpenAI · FFmpeg`
End-to-end AI pipeline that turns long-form YouTube videos into short-form Reels/Shorts content. Transcribes with word-level timestamps, uses OpenAI structured outputs to pick the most information-dense clip, and runs a 7-stage async pipeline (download, transcribe, clip selection, vertical render, caption burn-in) orchestrated with Celery + Redis.

**[College Admin & Collaboration Copilot](https://github.com/SandeshAwate6055)** — `FastAPI · FAISS · PostgreSQL · LLaMA 3.1 · Groq`
Multi-agent RAG system with an LLM-powered intent router that triages queries across document Q&A, project matching, and ticketing. Built a custom eval harness to measure router accuracy and retrieval quality, then patched hallucination and context-limit failure modes with retrieval guardrails. Ingests 1,000+ records via FAISS with sub-15ms retrieval latency and exact PDF citations.

**[VaaniAI](https://github.com/SandeshAwate6055)** — `Python · FastAPI · MediaPipe · Gemini · Deepgram · NLP`
Real-time AI presentation coach analyzing verbal and non-verbal delivery cues with sub-500ms feedback latency. Combines MediaPipe gesture tracking, Deepgram speech-to-text, and Gemini for sentiment analysis, achieving 90% feedback relevance across 150+ practice sessions.

---

### Positions of Responsibility

- **Perplexity Campus Partner**, VIIT Pune (2025) — led a 50+ student workshop on prompt engineering and AI-assisted workflows
- **AIDS Department Head**, CEC (2025) — organized expert seminars across technical and competitive-exam domains
- **Active Member**, AISA (2024) — helped organize Viz-Thon hackathon and the Data Science Symposium

---

<p align="center">
  <a href="https://www.linkedin.com/in/sandesh-awate-206478291/">LinkedIn</a> ·
  <a href="https://github.com/SandeshAwate6055">GitHub</a> ·
  <a href="https://x.com/Sandesh59830">X (Twitter)</a> ·
  <a href="https://leetcode.com/u/Sandeshawate6055/?utm=codolio">LeetCode</a> ·
  <a href="https://codolio.com/profile/sandeshawate6055">Codolio</a> ·
  <a href="https://huggingface.co/sandeshawate6055">Hugging Face</a> ·
  <a href="mailto:sandeshawate106@gmail.com">Email</a>
</p>
