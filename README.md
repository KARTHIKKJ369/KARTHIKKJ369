<div align="center">

<img
  src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:020617,50:1e293b,100:2563eb&section=header&text=Karthik%20Jayan&fontSize=54&fontColor=e2e8f0&animation=fadeIn&fontAlignY=38&desc=Building%20Reliable%20AI%20Systems%20from%20the%20Edge%20to%20the%20Cloud&descAlignY=60&descSize=18&descColor=94a3b8"
  width="100%"
/>

<a href="https://github.com/KARTHIKKJ369">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1200&color=64748B&center=true&vCenter=true&width=560&lines=I+enjoy+building+systems+that+keep+working;when+the+internet+doesn%27t.;Cryptography+%C2%B7+LLM+Infra+%C2%B7+Embedded+%C2%B7+Self-hosting" alt="Typing SVG" />
</a>

<br><br>

<a href="https://portfolio-one-lemon-97.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0a0a0b?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/karthik-jayan-8544ba267/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:karthikjayan369@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>

<br>

## whoami

```bash
$ whoami

Name        :: Karthik Jayan
Role        :: Backend / AI Systems Engineer
Focus       :: RAG pipelines, multi-agent orchestration, IoT backends
Research    :: Quantum-Safe Communication (CyberLabs, IIIT Kottayam)
Education   :: B.Tech CSE, MACE Kothamangalam · CGPA 9.14/10 · 2027
OS          :: macOS + Linux
Editor      :: Neovim / VS Code
Status      :: Building. Open to Backend/AI Engineering roles.
```

Final-year CS undergrad, currently a **Summer Research Intern at CyberLabs' Advanced Cryptology & Quantum-Safe Communication Lab, IIIT Kottayam**. I build production-style AI systems — corrective RAG pipelines, multi-agent orchestration platforms, real-time IoT backends — and run a Mac Mini M4 homelab for self-hosting open models.

I like software that keeps running after the demo ends.

<br>

## Currently shipping

```text
Maritime Collision Avoidance   █████████░  90%   ESP32/LoRa telemetry + LSTM risk engine
Multi-Agent LLM Platform       ████████░░  80%   supervisor-led orchestration, 3-tier memory
LCRAG                          ███████░░░  70%   local-first corrective RAG pipeline
```

<br>

## Featured builds

