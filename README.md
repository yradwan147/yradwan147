<!-- ============================================== -->
<!--  Header — wave + typing                        -->
<!-- ============================================== -->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=200&section=header&text=Yousef%20Radwan&fontSize=56&fontAlignY=36&animation=fadeIn&fontColor=ffffff&desc=AI%20Engineer%20%E2%80%A2%20Agentic%20Systems%20%E2%80%A2%20Applied%20Research&descSize=18&descAlign=50&descAlignY=58" width="100%"/>
</div>

<p align="center">
  <a href="https://github.com/yradwan147">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&multiline=false&width=720&height=46&lines=AI+Engineer+%E2%80%A2+Agentic+Systems+%E2%80%A2+Applied+ML+Research;Building+auditable+LLM+agents+%26+production-grade+ML+systems;MS+TIE+%40+KAUST+%E2%80%94+ML+Engineer+%40+DeSci+(Switzerland)" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Agentic_AI_%26_Applied_ML-1f3f63?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Stack-PyTorch_%E2%80%A2_HF_%E2%80%A2_smolagents-3a5d80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Open_to_Research_%26_Collaboration-0e2a47?style=for-the-badge" />
  <img src="https://komarev.com/ghpvc/?username=yradwan147&label=Profile%20views&color=58A6FF&style=for-the-badge" alt="Profile views" />
</p>

<br/>

<!-- ============================================== -->
<!--  About                                         -->
<!-- ============================================== -->

## 👋 About

AI engineer focused on **agentic systems, applied ML research, and auditable production
pipelines**. Currently building healthcare-triage + multi-agent workflows, fine-tuning small
LLMs (GRPO + LoRA), and shipping research code that re-runs end-to-end. I care about the
**reproducibility-vs-velocity** trade-off — every artefact in this profile re-executes from a
single command.

```yaml
location:   "🇸🇦 KAUST, Saudi Arabia  ←→  🇪🇬 Cairo, Egypt"
education:  "MS Tech, Innovation & Entrepreneurship — KAUST"
working_on: ["agentic LLM workflows", "small-model fine-tuning (GRPO + LoRA)",
             "multi-modal moderation", "applied research papers"]
publishing: ["NeurIPS 2026 — V-axis emotion centroids",
             "NeurIPS 2026 — Cross-Architecture Substrate",
             "INFOCOM / GSMA telecom-LLM track (×4 papers)"]
shipping:   "EdGame — K-12 stealth-assessment learning games"
```

<br/>

<!-- ============================================== -->
<!--  Featured projects                             -->
<!-- ============================================== -->

## 🎯 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🏥 [Healthcare Triage — Capstone Synthesis](https://github.com/yradwan147/cd001-p7-industry-synthesis)

End-to-end breast-cancer screening triage workflow that integrates a tuned RandomForest
classifier (P3), a smolagents-style audit layer (P6), and a vendored CNN feature hook (P4).
**Zero malignant cases missed** in the 114-case held-out cohort at the screening threshold.

`PyTorch` `sklearn` `OpenAI` `joblib`

</td>
<td width="50%" valign="top">

### 🪙 [Beaver's Choice Multi-Agent System](https://github.com/yradwan147/nd900-p4-beavers-choice)

Five-agent **smolagents** orchestrator-worker system for a paper-supply company: inventory +
quoting + sales + finance workers behind a customer-facing orchestrator. Wraps 7 SQLite
helpers as `@tool`s; produces an audited cash + inventory ledger on
`quote_requests_sample.csv`.

