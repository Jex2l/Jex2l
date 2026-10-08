<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:05080F,50:0B3D3A,100:00E5CC&height=240&section=header&text=JEEL%20PATEL&fontSize=72&fontColor=FFFFFF&fontAlignY=42&desc=Systems%20%E2%80%A2%20Infrastructure%20%E2%80%A2%20Agentic%20AI&descAlignY=64&descSize=20&animation=twinkling" width="100%" alt="Jeel Patel"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=700&color=00E5CC&center=true&vCenter=true&width=760&lines=%24+whoami+%E2%86%92+Jeel+Patel;MS+Computer+Engineering+%40+NYU+Tandon;120-node+GPU+cluster+%E2%86%92+4M%2B+events%2Fday;SRE+%C2%B7+HPC+%C2%B7+Low-latency+C%2B%2B+%C2%B7+Agentic+AI;Building+agents+that+triage+incidents+at+3AM;Open+to+full-time+SWE+roles+%F0%9F%9A%80" alt="Typing"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jeel3105-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeel3105/)
[![Portfolio](https://img.shields.io/badge/Portfolio-jeelpatel.net-00E5CC?style=for-the-badge&logo=vercel&logoColor=black)](https://jeelpatel.net)
[![Email](https://img.shields.io/badge/Email-pateljeel3105-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pateljeel3105@gmail.com)
[![IEEE](https://img.shields.io/badge/IEEE-Published-00629B?style=for-the-badge&logo=ieee&logoColor=white)](https://ieeexplore.ieee.org/document/10526152)

![Status](https://img.shields.io/badge/STATUS-OPEN_TO_WORK-22C55E?style=flat-square&labelColor=0D1117)
![Location](https://img.shields.io/badge/BASE-NYC_%C2%B7_open_to_relocate-00E5CC?style=flat-square&labelColor=0D1117)
![Visitors](https://komarev.com/ghpvc/?username=Jex2l&label=VISITORS&color=00E5CC&style=flat-square&labelColor=0D1117)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00E5CC,100:0D1117&height=2&section=header" width="100%" alt=""/>

## `> boot --profile`

```ts
const jeel = {
  education : "MS Computer Engineering, NYU Tandon (2026)",
  focus     : ["Distributed systems", "HPC infrastructure", "SRE / observability", "Agentic AI"],
  experience: ["NYU HPC Research Lab (Research Lead)", "The NorthStar Group (SRE/Backend)", "5POINT Solutions (Low-latency C++)"],
  philosophy: "Measure it. Automate it. Make it boringly reliable.",
  shipping  : "Systems that survive contact with production",
  status    : "Open to full-time software engineering roles",
} as const;
```

<div align="center">

| 🖥️ **120** | 📡 **4M+** | 👥 **100K+** | 📄 **1** |
|:---:|:---:|:---:|:---:|
| GPU nodes managed | telemetry events / day modeled | MAU platform kept reliable | IEEE publication |

</div>

## `> ls ./flagship-projects`

### 🛰️ Incident Triage Agent &nbsp;·&nbsp; `in active development`
> An on-call agent that reads alerts, investigates, and proposes fixes. A human approves before anything runs.

```mermaid
flowchart LR
    A[Prometheus / Alertmanager] --> B{Triage Agent}
    B -->|MCP tools| C[Metrics · Logs · K8s state]
    B --> D[Root-cause hypothesis]
    D --> E[/Human approval gate/]
    E --> F[Remediation]
    G[Fault-injection evals] -.scores.-> B
```

- **Human-in-the-loop by design:** no action executes without approval
- **Evaluated, not vibes-checked:** fault-injection harness scores the agent's diagnoses
- **Fully local and free:** Ollama + kind + open-source tooling
- `Python` `MCP` `Prometheus` `Alertmanager` `Kubernetes` `Ollama`

<br/>

### 🧬 TR4: Generative Telemetry Pipeline &nbsp;·&nbsp; `NYU HPC Research`
> Two-stage generative model (CVAE + GRU) that learns the behavior of HPC job telemetry at **4M+ events/day**.

- Trained on the **MIT Supercloud** dataset on **NYU Greene**, with infrastructure debugging along the way (NFS stalls, cuDNN faults, scaler corruption)
- Weekly reporting cadence with advisor **Prof. Yuzhang Lin**
- `PyTorch` `CUDA` `CVAE` `GRU` `Slurm` `Jupyter`

<br/>

### 🧾 Invoice Extractor E2E &nbsp;·&nbsp; `Vision-Language IE`
> LayoutLMv3 + OCR heuristics → structured data → Google Sheets / Excel, behind a FastAPI service with a Next.js UI.

- `LayoutLMv3` `FastAPI` `Next.js` `Docker` `OCR`

<br/>

<div align="center">

| 🩺 **Medical RAG Chatbot** | 🅿️ **Smart Parking IoT** | 📹 **Short-Video Recommender** |
|:---|:---|:---|
| PDF ingest → embeddings → **Pinecone** → grounded medical Q&A with sharply reduced hallucination. | Arduino UNO R4 WiFi + ultrasonic sensors → live occupancy portal, **<500ms** hardware-to-browser. | CountVectorizer + cosine similarity recs on Flask + Firebase + React, deployed to real users. |
| `RAG` `Pinecone` `LLM` | `Arduino` `WebSockets` | `Flask` `React` `NLP` |

| 🎮 **VRAMWatch** | 🚕 **NYC Taxi Demand Forecast** | 🔎 **OCR Extraction Pipeline** |
|:---|:---|:---|
| GPU/VRAM monitoring tool with LLM-powered insights via the Anthropic SDK. | LangGraph-orchestrated forecasting pipeline over NYC taxi data. | OpenCV + Tesseract pipeline orchestrated with the OpenAI Agents SDK. |
| `Python` `Anthropic SDK` | `LangGraph` `Forecasting` | `OpenCV` `Tesseract` |

</div>

> 🔗 More on [github.com/Jex2l](https://github.com/Jex2l)

## `> cat ./stack.json`

<div align="center">

**Systems & Languages**<br/>
[![C++](https://skillicons.dev/icons?i=cpp)](#) [![Python](https://skillicons.dev/icons?i=python)](#) [![TS](https://skillicons.dev/icons?i=ts)](#) [![Go](https://skillicons.dev/icons?i=go)](#) [![Bash](https://skillicons.dev/icons?i=bash)](#) [![Linux](https://skillicons.dev/icons?i=linux)](#)

**Infra & Observability**<br/>
[![K8s](https://skillicons.dev/icons?i=kubernetes)](#) [![Docker](https://skillicons.dev/icons?i=docker)](#) [![Prometheus](https://skillicons.dev/icons?i=prometheus)](#) [![Grafana](https://skillicons.dev/icons?i=grafana)](#) [![AWS](https://skillicons.dev/icons?i=aws)](#) [![GCP](https://skillicons.dev/icons?i=gcp)](#) [![GitHub Actions](https://skillicons.dev/icons?i=githubactions)](#)

**Messaging & Data**<br/>
[![Kafka](https://skillicons.dev/icons?i=kafka)](#) [![Postgres](https://skillicons.dev/icons?i=postgres)](#) [![Redis](https://skillicons.dev/icons?i=redis)](#) [![MongoDB](https://skillicons.dev/icons?i=mongodb)](#) [![MySQL](https://skillicons.dev/icons?i=mysql)](#)

**ML & AI**<br/>
[![PyTorch](https://skillicons.dev/icons?i=pytorch)](#) [![TensorFlow](https://skillicons.dev/icons?i=tensorflow)](#) [![FastAPI](https://skillicons.dev/icons?i=fastapi)](#) [![React](https://skillicons.dev/icons?i=react)](#) [![Next](https://skillicons.dev/icons?i=nextjs)](#)

`gRPC` · `CUDA` · `Triton` · `Slurm` · `MCP` · `LangGraph` · `Ollama` · `Pinecone`

</div>

## `> tail -f ./experience.log`

```text
[2025-26]  NYU HPC Research Lab       Graduate Research Lead     120-node GPU cluster · generative telemetry modeling
[prev]     The NorthStar Group        SRE / Backend Engineer     100K+ MAU platform · Kafka · gRPC · K8s · Prometheus/Grafana
[prev]     5POINT Solutions           Software Engineer          Low-latency C++ systems
```

## `> stats --github`

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Jex2l&theme=github_dark" height="160" alt="Stats"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Jex2l&theme=github_dark" height="160" alt="Languages"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Jex2l&theme=github_dark" height="160" alt="Commit languages"/>

<img width="68%" src="https://streak-stats.demolab.com?user=Jex2l&theme=tokyonight&background=0D1117&border=00E5CC&stroke=00E5CC&ring=00E5CC&fire=FF6B35&currStreakLabel=00E5CC&sideLabels=8B949E&dates=8B949E&currStreakNum=FFFFFF&sideNums=FFFFFF" alt="Streak"/>

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=Jex2l&theme=tokyo-night&bg_color=0D1117&color=00E5CC&line=00E5CC&point=FF6B35&area=true&hide_border=true&custom_title=Contribution%20Graph" alt="Activity"/>

<img src="https://github-profile-trophy.vercel.app/?username=Jex2l&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=8" alt="Trophies"/>

</div>

## `> currently --exploring`

- 🤖 **Agentic reliability:** evals, approval gates, and safe tool use for ops agents
- 🔭 **Observability for ML and GPU fleets:** telemetry, anomaly detection, capacity signals
- ⚡ **Low-latency systems:** C++ performance and tail-latency work

## `> connect`

<div align="center">

*Hiring for systems, infra, SRE, or applied AI? Let's talk.*

[![Email](https://img.shields.io/badge/📧_pateljeel3105@gmail.com-D14836?style=for-the-badge)](mailto:pateljeel3105@gmail.com)
[![LinkedIn](https://img.shields.io/badge/💼_linkedin.com/in/jeel3105-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/jeel3105/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5CC,50:0B3D3A,100:05080F&height=120&section=footer&text=shipped%20with%20purpose&fontSize=18&fontColor=FFFFFF&fontAlignY=65" width="100%" alt="Footer"/>

</div>
