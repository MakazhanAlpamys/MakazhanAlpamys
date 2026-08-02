<h1 align="center">Alpamys Makazhan</h1>

<p align="center">
  <b>Co-Founder &amp; CTO at <a href="https://trysoup.dev">Soup</a></b> — open-source LLM fine-tuning.<br>
  Astana, Kazakhstan.
</p>

<p align="center">
  <a href="https://trysoup.dev"><img src="https://img.shields.io/badge/Website-trysoup.dev-b8492a?style=flat-square" alt="Website"></a>
  <a href="https://www.linkedin.com/in/justalpamys/"><img src="https://img.shields.io/badge/LinkedIn-justalpamys-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://x.com/JustAlpamys"><img src="https://img.shields.io/badge/X-@JustAlpamys-000000?style=flat-square&logo=x&logoColor=white" alt="X"></a>
  <a href="mailto:makazanalpamys@gmail.com"><img src="https://img.shields.io/badge/Email-makazanalpamys-555555?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

I write infrastructure for people who train models on hardware that shouldn't be able to train them.

Started taking freelance work at 15 and have delivered **100+ projects** since. Now full-time on Soup — 96% of its commits, 100% of its architecture.

<br>

## Soup — fine-tune any open LLM in one command

<p>
  <a href="https://pypi.org/project/soup-cli/"><img src="https://img.shields.io/pypi/v/soup-cli?style=flat-square&color=b8492a&label=PyPI" alt="PyPI"></a>
  <a href="https://pepy.tech/project/soup-cli"><img src="https://img.shields.io/pepy/dt/soup-cli?style=flat-square&color=b8492a&label=downloads" alt="Downloads"></a>
  <a href="https://github.com/MakazhanAlpamys/Soup"><img src="https://img.shields.io/github/stars/MakazhanAlpamys/Soup?style=flat-square&color=b8492a&label=stars" alt="Stars"></a>
  <img src="https://img.shields.io/badge/license-Apache--2.0-555555?style=flat-square" alt="License">
</p>

```bash
pip install soup-cli
soup init --template chat
soup train
```

Fine-tuning today means assembling six libraries and writing 200 lines of glue for every project. Soup collapses that into three commands — 20 training methods, 142 model recipes, 9 quantization formats, multi-GPU, and one-command export to GGUF, Ollama and HuggingFace.

Two things nothing else does:

- **Layer streaming** — the frozen base model streams from CPU RAM one decoder layer at a time, so peak VRAM is bounded by a single layer instead of the whole model. Measured: a **3B model fine-tuned in 2.15 GB on a 4 GB laptop GPU**. First fine-tuning CLI where the base model doesn't have to fit in VRAM at all.
- **Training provenance** — CycloneDX ML-BOM, SLSA-3 in-toto attestation, EU AI Act Annex XI/XII documentation, HIPAA/SOC 2 audit logs, ed25519-signed adapters, weight-space backdoor scanning. No other fine-tuning tool, open-source or managed, ships a line of this.

**153,000 lines of Python · 16,735 automated tests · 167 releases in five months · Linux, macOS and Windows on Python 3.10–3.12.**

<br>

## Selected work

| | |
|---|---|
| **[Soup](https://github.com/MakazhanAlpamys/Soup)** | LLM fine-tuning CLI. Layer streaming, 20 training methods, full training-provenance stack. `Python` `PyTorch` |
| **[Kaspi Analytics Platform](https://github.com/MakazhanAlpamys/Kaspi-Analytics-Platform)** | Analytics over 210,000+ Kaspi.kz marketplace products with ML forecasting. `Next.js` `FastAPI` |
| **[NASA Exoplanet Detection AI](https://github.com/MakazhanAlpamys/NASA-Exoplanet-Detection-AI)** | Ensemble ML finding exoplanets in Kepler/K2/TESS data, SHAP-explained. *NASA Space Apps Global Nominee* |
| **[ClaudeShield](https://github.com/MakazhanAlpamys/claudeshield)** | Secure Docker sandbox for AI coding agents — secret isolation, command policy, audit trail. `Go` |
| **[PermitForge](https://github.com/MakazhanAlpamys/Permit-Forge)** | Hybrid-RAG assistant over Dubai Municipality building codes. 1,202 tests. `Next.js` `Gemini` `pgvector` |
| **[Higgsfield DS](https://github.com/MakazhanAlpamys/Higgsfield-DS)** | Churn model separating voluntary from involuntary churn. *HackNU 2026 — 2nd best macro-F1* |
| **[Smart City Advisor](https://github.com/MakazhanAlpamys/Smart-City-Advisor)** | RAG assistant for places and events in Astana. *1st place, GDG Astana 2025* |
| **[memory-service](https://github.com/MakazhanAlpamys/memory-service)** | Long-term memory for AI agents — LLM extraction, pgvector, hybrid budget-aware recall. `Python` |

<br>

## Recognition

**NASA Space Apps Challenge 2025** — winner, Astana local round; Global Nominee &nbsp;·&nbsp; **GDG Astana 2025** — 1st place &nbsp;·&nbsp; **Meta Llama Accelerator 2025** — finalist &nbsp;·&nbsp; **Google DevFest 2024** — speaker, 500+ audience &nbsp;·&nbsp; **Terricon Valley 2025** — speaker

<br>

## Stack

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HuggingFace">
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js">
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter">
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS">
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP">
</p>

<br>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MakazhanAlpamys&bg_color=00000000&color=b8492a&line=b8492a&point=b8492a&area=true&area_color=b8492a&hide_border=true&radius=6&custom_title=Contributions" alt="Contribution activity" width="100%">
</p>
