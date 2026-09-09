<div align="center">

# Abdoul Rachid Ouédraogo (韋正)

<a href="https://github.com/Rekin226">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2E9BF5&center=true&vCenter=true&width=760&lines=AI+%2F+ML+Engineer;LLM+fine-tuning%2C+agentic+systems%2C+physics-informed+ML;I+ship+the+evals%2C+not+just+the+demo;Research-to-production%3A+PyPI%2C+CUDA%2C+CI%2C+MCP" alt="Typing SVG" />
</a>

**Applied AI Researcher @ Taiwan Polar Institute** · **Adjunct Instructor @ FCU** · **Founder of [POUK YAM](https://www.poukyam.com)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/abdoul-rachid-ou%C3%A9draogo-ph-d-4a08481b7)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?logo=huggingface&logoColor=black&style=for-the-badge)](https://huggingface.co/Rekin226)
[![Website](https://img.shields.io/badge/rachidouedraogo.com-2E9BF5?logo=googlechrome&logoColor=white&style=for-the-badge)](https://rachidouedraogo.com)
[![Location](https://img.shields.io/badge/Taichung,_Taiwan-EF4444?logo=googlemaps&logoColor=white&style=for-the-badge)](https://www.google.com/maps/place/Taichung)

</div>

---

Building agentic AI platforms for national agencies: MCP servers, tool-calling analysts, data collectors,
forecasting models, dashboards.

**Background:** 6+ years across R&D, application development, and research, including LLM agents with RAG and ML
shipped in a commercial product.

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [AquaScope](https://github.com/Rekin226/aquascope) ⭐ 28
[![PyPI](https://img.shields.io/badge/PyPI-v0.15.1-2E9BF5?logo=pypi&logoColor=white)](https://pypi.org/project/aquascope/)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.21903143-blue)](https://doi.org/10.5281/zenodo.21903143)
[![MCP](https://img.shields.io/badge/MCP-server-D97757?logo=anthropic&logoColor=white)](https://github.com/Rekin226/aquascope)

Open-source Python toolkit that unifies global water data under one API, then puts an agent on top of it.

- **29 collectors** behind one Pydantic schema: USGS, UK EA, Hub'Eau, GRDC, FAO, GEMStat, EU WFD
- **MCP server** — Claude or Cursor gets stations, series, and cited flood frequency as real tools
- **Studio**: a six-role agent crew (scout, methodologist, analysts, critic, author) plans, runs, and returns a Word + Excel + notebook bundle
- **HydroGym**: gym-style RL environment for model calibration on real basins
- **1,000+ tests** · CAMELS-validated · **24 outside contributors** · Zenodo-archived

[![Explorer](https://img.shields.io/badge/🌊_Explorer-45,919_gauges_in--browser-2E9BF5)](https://rekin226-aquascope-explorer.static.hf.space/)

</td>
<td width="50%" valign="top">

### [Agronaut](https://github.com/Rekin226/Agronaut)
[![PyPI](https://img.shields.io/badge/PyPI-agronaut-3776AB?logo=pypi&logoColor=white)](https://pypi.org/project/agronaut/)
[![Open weights](https://img.shields.io/badge/open_weights-Ollama_%7C_vLLM-1C3C3C)](https://github.com/Rekin226/Agronaut)

Multimodal tool-calling agent over a deterministic, cited engineering core. Zero proprietary APIs.

- LLM collects and routes; a **validation gate** guards a pure, tested trust zone that does the math
- **Photos and voice notes** on Telegram, WhatsApp, and the web — a guard strips any fabricated reading, and a cited table returns a ranked **differential**, never a verdict
- **RAG measured, not asserted**: hit 0.879 · recall 0.833 · MAP 0.604 · 8/10 off-topic queries refused. Nine techniques benchmarked, four ship, every verdict recorded
- Faithfulness + **citation-accuracy** eval; per-turn tracing that records shape, never content
- **1,235 tests** · advice-safety golden set enforced in CI · [DPG](https://github.com/Rekin226/Agronaut/tree/main/docs/dpg) compliance pack

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [HydroPhysicsAI](https://github.com/Rekin226/HydroPhysicsAI)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)](https://github.com/Rekin226/HydroPhysicsAI)
[![PhysicsNeMo](https://img.shields.io/badge/NVIDIA-PhysicsNeMo-76B900?logo=nvidia&logoColor=white)](https://github.com/Rekin226/HydroPhysicsAI)

GPU physics-informed neural operators. One model replaces 61 hand-calibrated ones.

- Simulation **KGE 0.754** vs **0.736** for 61 per-well calibrated ODEs (climatology 0.446)
- Generalizes to **wells it never saw**: leave-one-well-out **0.565**, near the in-sample 0.591
- Forecast LSTM: **0.899** at 30 days vs 0.703 persistence, with ~90% calibrated intervals
- **14×** bf16 GPU speedup · **6.7×** parallel rollout · PhysicsNeMo port, bit-identical
- Negative results published, not buried: the PINN field, the adjoint solver, the subsidence coupling

[![Live demo](https://img.shields.io/badge/%F0%9F%A4%97_demo-live-FFD21E)](https://huggingface.co/spaces/Rekin226/HydroPhysicsAI-demo)

</td>
<td width="50%" valign="top">

### [Mooré-Voice](https://github.com/Rekin226/Moore-Voice)
[![NLLB](https://img.shields.io/badge/NLLB--200-3.3B_LoRA-0668E1?logo=meta&logoColor=white)](https://huggingface.co/Rekin226/nllb-3.3B-moore-lora-v0)
[![Whisper](https://img.shields.io/badge/Whisper-fine--tuned-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/Rekin226/whisper-small-moore-v0)

Translation and speech recognition for Mooré, a language of ~8M people and almost no training data.

- Curated **205,271 parallel pairs** across 4 directions: LID-gated, fragment-filtered, decontaminated against FLORES-200
- **LoRA fine-tunes** of NLLB-200 600M **and 3.3B** on a single consumer RTX 4070
- ASR corpus of **37,654 utterances / 85 h**; Whisper-small at **34.1% WER**, benchmarked against an MMS-1b zero-shot baseline
- Three adapters published on the Hub · BLEU / chrF++ on FLORES-200 devtest · Colab demo

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### [paper-agent](https://github.com/Rekin226/paper-agent) ⭐ 8 · [![Claude Code plugin](https://img.shields.io/badge/Claude_Code-plugin_v1.5.0-D97757?logo=anthropic&logoColor=white)](https://github.com/Rekin226/paper-agent) [![Semantic Scholar](https://img.shields.io/badge/Semantic_Scholar-MCP-1857B6)](https://github.com/Rekin226/paper-agent)

A Claude Code **plugin** that turns the agent into a disciplined manuscript collaborator — five strict modes (draft, review, revise, proofread, audit), **Semantic Scholar MCP** citation resolution with no API key, anti-fabrication guardrails, and a clean `.docx` round-trip. Ships journal profiles for Hydrogeology Journal, JHRS, and IEEE TIM, plus a generic quantitative-science profile. Install with one command: `/plugin marketplace add Rekin226/paper-agent`.

</td>
</tr>
</table>

---

## 🛠️ Tech stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,django,docker,kubernetes,postgres,redis,react,azure,githubactions,linux,git" alt="tech stack" />
</p>

`PyTorch` · `Hugging Face (transformers, PEFT, datasets)` · `LangChain` · `LangGraph` · `AutoGen` · `MCP` · `CUDA / bf16` ·
`NVIDIA PhysicsNeMo` · `RAG & vector search (FAISS)` · `Ollama / vLLM` · `pandas` · `NumPy` · `SciPy` · `FastAPI` ·
`Django` · `PostgreSQL` · `Docker` · `GitHub Actions` · `pytest` · `Streamlit` · `Gradio`

## 🔬 Interests

`Agentic AI & tool use` · `LLM fine-tuning for low-resource languages` · `Evaluation, guardrails & AI safety in production` ·
`Physics-informed & scientific ML` · `Uncertainty quantification` · `AI as a digital public good`

---

## 📌 Recent work

- 🌊 **[AquaScope](https://github.com/Rekin226/aquascope) v0.15.1** — grew from a data library into an agent platform: an **MCP server** that hands Claude and Cursor real gauge data, a **six-role research crew** (`aquascope studio`) that writes a brief, proposes a methodology you approve, runs it with a check after every step and returns a Word/Excel/notebook bundle, and the **[Explorer](https://rekin226-aquascope-explorer.static.hf.space/)** — 45,919 public gauges on one map with flood frequency computed **in the browser** on Pyodide, no server. Now **24 outside contributors**, a Zenodo DOI, and an open weekly-harvested GeoParquet archive on [Hugging Face](https://huggingface.co/datasets/Rekin226/aquascope-gauges)
- 🗣️ **[Mooré-Voice](https://github.com/Rekin226/Moore-Voice)** — new. LoRA fine-tunes of **NLLB-200 3.3B** and Whisper-small for Mooré, my mother tongue, trained on a corpus I curated from scratch: 205k parallel pairs, LID-gated and decontaminated against FLORES-200, plus 85 hours of transcribed audio. Three adapters are on the Hub; the corpus goes upstream to Common Voice
- 🌱 **[Agronaut](https://github.com/Rekin226/Agronaut)** — the aquaponics agent gained **field senses** (photos and voice notes on Telegram, WhatsApp and the web) and, more importantly, the instruments to know whether it works: a 33-query retrieval golden set with recorded verdicts for **nine** techniques, an LLM-judged faithfulness eval beside a code-checked citation-accuracy score, and per-turn tracing that records latency and shape but never message content. **1,235 tests**, an advice-safety golden set that fails the build on a regression
- 🧠 **[HydroPhysicsAI](https://github.com/Rekin226/HydroPhysicsAI)** — adding multi-timescale recharge memory and an ET driver lifted one shared operator from KGE 0.591 to **0.754**, past the 61 hand-calibrated ODEs it replaces. Leave-one-well-out generalization went 0.236 → **0.565**. The negative results (a continuous-field PINN, an adjoint rollout, three subsidence couplings) are written up with the same care as the wins
- 🤖 **[paper-agent](https://github.com/Rekin226/paper-agent) v1.5.0** — packaged as a **Claude Code plugin**, broadened from hydrology to IEEE and a generic quantitative-science profile
- 🎓 **Numerical Analysis with Python** — graduate course taught at Feng Chia University
- 💼 **[POUK YAM](https://www.poukyam.com)** — consulting and software at the intersection of agentic AI and scientific computing

---

## 📈 GitHub activity

<div align="center">

<img height="170" src="https://github-readme-stats-ivory-nu-35.vercel.app/api?username=Rekin226&show_icons=true&theme=react&hide_border=true&include_all_commits=true&count_private=true" alt="stats" />
<img height="170" src="https://github-readme-stats-ivory-nu-35.vercel.app/api/top-langs/?username=Rekin226&layout=compact&theme=react&hide_border=true&langs_count=8" alt="top langs" />

<img src="https://streak-stats.demolab.com?user=Rekin226&theme=react&hide_border=true" alt="streak" />

<img src="https://github-profile-trophy-seven-theta.vercel.app/?username=Rekin226&theme=algolia&no-frame=true&no-bg=true&margin-w=4&column=7" alt="trophies" />

</div>

---

<div align="center">

**Open to conversations about AI/ML engineering roles and collaborations.**
[LinkedIn](https://www.linkedin.com/in/abdoul-rachid-ou%C3%A9draogo-ph-d-4a08481b7) · [rachidouedraogo.com](https://rachidouedraogo.com)

[![POUK_YAM](https://img.shields.io/badge/POUK_YAM-2E9BF5?logo=googlechrome&logoColor=white)](https://www.poukyam.com)
[![AquaScope](https://img.shields.io/badge/⭐_AquaScope-2E9BF5?logo=github&logoColor=white)](https://github.com/Rekin226/aquascope)

<sub>Building AI for science · Taichung, Taiwan</sub>

</div>