`smolagents` `gpt-4o-mini` `SQLAlchemy` `pandas`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [UdaPlay — RAG + Web Fallback](https://github.com/yradwan147/nd900-p3-udaplay)

ChromaDB-backed RAG agent over 15 video-game JSON records with **LLM-as-judge retrieval
evaluation** and a **Tavily web-search fallback**. Three demo queries; the third correctly
delegates to web search and cites a Wikipedia URL.

`ChromaDB` `OpenAI` `Tavily` `pydantic`

</td>
<td width="50%" valign="top">

### 🧪 [GRPO + LoRA Fine-Tuning of Qwen2.5-3B](https://github.com/yradwan147/udacity-nd608-grpo-lora-letter-counter)

Reinforcement-learning fine-tune of **Qwen2.5-3B-Instruct** on a chain-of-thought
letter-counting task using **GRPO** with **LoRA** adapters. Demonstrates training-time
reward shaping on a small model.

`Hugging Face TRL` `LoRA` `Qwen` `transformers`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚀 [AgentsVille Trip Planner](https://github.com/yradwan147/nd900-p1-trip-planner)

CoT + **ReAct** travel-itinerary system. A Chain-of-Thought planner emits a strict
Pydantic-validated `TravelPlan`; an Itinerary-Revision agent runs a THINK→ACT→OBSERVE loop
over four tools with a `run_evals_tool`-before-`final_answer_tool` exit invariant.

`OpenAI` `pydantic` `json-repair`

</td>
<td width="50%" valign="top">

### 🛰️ [NASA Apollo &amp; Challenger RAG Chat](https://github.com/yradwan147/udacity-nd608-nasa-rag-chat)

Retrieval-augmented chat over **Apollo 11, Apollo 13, and Challenger** mission documents.
Vector store + reranker + cited answers. Gradio UI; FastAPI backend.

`LangChain` `ChromaDB` `Gradio` `FastAPI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [Multimodal Content Moderation](https://github.com/yradwan147/udacity-nd608-multimodal-moderation)

Pipeline that moderates **text, image, audio, and video** with **pydantic-ai**, a streaming
Gradio chat UI, and a FastAPI service layer. Structured outputs end-to-end.

`pydantic-ai` `FastAPI` `Gradio` `Whisper`

</td>
<td width="50%" valign="top">

### 🎮 [EdGame — Stealth-Assessment Learning Games](https://github.com/yradwan147/edgame-platform)

Production K-12 ed-tech platform: 5 **KAPLAY.js** games, **ECD** (Evidence-Centered Design)
analytics, 90K+ event samples. Built for a startup; live in classrooms.

`KAPLAY.js` `Node.js` `PostgreSQL` `React`

</td>
</tr>
</table>

> [!TIP]
> Full project list — the **Udacity AI Mastery Capstone** spans 8 chapters (`cd001-p1` … `cd001-p8`); the **Agentic AI Nanodegree** spans 4 (`nd900-p1` … `nd900-p4`); research code lives under `paper1_*` … `paper4_*` and the `vaxis-paper` / `substrate-paper` NeurIPS submissions.

<br/>

<!-- ============================================== -->
<!--  Tech stack                                    -->
<!-- ============================================== -->

## 🧰 Tech stack

<details open>
<summary><b>Languages</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,js,ts,cpp,latex,bash,sql,html" />
</p>
</details>

<details open>
<summary><b>ML, deep learning, generative AI</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000" />
  <img src="https://img.shields.io/badge/Diffusers-9146FF?style=for-the-badge&logo=huggingface&logoColor=white" />
  <img src="https://img.shields.io/badge/LoRA%20%26%20PEFT-FF6F00?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Apple%20MPS-000000?style=for-the-badge&logo=apple&logoColor=white" />
</p>
</details>

<details open>
<summary><b>Agentic AI &amp; LLM tooling</b></summary>
<p align="center">
  <img src="https://img.shields.io/badge/OpenAI%20SDK-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/smolagents-FFB000?style=for-the-badge&logo=huggingface&logoColor=000" />
  <img src="https://img.shields.io/badge/pydantic--ai-E92063?style=for-the-badge&logo=pydantic&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-FF4F4F?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Tavily-2E7CF6?style=for-the-badge&logo=duckduckgo&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white" />
</p>
</details>

<details open>
<summary><b>Data &amp; backend</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,sqlite,fastapi,flask,django,redis,docker" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/Statsmodels-3F4F9D?style=for-the-badge&logo=python&logoColor=white" />
</p>
</details>

<details>
<summary><b>Web, mobile, ed-tech</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,vite,tailwind" />
  <img src="https://img.shields.io/badge/KAPLAY.js-FF6B00?style=for-the-badge&logo=javascript&logoColor=white" />
  <img src="https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
</p>
</details>

<details>
<summary><b>DevOps, infra, tooling</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,linux,aws,gcp,vscode,jupyter" />
  <img src="https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black" />
</p>
</details>

<br/>

<!-- ============================================== -->
<!--  GitHub stats                                  -->
<!-- ============================================== -->

## 📊 GitHub stats

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=yradwan147&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&count_private=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yradwan147&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&langs_count=8" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=yradwan147&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=yradwan147&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=58A6FF&line=58A6FF&point=ffffff&area=true&area_color=58A6FF" alt="Contribution graph" />
</div>

<br/>

<!-- ============================================== -->
<!--  Snake contribution animation                  -->
<!-- ============================================== -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yradwan147/yradwan147/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yradwan147/yradwan147/output/github-contribution-grid-snake.svg" />
    <img alt="snake eating my contributions" src="https://raw.githubusercontent.com/yradwan147/yradwan147/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

<br/>

<!-- ============================================== -->
<!--  Publications                                  -->
<!-- ============================================== -->

## 📚 Publications &amp; research

<table>
<tr><th align="left">Year</th><th align="left">Venue</th><th align="left">Title (repo / link)</th></tr>
<tr><td>2026</td><td>NeurIPS (under review)</td><td><a href="https://github.com/yradwan147/vaxis-paper">Nine Emotion Centroids — A Label-Free Valence Axis Across Four Modalities</a></td></tr>
<tr><td>2026</td><td>NeurIPS (under review)</td><td><a href="https://github.com/yradwan147/substrate-paper">The Cross-Architecture Substrate</a></td></tr>
<tr><td>2026</td><td>Telecom-LLM track</td><td><a href="https://github.com/yradwan147/paper1_d1_path_lora_rag">Three Levers to Make LLMs Configure 5G Networks (catalog grounding + LoRA + RAG)</a></td></tr>
<tr><td>2026</td><td>INFOCOM track</td><td><a href="https://github.com/yradwan147/paper2_d2_lyapunov">Geometric V-Metric Instrumentation on Telecom Control Substrates</a></td></tr>
<tr><td>2026</td><td>Wireless control</td><td><a href="https://github.com/yradwan147/paper3_d3_whisper">Rate-Distortion Characterization of a 6-Bit VQ Codec (LLM + linear baselines)</a></td></tr>
<tr><td>2026</td><td>GSMA benchmarking</td><td><a href="https://github.com/yradwan147/paper4_d4_max_tokens">max_tokens × Prompt-Length Confound in Telecom-MCQ LLM Benchmarking</a></td></tr>
<tr><td>2025</td><td>Frontiers in Human Neuroscience</td><td>Stochasticity as a Solution for Overfitting (EEG inner-speech classification)</td></tr>
<tr><td>2025</td><td>Scientific Data</td><td>ArEEG — Arabic Inner Speech EEG Dataset</td></tr>
<tr><td>2024</td><td>EUROCAST</td><td>Symbolic Regression — Genetic Programming vs ML/DL</td></tr>
<tr><td>2023</td><td>3ICT Conference</td><td>Smart Attendance Using BLE</td></tr>
</table>

<br/>

<!-- ============================================== -->
<!--  Trophies                                      -->
<!-- ============================================== -->

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=yradwan147&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=10" />
</div>

<br/>

<!-- ============================================== -->
<!--  Connect                                       -->
<!-- ============================================== -->

## 🤝 Connect

<p align="center">
  <a href="https://github.com/yradwan147">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:yousef.radwan@kaust.edu.sa">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/yousef-radwan-2b5b1019b/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://scholar.google.com/citations?hl=en">
    <img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" />
  </a>
</p>

<br/>

<!-- ============================================== -->
<!--  Footer wave                                   -->
<!-- ============================================== -->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=120&section=footer" width="100%"/>
</div>

<p align="center"><sub><i>Reproducibility is a feature, not a constraint.</i></sub></p>
