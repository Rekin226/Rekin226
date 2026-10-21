<div align="center">

# Abdoul Rachid Ouédraogo (韋正)

<a href="https://github.com/Rekin226">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2E9BF5&center=true&vCenter=true&width=760&lines=AI+%2F+ML+Engineer;LLM+fine-tuning%2C+agentic+systems%2C+physics-informed+ML;I+ship+the+evals%2C+not+just+the+demo;Research-to-production%3A+PyPI%2C+CUDA%2C+CI%2C+MCP" alt="Typing SVG" />
</a>

**Applied AI Researcher @ Taiwan Polar Institute** · **Founder of [POUK YAM](https://www.poukyam.com)**

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

### [AquaScope](https://github.com/Rekin226/aquascope) ⭐ 30
[![PyPI](https://img.shields.io/badge/PyPI-v0.27.0-2E9BF5?logo=pypi&logoColor=white)](https://pypi.org/project/aquascope/)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.21903143-blue)](https://doi.org/10.5281/zenodo.21903143)
[![MCP](https://img.shields.io/badge/MCP-server-D97757?logo=anthropic&logoColor=white)](https://github.com/Rekin226/aquascope)

Explore river records and run reproducible water analyses in your browser or in Python, with an agent on top.

- **37 global water-data sources** behind one Pydantic schema: USGS, UK EA, Hub'Eau, GRDC, FAO, GEMStat, EU WFD
- **Every river on a globe**: ~6.8M GEOGLOWS reaches, 15-day forecasts, an A to D evidence ladder grading global models, flood layers back to 1990
- **AI on the map**: ask the map, explain this view, review your model results, run what-if scenarios
- **Studio**: a seven-role agent crew plans, runs, and signs off a study, returning Word, Excel, notebook, and engineering exports (HEC-RAS/HMS, SWMM, MODFLOW 6)
- **MCP server** for Claude or Cursor · **HydroGym** RL calibration environment
- **3,200+ tests** · CAMELS-validated · **30+ outside contributors** · Zenodo-archived

[![Explorer](https://img.shields.io/badge/🌊_Explorer-open_in_browser-2E9BF5)](https://rekin226-aquascope-explorer.static.hf.space/)

</td>
<td width="50%" valign="top">

### [Agronaut](https://github.com/Rekin226/Agronaut) ⭐ 5
[![PyPI](https://img.shields.io/badge/PyPI-v1.4.0-3776AB?logo=pypi&logoColor=white)](https://pypi.org/project/agronaut/)
[![Runs local](https://img.shields.io/badge/runs_local-Ollama-1C3C3C)](https://github.com/Rekin226/Agronaut)

Open-source agriculture assistant you run on your own machine: a multimodal tool-calling agent over a deterministic, cited engineering core.

- LLM collects and routes; a **validation gate** guards a pure, tested trust zone that does the math, and every number in a reply is checked against what the engine computed
- Cited **aquaponics and hydroponics design** (10 fish, 34 crops), farm and crop records, and experimental field-irrigation checks (drip, sprinkler, soil water)
- **Photos and voice notes** on Telegram, WhatsApp, and the web; a cited table returns a ranked **differential**, never a verdict
- **RAG measured, not asserted**: hit 0.879 · recall 0.833 · MAP 0.604 · 8/10 off-topic refused; nine techniques benchmarked, four ship. Faithfulness ~0.8, citation accuracy 1.00, judge agreement reported too
- **1,770+ tests** · advice-safety golden set in CI · `agronaut eval` · [DPG](https://github.com/Rekin226/Agronaut/tree/main/docs/dpg) compliance pack

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [HydroPhysicsAI](https://github.com/Rekin226/HydroPhysicsAI)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)](https://github.com/Rekin226/HydroPhysicsAI)
[![PhysicsNeMo](https://img.shields.io/badge/NVIDIA-PhysicsNeMo-76B900?logo=nvidia&logoColor=white)](https://github.com/Rekin226/HydroPhysicsAI)

A differentiable research twin of Taiwan's Choushui alluvial fan: pumping policy in, groundwater heads and land subsidence out, gated against held-out data at every stage.

- **174 monitoring wells**, **116,769 metered pumps**, **798 leveling benchmarks**, 2012–2022, on a 1 km four-aquifer grid
- Full chain hindcast of subsidence: **R² 0.639, RMSE 5.7 cm** across 36 ensemble members; compaction column **R² 0.652** out of fold
- Policy projections to 2032 (36 members × 3 policies × 21 years in ~50 min on one GPU) and a decision app with orthophoto and terrain
- **Failures published, not hidden**: on new 2023–2026 data the frozen forecast loses to seasonal climatology (RMSE 2.07 m vs 1.67 m), and every gate verdict is in the README

[![Live demo](https://img.shields.io/badge/%F0%9F%A4%97_demo-live-FFD21E)](https://huggingface.co/spaces/Rekin226/HydroPhysicsAI-demo)

</td>
<td width="50%" valign="top">

### [Mooré-Voice](https://github.com/Rekin226/Moore-Voice)
[![MMS](https://img.shields.io/badge/MMS--1b-fine--tuned_ASR-0668E1?logo=meta&logoColor=white)](https://github.com/Rekin226/Moore-Voice)
[![NLLB](https://img.shields.io/badge/NLLB--200-3.3B_LoRA-0668E1?logo=meta&logoColor=white)](https://huggingface.co/Rekin226/nllb-3.3B-moore-lora-v0)

Speech recognition and translation for Mooré, a language of ~8M people and almost no training data.

- ASR corpus of **37,654 utterances / 85 h**; fine-tuned MMS-1b reaches **16.8% WER / 4.3% CER** on 564 held-out utterances, vs 31.1% zero-shot
- Curated **205,271 parallel pairs** across 4 directions: LID-gated, fragment-filtered, decontaminated against FLORES-200
- **LoRA fine-tunes** of NLLB-200 600M **and 3.3B** on a single consumer RTX 4070
- Honest about what isn't solved: a native-speaker blind A/B puts translation at a coin flip, so it ships as unproven
- Three adapters on the Hub · Colab demo

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### [paper-agent](https://github.com/Rekin226/paper-agent) ⭐ 8 · [![Claude Code plugin](https://img.shields.io/badge/Claude_Code-plugin_v1.7.0-D97757?logo=anthropic&logoColor=white)](https://github.com/Rekin226/paper-agent) [![Semantic Scholar](https://img.shields.io/badge/Semantic_Scholar-MCP-1857B6)](https://github.com/Rekin226/paper-agent)

A Claude Code **plugin** that turns the agent into a disciplined manuscript collaborator. Six strict modes (draft, review, revise, proofread, audit, format), **Semantic Scholar MCP** citation resolution with no API key, anti-fabrication guardrails, a number checker that traces every figure to its source, and a submission-ready `.docx` with a compliance report. Ships profiles for 10 journals (Hydrogeology Journal, J. Hydrology, WRR, HESS, Groundwater, IEEE TIM, and more) plus a generic quantitative-science profile. Install with one command: `/plugin marketplace add Rekin226/paper-agent`.

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
