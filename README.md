<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1020,55:2455c7,100:8b5cf6&height=205&section=header&text=Brindha%20Senthilkumar&fontSize=43&fontColor=ffffff&fontAlignY=35&desc=Distributed%20Systems%20%7C%20LLM%20Systems%20%7C%20Applied%20AI&descSize=17&descColor=dbeafe&descAlignY=57" width="100%" alt="Brindha Senthilkumar: Distributed Systems, LLM Systems, Applied AI" />

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=19&duration=3200&pause=1100&color=7AA2FF&center=true&vCenter=true&width=740&lines=Building+systems+that+keep+working+when+things+fail;Making+LLM+training+faster+on+GPUs;From+consensus+protocols+to+citation-grounded+AI" alt="Building fault-tolerant systems, GPU training tools, and AI applications" />

<br />

[![GitHub](https://img.shields.io/badge/GitHub-brindhas110404-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/brindhas110404)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brindha-s-465728360/)
[![Projects](https://img.shields.io/badge/Explore-Projects-5B5BD6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/brindhas110404?tab=repositories)

</div>

---

## 👩‍💻 About Me

```python
brindha = {
    "now": "MS in Computer Science and Applied Mathematics, Stony Brook (May 2027)",
    "focus": ["Distributed Systems", "LLM Systems", "Applied AI"],
    "languages": ["Python", "Go", "TypeScript", "C++", "SQL", "R"],
    "building_with": ["PyTorch", "gRPC", "Docker", "Cloudflare Workers", "Next.js", "Django"],
    "currently_learning": ["CUDA", "Nsight Systems", "GPU performance"],
    "open_to": "2027 new grad roles in AI engineering, ML systems, and backend",
}
```

I build projects to understand how software behaves under real conditions: workers fail, data moves between machines, transactions cross boundaries, and models have to show where their answers came from. Lately I'm working on the other end of AI too: making model training itself faster on GPUs.

- 🔬 **Graduate Research Assistant, IRS Labs, Stony Brook University.** Building MedRec with Stony Brook Hospital, a multimodal AI app that reads handwritten prescriptions, pill images, audio, and pill-bottle videos to extract medication names and dosages.
- 🧑‍🏫 **Teaching Assistant, CSE 581** (Computer Science Fundamentals: Theory).
- 💼 **Previously at Social Friend, Chennai:** software engineer intern on iFriend, an AI chat assistant for 2,000+ students, and data science intern building ETL pipelines and dashboards.

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center">🧠 Fault-Tolerant Distributed ML</h3>

Synchronous data-parallel training with a fused Ring-AllReduce I wrote from scratch over gRPC.

- **2.83x throughput** and **94% scaling efficiency** on 3 workers.
- Heartbeat failure detection (max 3.4 s), checkpoint rollback, and idempotent commits.
- Recovered from **all 200 injected faults**; final weights match serial training to 7.77e-16.

`Python` `NumPy` `gRPC` `Docker` `Ring-AllReduce`

<div align="center">

[![View repository](https://img.shields.io/badge/View-Repository-2455C7?style=for-the-badge&logo=github&logoColor=white)](https://github.com/brindhas110404/fault-tolerant-distributed-ml-training)
[Final report](https://github.com/brindhas110404/fault-tolerant-distributed-ml-training/blob/main/FINAL_REPORT.md)

</div>

</td>
<td width="50%" valign="top">

<h3 align="center">📚 CiteSeek: Citation-Grounded RAG</h3>

A research assistant that answers questions about your papers and cites the exact passage behind every claim.

- Llama 3.1 8B rewrites the query, vector search finds the top 20, a reranker keeps 6, and Llama 3.3 70B streams the answer.
- Two-stage library search: the same 2 vector queries for 10 papers or 1,000.
- Checkpointed ingestion, a 161,141-paper topic map, and 19 end-to-end tests, all on Cloudflare's free plan.

`TypeScript` `Cloudflare Workers` `Llama 3.3` `Vectorize` `D1`

<div align="center">

[![Live demo](https://img.shields.io/badge/Live-Demo-16A34A?style=for-the-badge&logo=cloudflare&logoColor=white)](https://citeseek.brindhas110404.workers.dev/)
[![View repository](https://img.shields.io/badge/View-Repository-7C3AED?style=for-the-badge&logo=github&logoColor=white)](https://github.com/brindhas110404/citeseek)

</div>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3 align="center">⚡ GPU LLM Training Profiler <sub>(in progress)</sub></h3>

Measuring and speeding up GPT-2 (124M) pre-training one optimization at a time.

- fp32, TF32, bf16 mixed precision, FlashAttention, and torch.compile, profiled with Nsight Systems.
- A fused bias + GELU CUDA kernel and a roofline model of every op in a transformer block.
- An agent that reads the profiles, names the bottleneck, and runs the next experiment.

`Python` `PyTorch` `CUDA` `Nsight Systems`

<div align="center">

[![View repository](https://img.shields.io/badge/View-Repository-2455C7?style=for-the-badge&logo=github&logoColor=white)](https://github.com/brindhas110404/gpu-llm-training-profiler)

</div>

</td>
<td width="50%" valign="top">

<h3 align="center">🏦 Distributed Banking System</h3>

A Go-based banking system exploring replicated state and transaction coordination across shards.

- Paxos consensus within each cluster.
- Two-phase commit for cross-shard transactions, with rollback on abort.
- SQLite persistence, RPC communication, and recovery after failures.

`Go` `SQLite` `RPC` `Paxos` `Two-Phase Commit`

<div align="center">

[![View repository](https://img.shields.io/badge/View-Repository-7C3AED?style=for-the-badge&logo=github&logoColor=white)](https://github.com/brindhas110404/Distributed-Banking-System-Paxos-2PC)

</div>

</td>
</tr>
</table>

---

## ✨ More Projects

| Project | What it does | Stack |
|:--------|:-------------|:------|
| [**SmartAI**](https://github.com/brindhas110404/smartai) · [Live](https://smartai-omega-two.vercel.app/) | An AI workspace where a Gemini planner routes each request to chat, code, image, voice, or vision tools and chains up to 3 steps, with usage tracking and per-user rate limits. | `Next.js` `TypeScript` `Gemini` `Prisma` `PostgreSQL` |
| [**Real-Time Vision Assistant**](https://github.com/brindhas110404/real-time-vision-assistant) | A local Flask app with browser streams for TinyYOLOv3 object detection and dlib face recognition, with laptop or phone webcam input and a face-registration flow. | `Python` `Flask` `OpenCV` `TinyYOLOv3` `dlib` |
| [**ICU Patient Phenotyping**](https://github.com/brindhas110404/icu-patient-phenotyping) | Course group project clustering MIMIC-IV ICU stays, studying vital-sign trends, and evaluating admission-time prediction with leakage called out explicitly. | `R` `Python` `K-Means` `scikit-learn` |
| [**ReelyAI**](https://github.com/brindhas110404/reelyai) | Builds short portrait reels from uploaded media with AI narration, optional music, and background video processing. | `Flask` `Redis` `RQ` `ElevenLabs` `FFmpeg` |
| [**PaperMind**](https://github.com/brindhas110404/papermind) | Answers questions over uploaded research papers using retrieval, vector search, and saved chat sessions. | `Cloudflare Workers` `Vectorize` `R2` `TypeScript` |

---

## 🛠️ Tech Stack

| Area | Tools and concepts used in my projects |
|:-----|:---------------------------------------|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white) `SQL` |
| **Distributed systems** | `gRPC` `Protocol Buffers` `Paxos` `Two-Phase Commit` `Ring-AllReduce` |
| **AI and LLMs** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) `LLMs` `RAG` `Embeddings` `Vector Search` `Gemini` `Llama` |
| **GPU performance** | `CUDA (learning)` `Nsight Systems` `Mixed Precision` `FlashAttention` `Roofline Analysis` |
| **ML and vision** | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) `scikit-learn` `TinyYOLOv3` `dlib` |
| **Applications and data** | ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-111827?style=flat-square&logo=flask&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=nextdotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) `Redis` `Cloudflare Workers` `AWS` |
| **Development** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

---

## 🎓 Education

| Degree | University | Dates |
|:-------|:-----------|:------|
| **Master's in Computer Science and Applied Mathematics** | Stony Brook University, New York | Aug 2025 - May 2027 |
| **Bachelor of Engineering in Computer Science and Engineering** | Sri Venkateswara College of Engineering, Anna University, Chennai | Aug 2021 - May 2025 |

---

## 📊 GitHub Activity

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=brindhas110404&theme=github_dark" width="48%" alt="GitHub statistics" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=brindhas110404&theme=github_dark" width="48%" alt="Languages across public repositories" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=brindhas110404&theme=github_dark" width="96%" alt="GitHub contribution activity" />

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/brindhas110404/brindhas110404/output/github-snake-dark.svg?v=2" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/brindhas110404/brindhas110404/output/github-snake.svg?v=2" />
  <img src="https://raw.githubusercontent.com/brindhas110404/brindhas110404/output/github-snake-dark.svg?v=2" width="96%" alt="Animated contribution graph in blue and violet" />
</picture>

</div>

---

<div align="center">

### Explore the code, experiments, and design decisions

[![See my work](https://img.shields.io/badge/See-My%20Work-5B5BD6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/brindhas110404?tab=repositories)
[![Email](https://img.shields.io/badge/Email-Say%20hello-111827?style=for-the-badge&logo=gmail&logoColor=white)](mailto:brindhas110404@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1020,55:2455c7,100:8b5cf6&height=100&section=footer" width="100%" alt="Decorative blue and violet footer" />

</div>
