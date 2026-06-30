<div align="center">

# Abdoul Rachid Ouédraogo (韋正)

<a href="https://github.com/Rekin226">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2E9BF5&center=true&vCenter=true&width=720&lines=Data+Scientist+%26+ML+Researcher%2C+Ph.D.;Physics-informed+ML+%26+agentic+AI+for+science;From+large+multi-source+data+to+validated+predictive+models;Hydrogeologist+by+training%2C+AI+builder+by+practice" alt="Typing SVG" />
</a>

**Applied AI Researcher @ Taiwan Polar Institute** · **Adjunct Instructor @ FCU** · **Founder of [POUK_YAM](https://github.com/Pouk-Yam)**

[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--4616--4153-A6CE39?logo=orcid&logoColor=white&style=for-the-badge)](https://orcid.org/0000-0002-4616-4153)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?logo=googlescholar&logoColor=white&style=for-the-badge)](https://scholar.google.com/citations?user=AFrUnG0AAAAJ)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/abdoul-rachid-ou%C3%A9draogo-ph-d-4a08481b7)
[![Website](https://img.shields.io/badge/rachidouedraogo.com-2E9BF5?logo=googlechrome&logoColor=white&style=for-the-badge)](https://rachidouedraogo.com)
[![Location](https://img.shields.io/badge/Taichung,_Taiwan-EF4444?logo=googlemaps&logoColor=white&style=for-the-badge)](https://www.google.com/maps/place/Taichung)

</div>

---

I build AI for science: physics-informed machine learning, agentic AI, and the tested software that ships it. My depth is in hydrogeology and groundwater modeling, which I use as a proving ground for honest, reproducible scientific ML. I also teach numerical methods at Feng Chia University.

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [HydroPhysicsAI](https://github.com/Rekin226/HydroPhysicsAI)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)](https://github.com/Rekin226/HydroPhysicsAI)
[![CUDA](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white)](https://github.com/Rekin226/HydroPhysicsAI)

GPU physics-informed neural operators for groundwater, one model across 61 wells.

- One attribute-conditioned operator vs **61** hand-calibrated ODEs
- Generalizes to **unseen wells**: leave-one-well-out **KGE 0.565** (climatology 0.446, in-sample 0.591)
- Forecast LSTM beats persistence at **7 & 30 days**, calibrated intervals
- **14×** GPU speedup (CUDA, bf16) · NVIDIA **PhysicsNeMo** port

[![Live demo](https://img.shields.io/badge/%F0%9F%A4%97_demo-live-FFD21E)](https://huggingface.co/spaces/Rekin226/HydroPhysicsAI-demo)

</td>
<td width="50%" valign="top">

### [AquaScope](https://github.com/Rekin226/aquascope)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://github.com/Rekin226/aquascope)
[![PyPI](https://img.shields.io/badge/PyPI-2E9BF5?logo=pypi&logoColor=white)](https://pypi.org/project/aquascope/)

Open-source Python toolkit that unifies global water data under one API.

- **15 collectors**: USGS, FAO, GEMStat, EU WFD, and more
- **26 methodologies** + an agentic AI engine (7 pipelines)
- Bulletin 17C flood frequency, FAO-56 ET, CAMELS-validated
- **500+ tests**, Python 3.10+

[![Support on Ko-fi](https://img.shields.io/badge/Support_on-Ko--fi-FF5E5B?logo=kofi&logoColor=white)](https://ko-fi.com/getaquascope)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Agronaut](https://github.com/Rekin226/Agronaut)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://github.com/Rekin226/Agronaut)
[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)](https://github.com/Rekin226/Agronaut)

Tool-calling aquaponics agent over a deterministic, tested, cited engineering core.

- LLM collects and routes; a verifiable engine does the math
- **Cross-session memory** + a deep troubleshooting knowledge base
- Calibrated on real-pond data; design & optimize need **no LLM**
- Runs as Streamlit or a Telegram agent; Ollama · NVIDIA · HF

</td>
<td width="50%" valign="top">

### [paper-agent](https://github.com/Rekin226/paper-agent)
[![Claude Code plugin](https://img.shields.io/badge/Claude_Code-plugin_v1.5.0-D97757?logo=anthropic&logoColor=white)](https://github.com/Rekin226/paper-agent)
[![Semantic Scholar](https://img.shields.io/badge/Semantic_Scholar-MCP-1857B6)](https://github.com/Rekin226/paper-agent)

Claude Code **plugin** that turns the agent into a disciplined manuscript collaborator.

- Five modes: draft, review, revise, proofread, audit
- **Semantic Scholar MCP** citations (no API key), anti-fabrication guardrails
- Hydrology (HJ, JHRS) + IEEE + a generic quantitative-science profile
- Clean `.docx` round-trip; bundled try-it demos

</td>
</tr>
</table>

---

## 🔬 Research interests

`Physics-informed & scientific ML` · `Agentic AI for science` · `Groundwater modeling & hydrogeology` · `Numerical methods & scientific computing` · `Sustainable water resources`

## 🛠️ Tech stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,fastapi,streamlit,docker,git,github,linux,jupyter,latex" alt="tech stack" />
</p>

---

## 📌 Recent work

- 🧠 **[HydroPhysicsAI](https://github.com/Rekin226/HydroPhysicsAI)**: GPU physics-informed neural operators benchmarked against per-well gray-box ODEs, with a live demo and an honest, reproducible benchmark harness
- 🤖 **[paper-agent](https://github.com/Rekin226/paper-agent)**: packaged as a **Claude Code plugin (v1.5.0)** — draft/review/revise/proofread/audit manuscripts with Semantic Scholar MCP citation integrity, now broadened from hydrology to IEEE and a generic quantitative-science profile
- 🌱 **[Agronaut](https://github.com/Rekin226/Agronaut)**: tool-calling aquaponics agent over a deterministic, cited engineering core, with cross-session memory and a troubleshooting knowledge base
- 📄 **Hydrogeology Journal** accepted manuscript on gray-box groundwater modeling for the Zhuoshui Alluvial Fan, Taiwan
- 📚 **Publications & patent**: 4 peer-reviewed papers (3 SCIE-indexed, incl. *Hydrogeology Journal* 2026) · granted Taiwan patent **M661364**
- 📊 **[aquascope-demos](https://github.com/Rekin226/aquascope-demos)**: real-world reproducible demo cases on public hydrology datasets
- 🎓 **Numerical Analysis with Python**, graduate course taught at Feng Chia University
- 💼 **POUK_YAM**, consulting and software at the intersection of scientific computing and agentic AI

## 🎓 Background

- **Ph.D.**, Infrastructure Planning & Engineering (groundwater modeling & hydrogeology), Feng Chia University, Taiwan · 2023
- **M.S.**, Water Resources Engineering & Conservation, Feng Chia University, Taiwan · 2019
- **Undergraduate**, 2iE (Institut International d'Ingénierie de l'Eau et de l'Environnement), Ouagadougou, Burkina Faso

🌐 Multilingual: French (native) · English (advanced) · Mandarin (working proficiency)

---

## 📈 GitHub activity

<div align="center">

<img height="170" src="https://github-readme-stats-ivory-nu-35.vercel.app/api?username=Rekin226&show_icons=true&theme=react&hide_border=true&include_all_commits=true&count_private=true" alt="stats" />
<img height="170" src="https://github-readme-stats-ivory-nu-35.vercel.app/api/top-langs/?username=Rekin226&layout=compact&theme=react&hide_border=true&langs_count=8" alt="top langs" />

<img src="https://streak-stats.demolab.com?user=Rekin226&theme=react&hide_border=true" alt="streak" />

<img src="https://github-profile-trophy.vercel.app/?username=Rekin226&theme=algolia&no-frame=true&no-bg=true&margin-w=4&column=7" alt="trophies" />

</div>

---

<div align="center">

[![POUK_YAM](https://img.shields.io/badge/POUK__YAM-181717?logo=github&logoColor=white)](https://github.com/Pouk-Yam)
[![AquaScope](https://img.shields.io/badge/⭐_AquaScope-2E9BF5?logo=github&logoColor=white)](https://github.com/Rekin226/aquascope)

<sub>Building AI for science · Taichung, Taiwan</sub>

</div>