**Maritime Collision-Avoidance Platform** — end-to-end system built at CyberLabs on ESP32/LoRa telemetry and MQTT, with a FastAPI backend and a real-time React/Leaflet dashboard. An LSTM-based trajectory predictor and configurable risk engine, validated across head-on, crossing, and sudden-stop scenarios, plus MQTT-driven cooperative maneuver recommendations and an automated scenario-evaluation pipeline for reproducible safety testing.
`ESP32` `LoRa` `MQTT` `FastAPI` `React` `Leaflet` `LSTM`
→ [github.com/KARTHIKKJ369](https://github.com/KARTHIKKJ369)

**Multi-Agent LLM Platform** — a supervisor-led orchestration system that plans a dependency task graph and dispatches specialized agents concurrently. Three-tier memory model — Redis for conversation/execution state, Qdrant for semantic memory, PostgreSQL for durable persistence — deployed via a health-checked Docker Compose stack with optional LangSmith/OTEL/Prometheus telemetry.
`FastAPI` `LangChain` `Redis` `PostgreSQL` `Qdrant` `Docker`
→ [github.com/KARTHIKKJ369](https://github.com/KARTHIKKJ369)

**LCRAG** — Local-First Corrective RAG Pipeline. A LangGraph-orchestrated retrieval loop that grades document relevance via a lightweight LLM, rewrites weak queries, and retries until sufficient evidence is found. Modular ingestion (web, PDF, markdown, text) with MMR retrieval over a persistent ChromaDB store, running 100% locally through Ollama.
`Python` `LangGraph` `ChromaDB` `Ollama` `Sentence Transformers`
→ [github.com/KARTHIKKJ369](https://github.com/KARTHIKKJ369)

**Recall** — vector-based long-term memory for multi-agent LLMs. A three-agent customer-support pipeline (Intake, Knowledge, Response) backed by a segmented memory bank with hybrid dense/BM25 retrieval fused via min-max normalization, an Ebbinghaus forgetting-curve decay model, and cosine-similarity deduplication (>0.92) at write time.
`Python` `Flask` `BM25` `Hybrid Retrieval` `REST APIs`
→ [github.com/KARTHIKKJ369](https://github.com/KARTHIKKJ369)

**Self-Hosted WebRTC** — a private video-calling stack over a personal Tailscale tunnel, no third-party signaling servers.
`WebRTC` `Node.js` `Android` `Tailscale`
→ [github.com/KARTHIKKJ369](https://github.com/KARTHIKKJ369)

**Offline UPI** — routes payments over UPI 123PAY via IVR, working with zero internet connectivity.
`Kotlin` `Jetpack Compose` `Telephony`
→ [github.com/KARTHIKKJ369](https://github.com/KARTHIKKJ369)

<br>

## Homelab

```text
Internet
   │
Tailscale
   │
Mac Mini M4
   ├── Ollama    (local inference)
   ├── Docker    (services)
   ├── Caddy     (reverse proxy / TLS)
   └── SSH       (managed from anywhere)
```

Everything above runs 24/7 on a single Mac Mini M4, reachable only over Tailscale. If it needs the public internet to function, I probably don't trust it yet.

<br>

## Stack

**Languages** &nbsp; ![Python](https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

**Backend** &nbsp; ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

**AI / ML** &nbsp; ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![Corrective RAG](https://img.shields.io/badge/Corrective_RAG-4B5563?style=flat-square) ![LSTM](https://img.shields.io/badge/LSTM-4B5563?style=flat-square)

**Databases** &nbsp; ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-4B5563?style=flat-square) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**DevOps & Infra** &nbsp; ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white) ![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)

**Mobile & Embedded** &nbsp; ![Kotlin](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![LoRa](https://img.shields.io/badge/LoRa-2E7D32?style=flat-square)

<br>

## Currently learning

`Rust` · `eBPF` · `Distributed Systems` · `Post-Quantum Cryptography` · `AI Memory Architectures`

<br>

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KARTHIKKJ369&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="github-stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KARTHIKKJ369&layout=compact&theme=tokyonight&hide_border=true" alt="top-langs" height="165"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=KARTHIKKJ369&theme=tokyonight&hide_border=true" alt="streak-stats" height="165"/>
</p>

<details>
<summary><b>Contribution snake</b> (setup required — see note below)</summary>
<br>

```md
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KARTHIKKJ369/KARTHIKKJ369/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KARTHIKKJ369/KARTHIKKJ369/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/KARTHIKKJ369/KARTHIKKJ369/output/github-contribution-grid-snake.svg" />
</picture>
```

This needs the [`Platane/snk`](https://github.com/Platane/snk) GitHub Action running on a schedule in this repo to generate the SVG. Add a workflow at `.github/workflows/snake.yml` — once it runs once, the image above will render. Drop the block above back into the README once it's live.

</details>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=KARTHIKKJ369&theme=tokyonight&no-frame=true&margin-w=15&row=1" alt="trophies"/>
</p>

<br>

## Fun facts

- I self-host almost everything I can justify self-hosting.
- Local inference on a Mac Mini is more satisfying than it has any right to be.
- Debugging distributed systems at 1am is a personality trait at this point.
- Good documentation is a feature, not a chore.
- 90% of "it's broken" turns out to be an SSH config issue.

<br>

## Contact

<p align="center">
  <a href="https://portfolio-one-lemon-97.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-0a0a0b?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/karthik-jayan-8544ba267/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/KARTHIKKJ369">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:karthikjayan369@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<br>

<div align="center">

*"Build systems that continue working when assumptions fail."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:0f172a&height=100&section=footer" width="100%"/>

</div>
