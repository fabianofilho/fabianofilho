<div align="center">

# Hi, I'm Dr. Fabiano Filho! 👋🩺

**Medical Doctor · Data Scientist · AI in Health Specialist**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-fabianofilho-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/fabianofilho/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Fabiano%20Filho-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=IqVY-BQAAAAJ&hl=pt-BR)
[![Substack](https://img.shields.io/badge/Substack-Medicine%20%26%20AI-FF6719?style=flat&logo=substack&logoColor=white)](https://fabianofilho.substack.com/)
[![Medium](https://img.shields.io/badge/Medium-dadosesaude-000000?style=flat&logo=medium)](https://fabianonbfilho.medium.com/)
[![IA.med](https://img.shields.io/badge/IA.med-app.iamed.cc-0D9488?style=flat&logoColor=white)](https://app.iamed.cc)
[![Website](https://img.shields.io/badge/Portfolio-fabianofilho.com-3b82f6?style=flat&logo=google-chrome&logoColor=white)](https://portfolio.fabianofilho.com)

</div>

---

I'm a **medical doctor and data scientist** passionate about using AI to transform healthcare. I currently serve as **Medical Manager of Innovation and AI at Hapvida NotreDame Intermédica** and am a **PhD student in Machine Learning for Public Health at FSP-USP**, researching **multicalibration and fairness** in predictive models to ensure AI is equitable across all populations. 🌱

- 🏥 **Medical AI Manager** · Hapvida NotreDame Intermédica
- 🎓 **PhD Student** · Machine Learning in Public Health · FSP-USP (LABDAPS)
- 🔬 Research in **fairness, multicalibration and dataset shift** in health
- 🧪 Builder of **[IA.med](https://app.iamed.cc)** · open tools and content on AI in medicine, in Portuguese
- 📍 São Paulo, Brazil · Vegan 🌱
- ✉️ drfabianofilho@gmail.com

---

## 🧭 Where I'm heading

The work I'm shipping now follows a few convictions that came out of the clinic, the lab and the health system:

- **Local first.** Clinical text should not leave the machine. My recent tools run on a self-hosted LLM, offline, with no API key required to try them.
- **Brazilian public data as a first-class citizen.** DATASUS, InfoDengue, Anvisa, CFM and Conitec are rich, open and under-tooled. I build the plumbing so others can skip it.
- **Evaluation beyond accuracy.** Variance between identical runs, overconfidence and fragility to semantic perturbation are what accuracy hides. Measure them.
- **Honest scope.** Every tool states what it is not: not an official source, not a medical device, not a substitute for clinical judgment. The official link comes with every answer.
- **Agents that plug into the clinician's workflow.** MCP servers, Claude skills and reproducible pipelines instead of yet another chat window.

---

## 🧰 Toolbox

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Machine Learning & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2E8B57?style=flat&logoColor=white)
![skforecast](https://img.shields.io/badge/skforecast-1F77B4?style=flat&logoColor=white)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-000000?style=flat&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)

**Data & Infrastructure**

![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat&logo=uv&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

**Health & Interoperability**

![FHIR](https://img.shields.io/badge/HL7%20FHIR-E84C27?style=flat&logoColor=white)
![DATASUS](https://img.shields.io/badge/DATASUS-009C3B?style=flat&logoColor=white)

---

## 🚀 Open Source

### 🔌 IA.med MCP suite · [iamed.cc/mcps](https://iamed.cc/mcps)

Model Context Protocol servers that give any LLM client (Claude, Claude Code, others) grounded access to Brazilian health regulation and literature. Local, auditable, every answer links to the official document.

| Server | What it does |
|--------|--------------|
| [**anvisa-mcp**](https://github.com/fabianofilho/anvisa-mcp) | Drug registration status and recent medical devices from Anvisa open data, with a heuristic flag for AI-based devices · public connector available |
| [**radar-cfm-mcp**](https://github.com/fabianofilho/radar-cfm-mcp) | Searches and monitors CFM (Federal Council of Medicine) resolutions on AI, telemedicine and electronic health records · public connector available |
| [**protocolos-pcdt-mcp**](https://github.com/fabianofilho/protocolos-pcdt-mcp) | Queries the Ministry of Health clinical protocols (PCDT/Conitec) and summarizes the recommended conduct with a verified literal citation |
| [**radar-papers-mcp**](https://github.com/fabianofilho/radar-papers-mcp) | Watches PubMed and medRxiv for configurable topics and summarizes new papers with a local LLM, deduplicated by DOI |
| [**revisor-notas-mcp**](https://github.com/fabianofilho/revisor-notas-mcp) | Checks SOAP clinical notes for missing fields and incoherence between complaint, exam and plan · 100% offline |

### 🏥 Open labs on Brazilian public health data

| Project | Description | Stack |
|---------|-------------|-------|
| [**lab-ai-prediction**](https://github.com/fabianofilho/lab-ai-prediction) | Open predictive-modeling lab: run the same pipeline on DATASUS microdata, your own dataset or international benchmarks · [live app](https://lab-ai-prediction.streamlit.app) | Python · Streamlit · scikit-learn |
| [**datasus-outbreak-prediction**](https://github.com/fabianofilho/datasus-outbreak-prediction) | Integrated epidemiological surveillance: outbreak alerts (z-score, CUSUM, LightGBM), CID-10 co-occurrence graph, supply planning and sanitation × disease map · [live app](https://datasus-outbreak-prediction.streamlit.app) | InfoDengue · SIM · SNIS · IBGE |
| [**datasus-ai-prediction**](https://github.com/fabianofilho/datasus-ai-prediction) | Predictive ML models trained on DATASUS data for clinical and epidemiological outcomes | Python · scikit-learn · XGBoost |
| [**datasus-ai-search**](https://github.com/fabianofilho/datasus-ai-search) | Natural language queries over Brazilian epidemiological data, no SQL needed | Python · LLMs · DuckDB · Streamlit |

### 📈 Evaluation & forecasting

| Project | Description | Stack |
|---------|-------------|-------|
| [**iamed-harness**](https://github.com/fabianofilho/iamed-harness) | Minimal, auditable harness to evaluate LLMs on clinical multiple-choice tasks: run-to-run variance, calibration and semantic perturbations. First command runs offline, no API key | Python · uv |
| [**cardiovascular-timeseries-prediction**](https://github.com/fabianofilho/cardiovascular-timeseries-prediction) | Monthly cardiovascular mortality in São Paulo state (SIM, 2010–2023): SARIMA vs Prophet vs TimesFM vs boosting, rolling-origin backtesting with measured uncertainty | skforecast · TimesFM · SIM |
| [**dengue-timeseries-skforecast**](https://github.com/fabianofilho/dengue-timeseries-skforecast) | Dengue forecasting for 8 Brazilian capitals (InfoDengue, 2010–2024): seasonal naive, SARIMA, Prophet, LightGBM/XGBoost/CatBoost/RF and TimesFM 2.5 zero-shot | skforecast · InfoDengue |
| [**amie-agents**](https://github.com/fabianofilho/amie-agents) | Conversational medical AI assistants inspired by Google DeepMind's AMIE, multi-agent architecture | MedGemma · FastAPI · LangChain |

### 📚 Curated lists & community

| Project | Description |
|---------|-------------|
| [**awesome-medical-ai**](https://github.com/fabianofilho/awesome-medical-ai) | Curated list of Medical AI resources: papers, datasets, tools, pre-trained models, code and competitions, with weekly automated updates |
| [**awesome-health-datasets**](https://github.com/fabianofilho/awesome-health-datasets) | Open datasets in healthcare, medical imaging, clinical data and bioinformatics |
| [**labdaps/labskills**](https://github.com/labdaps/labskills) | Collaborative Claude Code skills for the LABDAPS lab (FSP-USP): ML in health and scientific writing, distributed as plugins |
| [**iamed**](https://github.com/fabianofilho/iamed) | IA.med clinical suite: 8 structured clinical-reasoning templates as a Claude skill |

---

## 📚 Selected Publications

- 📄 **[A bibliometric network analysis of coronavirus during the first eight months of COVID-19](https://scholar.google.com/citations?user=IqVY-BQAAAAJ)** · *IJERPH, 2021* · **106 citations**
- 📄 **Strategies for detecting and mitigating dataset shift in ML for health predictions** · *Journal of Biomedical Informatics, 2025*
- 📄 **Predictive modeling of gestational weight gain: a ML multiclass classification study** · *BMC Pregnancy and Childbirth, 2024*
- 📄 **Multicenter comparative analysis of local and aggregated data in COVID-19 outcome prediction** · *PLOS Digital Health, 2024*

---

## 📊 GitHub Stats

<div align="center">

![Dr. Fabiano's GitHub Stats](https://github-readme-stats.vercel.app/api?username=fabianofilho&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Most Used Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=fabianofilho&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## ✍️ Content & Outreach

- 🧪 **[IA.med](https://app.iamed.cc)** · Curated papers, podcasts, lessons and open tools on AI in medicine, in Portuguese
- 📰 **[Substack — Medicine and Artificial Intelligence](https://fabianofilho.substack.com/)** · Newsletter on fairness, LLMs and generative AI in medicine
- ✍️ **[Medium — dadosesaude](https://fabianonbfilho.medium.com/)** · Educational articles on health data science
- 🌐 **[portfolio.fabianofilho.com](https://portfolio.fabianofilho.com)** · Full portfolio with career, projects and publications

---

<div align="center">

*"Evidence-based medicine, combined with data science, has the power to transform patient care in a personalized and equitable way."*

</div>
