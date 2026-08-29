<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=140&color=0:0d1117,100:161b22&section=header" width="100%" alt="" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=38&duration=1&pause=999999&color=F8FAFC&center=true&vCenter=true&width=500&lines=Karthik+Jayan" width="500" height="60" alt="Karthik Jayan" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=13&duration=3000&pause=1600&color=e8384f&center=true&vCenter=true&width=680&lines=In-database+hybrid+retrieval+%E2%80%94+no+dedicated+vector+store.;LangGraph+state+machines+with+%3C5ms+semantic+caching.;TFLite+LSTM+%40+2.42ms+inference+on+ESP32+edge+hardware.;I+like+building+things+that+keep+running." width="680" height="46" alt="Tagline" />

<br><br>

<a href="https://karthikjayan.dev/"><img src="https://img.shields.io/badge/karthikjayan.dev-21262d?style=flat-square&logoColor=white" alt="Portfolio" /></a>&nbsp;
<a href="https://www.linkedin.com/in/karthik-jayan-8544ba267/"><img src="https://img.shields.io/badge/LinkedIn-21262d?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
<a href="https://github.com/KARTHIKKJ369"><img src="https://img.shields.io/badge/GitHub-21262d?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>&nbsp;
<a href="mailto:karthikjayan369@gmail.com"><img src="https://img.shields.io/badge/Email-21262d?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=60&color=0:161b22,100:0d1117&section=footer&reversal=true" width="100%" alt="" />

</div>

<br>

```bash
$ whoami

Name        ::  Karthik Jayan
Role        ::  AI Systems Engineer
Focus       ::  Corrective RAG · Multi-Agent Orchestration · Edge IoT
Research    ::  CyberLabs — Advanced Cryptology & Quantum-Safe Comm Lab, IIIT Kottayam
Education   ::  B.Tech CSE, MACE Kothamangalam · CGPA 9.14 · Class of 2027
Homelab     ::  Mac Mini M4 · Ollama · Docker · Tailscale · Caddy
Status      ::  Open to backend and AI systems engineering roles.
```

Final-year CS undergrad and summer research intern at CyberLabs, IIIT Kottayam. I build production-grade AI systems — corrective RAG pipelines, multi-agent orchestration platforms, real-time edge IoT backends. My flagship is Ridge, a multi-tenant CRAG system that runs entirely on PostgreSQL 16 without a dedicated vector store. I like software that keeps running after the demo ends.

<br>

---

```text
Ridge                     ██████████  100%   PostgreSQL 16 + pgvector + SQL RRF + LangGraph
Multi-Agent DAG Platform  █████████░   90%   Topological DAG + 3-Tier Memory + OTEL
Edge Collision Avoidance  █████████░   90%   ESP32 + LoRa + TFLite LSTM @ 2.42ms
TinyLM                    ████░░░░░░   40%   Decoder-only SLM trained from scratch in PyTorch
```

<br>

---

### ▌ Ridge &nbsp;·&nbsp; [Multi-Tenant Corrective RAG](https://github.com/KARTHIKKJ369/Ridge)

<sub>Live · <a href="https://ridge.karthikjayan.tech">ridge.karthikjayan.tech</a></sub>

Multi-tenant CRAG system of record built entirely on **PostgreSQL 16 + pgvector** — no dedicated vector database. Dense 1024-dim BGE-Large vectors (HNSW) fuse with native GIN full-text search via **in-database SQL Reciprocal Rank Fusion** (K=60), hitting 75–90ms hybrid retrieval. The ingestion layer parses documents into a normalized `DocumentAST → PageAST → BlockAST` hierarchy with layout-aware PDF reconstruction and RapidOCR ONNX fallback. The LangGraph state machine adds `<5ms` semantic vector caching, dynamic intent routing across 5 archetypes, FlashRank cross-encoder reranking, cross-document contradiction detection, and hallucination verification streamed over SSE at 400+ tok/s on Groq LPU.

```text
[ Multi-Format Ingestion ]
          │
[ AST Parser + SimHash Dedup ] ──► [ pgvector HNSW ] ──┐
                                                         ├─► [ SQL RRF  K=60 ] ─► [ FlashRank ]
                               ──► [ GIN Full-Text  ] ──┘
                                                                     │
         [ SSE Stream ] ◄── [ Hallucination Auditor ] ◄── [ Groq LPU / Gemini ]
```

`PostgreSQL 16` `pgvector` `LangGraph` `FastAPI` `Groq LPU` `Gemini` `FlashRank` `React 19` `Docker`

---

### ▌ Multi-Agent DAG Platform &nbsp;·&nbsp; [Autonomous Task Orchestration](https://github.com/KARTHIKKJ369/multi-agent-system)

