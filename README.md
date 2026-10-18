<h1 align="center">Hi, I'm Noah👋 </h1>

**Software Engineering** major with a **Business Administration** minor at **South China University of Technology**.
I like building things — web apps, AI experiments, and the occasional weird idea.

<img src="https://raw.githubusercontent.com/NoahIsARider/NoahIsARider/main/dino.svg?v=2" width="850" alt="Chrome dino — an endless runner, day and night" />

💫 [My Personal Page](https://noahisarider.github.io/) · 🎓 [Curriculum Vitae](https://noahisarider.github.io/cv/) · 🛠 [Skills & Tools](https://noahisarider.github.io/NoahIsARider/skills.html) · 🗂️ [Blog](https://noahsblog.pages.dev/) · 📇 [Portfolio](https://noahisarider.github.io/oblivio/portfolio/) · 📍 Guangzhou

---

## 🔬 Research Interests

Artificial Intelligence · Deep Learning · Social Computing · Multi-Agent Systems · Human-AI Collaborative Workflow Design · AI for Business · AI for Healthcare · Recommender Systems

---

## 📦 Things I've Built

| Area | Project | Stack | What it does · the systems idea behind it |
| :--- | :--- | :--- | :--- |
| 🤖 **AI & Multi-Agent** | 🍵 [MatchaFlow](https://github.com/NoahIsARider/MatchaFlow) | Python · LLM orchestration · SQLite shared state | Five role agents (PM → architect → dev → QA → client) run a whole project-management loop; state lives in a shared DB instead of chat history, so every agent reads one project truth and any OpenAI-compatible model can be swapped in. |
| | ⚔️ [Crusaders](https://github.com/NoahIsARider/Crusaders) | TypeScript + Python · evaluation harness | Scaffold for human-machine teams with dynamic power handover: declare actors, handoff rules and metrics once, then measure who should hold control at each step. Rule-based, simulated-expert and real-LLM actors are interchangeable plug-ins. |
| | 🎯 [DLFaceDetection](https://github.com/NoahIsARider/DLFaceDetection) | Python · gRPC · distributed runtime | Face recognition cut into modules that migrate between nodes at runtime; partitioning follows live CPU load and network latency rather than a fixed layout. The scheduling idea is the point, the model is replacement filler. |
| 🩺 **AI for Healthcare** | 🩺 [Open Stethoscope](https://github.com/NoahIsARider/open-stethoscope) | Python · audio DSP · web demo | 404K-param heart-murmur detector that fits in a primary-care laptop; multi-location masked-attention fusion over the four auscultation points, reported with the official PhysioNet-2022 challenge metric instead of a friendlier accuracy number. |
| 💼 **AI for Business & Recommender** | 💼 [ZhituCareer](https://github.com/NoahIsARider/ZhituCareer) | Flask · multi-agent · Docker | Career copilot: LLM agents plus a Playwright live-market scraper feed a matching and course-recommendation engine; the whole platform ships as one `docker compose up`, so the demo never rots. |
| | 🗺️ [Bigdata-Final-System](https://github.com/NoahIsARider/Bigdata-Final-System) | Flink · Kafka · Spark · HBase · ClickHouse · Vue 3 | Store-site selection over telecom signalling data: a real-time path (Flume→Kafka→Flink→HBase) and an offline path (HDFS→Spark→ClickHouse) share one point-in-polygon spatial model. The generator may only write spool files, so nothing shortcuts the pipeline. |
| | 📈 [MankiwEcoLab](https://github.com/NoahIsARider/MankiwEcoLab) | Python · pytest (204 tests) | Every core model in Mankiw's micro and macro, from PPF to the Phillips curve, built as runnable, perturbable, tested code. A textbook turned into a library you can experiment on. |
| | 🛡️ [RecRedTeam](https://github.com/NoahIsARider/RecRedTeam) | Python · OWASP ASI 2026 · Streamlit | Red-team audit framework for LLM shopping and recommendation agents: threat taxonomy, attack library, dual-channel judge, defense plugins, leaderboard and compliance reports. LangGraph and OpenAI-Agents adapters fall back deterministically, so an audit always finishes. |
| 🦎 **Social Computing** | 🖼️ [AIFrameQuest](https://github.com/NoahIsARider/AIFrameQuest) | Vue 3 · Flask · FAISS · MySQL | A community platform used as an instrument rather than a product: FAISS image similarity plus rating data read through Baudrillard, Hupu as spectacle and Douban as a bid for subjectivity. Research design first, features second. |
| | 🦎 [Reptile](https://github.com/NoahIsARider/Reptile) | Python · BeautifulSoup · headered requests | One crawler interface, an adapter per site: A24 filmographies, Bilibili danmaku, news pages. Thin, adaptable, built to survive layout changes. |
| | ⛓️ [OnChainGov](https://github.com/NoahIsARider/OnChainGov) | Python · Polars · DID / PSM-DID | Chain-governance research toolchain end to end: Snapshot, Tally, EVM and Steemit collection, research-ready panels, then DID, PSM-DID, placebo and event-study estimation with published datasets. |

---

## 🤖 My AI Crew

I keep a couple of agents as pets:

- 🌊 [**Clawbot (Triton)**](https://clawbot-triton.vercel.app) — A digital sea spirit, documenting its dives
- 🏛️ [**Hermesbot (Palaemon)**](https://palaemon-harbor.vercel.app) — A harbor blog

## 🌠 Interesting Projects

Here are some fun projects I'd like to share with you:

- 💐 [**oblivio**](https://noahisarider.codeberg.page/oblivio/) — Oblivion is freedom and no one lasts forever.
- 🗻 [LANDSLIDE](https://github.com/LandslideLab) — A cave for explorations on AI-Human Collaboration and Multi-Agent Systems as well as weird ideas. Feel free to join it.
- 🎧 [Codeberg](https://codeberg.org/NoahIsARider) — Stay original, authentic and independent.