Decomposes ambiguous goals into dependency-aware Directed Acyclic Graphs, dispatching up to 5× concurrent subtasks across 10+ specialized agents. Memory is a deliberate three-tier split: **Redis 7** for session state and distributed locks (`<2ms`), **PostgreSQL 16** for durable execution graphs and audit traces, **Qdrant v1.7** for cross-session semantic retrieval (`<45ms`). Full observability via Prometheus, OpenTelemetry, and LangSmith — visualized in a real-time Next.js 16 dark-mode DAG dashboard.

`Python 3.11` `FastAPI` `LangChain` `Next.js 16` `Redis 7` `PostgreSQL 16` `Qdrant` `OTEL` `Docker Compose`

---

### ▌ Backwater Collision Avoidance &nbsp;·&nbsp; [Edge AI + Sub-GHz IoT](https://github.com/KARTHIKKJ369/backwater_collision_avoidance)

ESP32 nodes fuse 6-DOF IMU, GPS, and obstacle camera feeds over encrypted **SX1278 Sub-GHz LoRa** — zero cloud dependency. A quantized 11-channel **TFLite LSTM** runs at **2.42ms inference latency** on edge hardware, forecasting 15-second trajectories with a **50.9s mean Time-to-Collision lead time** and 100% collision recall across head-on, crossing, and sudden-stop scenarios. COLREGS-standard maneuvers dispatch over MQTT to a React + Leaflet GIS operator dashboard.

`ESP32` `LoRa SX1278` `TFLite` `PyTorch` `FastAPI` `Mosquitto MQTT` `React 19` `Leaflet` `Docker`

---

### ▌ Recall &nbsp;·&nbsp; [Biological Long-Term Memory for LLMs](https://github.com/KARTHIKKJ369)

<sub>Published · JETIR — Journal of Emerging Technologies and Innovative Research</sub>

Memory layer modeled on the Ebbinghaus forgetting curve: each node decays exponentially, retrieval triggers spaced-repetition reinforcement, stale nodes prune automatically. Hybrid retrieval fuses dense sentence embeddings with BM25 keyword scoring. Write-time cosine deduplication (≥0.92) prevents store inflation. Three-agent pipeline eliminates double-counting across sessions.

`Python` `Flask` `Sentence-Transformers` `BM25` `SSE` `Chart.js`

<br>

---

**Research Intern — CyberLabs, IIIT Kottayam** &nbsp;`2026 – Present`  
Advanced Cryptology & Quantum-Safe Communications Lab · AES-128 / post-quantum primitives · Sub-GHz LoRa mesh networking · edge collision-avoidance algorithms

**Lead Author** — *Project Recall: Cognitive Long-Term Vector Memory for Multi-Agent LLMs* · JETIR

<br>

---

```text
Homelab  ·  Apple Mac Mini M4  ·  24/7

  Tailscale Mesh (WireGuard zero-trust)
       │
  Caddy (auto-TLS)
       ├── FastAPI microservices
       ├── Next.js frontends
       └── Ollama  (local inference)

  Docker Compose
       ├── PostgreSQL 16 + pgvector
       ├── Redis 7
       └── Qdrant v1.7

If it requires the public internet to function, I probably don't trust it yet.
```

<br>

---

**Languages** &nbsp;
![Python](https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend** &nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**AI / ML** &nbsp;
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)

**Databases** &nbsp;
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-4B5563?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**DevOps** &nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)

**Edge & Mobile** &nbsp;
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![LoRa](https://img.shields.io/badge/LoRa%20SX1278-2E7D32?style=flat-square)
![TFLite](https://img.shields.io/badge/TFLite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Currently learning** &nbsp;`Rust` · `eBPF` · `Post-Quantum Cryptography` · `Distributed Systems` · `TinyLM from scratch`

<br>

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=KARTHIKKJ369&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&title_color=e8384f&icon_color=e8384f&text_color=6b7280&bg_color=0d1117" height="155" alt="GitHub Stats" />&nbsp;&nbsp;<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KARTHIKKJ369&layout=compact&theme=tokyonight&hide_border=true&title_color=e8384f&text_color=6b7280&bg_color=0d1117&langs_count=6" height="155" alt="Top Languages" />

<br><br>

<img src="https://streak-stats.demolab.com?user=KARTHIKKJ369&theme=tokyonight&hide_border=true&stroke=e8384f&ring=e8384f&fire=e8384f&currStreakLabel=e8384f&background=0d1117" height="155" alt="Streak Stats" />

</div>

<br>

---

<div align="center">

[karthikjayan.dev](https://karthikjayan.dev) &nbsp;·&nbsp; [karthikjayan369@gmail.com](mailto:karthikjayan369@gmail.com)

<br>

*Build systems that continue running when assumptions fail.*

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:0d1117,100:161b22&section=footer" width="100%" alt="" />

</div>
