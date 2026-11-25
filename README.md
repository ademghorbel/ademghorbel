<div align="center">

```
 █████╗ ██████╗  █████╗ ███╗   ███╗
██╔══██╗██╔══██╗██╔══██╗████╗ ████║
███████║██║  ██║███████║██╔████╔██║
██╔══██║██║  ██║██╔══██║██║╚██╔╝██║
██║  ██║██████╔╝██║  ██║██║ ╚═╝ ██║
╚═╝  ╚═╝╚═════╝ ╚═╝  ╚═╝╚═╝     ╚═╝
```

### Mohamed Adam Ghorbel
**Data Engineering & AI Systems · ENET'Com Sfax, Tunisia**

*Building agents that reason, pipelines that scale, and systems that decide.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mohamed--adam--ghorbel-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/mohamed-adam-ghorbel/)
[![Portfolio](https://img.shields.io/badge/Portfolio-MAG-111111?style=flat-square&logo=githubpages)](https://ademghorbel.github.io/MAG/)
[![Email](https://img.shields.io/badge/Email-adam.ghorbel510@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:adam.ghorbel510@gmail.com)

</div>

---

## About

Final-year Data Engineering & Decision Systems (IDSD) student at ENET'Com Sfax, graduating September 2027. My work sits where **data pipelines** meet **AI agents**: from raw data ingestion to autonomous systems that take real decisions. Three internships so far, with work that runs in production, not just demos.

**Looking for a six-month end-of-studies internship (PFE) from February 2027** in data engineering, agentic AI or multimodal AI, in Tunisia or abroad.

---

## Projects

### 📄 DocAgent: Agentic Multimodal RAG for Technical Manuals
> *LangGraph · ColQwen · Qwen2.5-VL · FAISS · Gradio · Python*

When a machine raises an alert, DocAgent reads the equipment's manuals (text, tables and diagrams) and returns a sourced diagnosis with links to the exact pages. It runs on-premise with open-weight models (Qwen2.5-VL-7B, 4-bit, free Kaggle T4).

Benchmarked against text RAG, direct VLM and ColQwen page-image RAG on **184 questions**: **+8.7 points** over the best baseline on long single documents (MMLongBench-Doc), **91%** on the in-house drive-manual questions, and **21 of 23** unanswerable questions correctly refused. It still trails page-image RAG on whole-corpus search, which is documented in the analysis.

[![Repo](https://img.shields.io/badge/View_Repo-DocAgent-0ea5e9?style=flat-square&logo=github)](https://github.com/ademghorbel/DocAgent)

---

### 🔁 Boomi Daily Monitoring: n8n Automation *(OliveSoft internship)*
> *n8n · Boomi AtomSphere API · Python · Docker*

Replaced a two-hour manual morning report on **22 production integration flows** for a luxury-fashion client with an n8n workflow that rebuilds and sends the exact same email. Validated row by row against real reports (22/22 rows, 0 mismatches) after analysing **27,897 execution records** across 34 processes.

[![Repo](https://img.shields.io/badge/View_Case_Study-Boomi_Monitoring-f97316?style=flat-square&logo=github)](https://github.com/ademghorbel/boomi-daily-monitoring)

---

### 🏛️ LegacyLens: Multi-Agent Legacy Code Analysis *(Talan internship)*
> *LangGraph · LangChain · Gemini · FastAPI · Streamlit*

A multi-agent pipeline that routes COBOL, VB6, Fortran and modern code to specialised agents, groups the analysis into RFP-ready business modules, draws Mermaid architecture and class diagrams, and lets you chat with the codebase. Built the code analyser and module aggregation agents at Talan, then extended it as open source.

[![Repo](https://img.shields.io/badge/View_Repo-LegacyLens-8b5cf6?style=flat-square&logo=github)](https://github.com/ademghorbel/LegacyLens)

---

### ⚡ VoltWise: Solar Forecasting + AI Battery Agent
> *XGBoost · Streamlit · Open-Meteo · OpenRouter · Python*

An XGBoost model trained on real PV plant data from Sfax predicts solar output for the next 48 hours from live weather (R²=0.77, MAE=0.26 kW), averaging four forecast models for steadier inputs. An LLM agent then decides battery actions (**CHARGE**, **DISCHARGE** or **MAINTAIN**). Ranked **4th at the IEEE TSYP 13** PES & YP & Spectra Technical Challenge.

[![Repo](https://img.shields.io/badge/View_Repo-VoltWise-22c55e?style=flat-square&logo=github)](https://github.com/ademghorbel/VoltWise)

---

### More
- **[Memo](https://github.com/ademghorbel/memo)**: a tiny desktop buddy that keeps your AI assistant's markdown memory notes tidy
- **[MAG](https://github.com/ademghorbel/MAG)**: my portfolio site, vanilla JS + GSAP, covering both my data work and my graphic design

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Data Engineering**

![Data Vault 2.0](https://img.shields.io/badge/Data_Vault-2.0-0f766e?style=flat-square)
![Medallion](https://img.shields.io/badge/Medallion-Lakehouse-b45309?style=flat-square)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Boomi](https://img.shields.io/badge/Boomi-0B3D91?style=flat-square)

**AI & Agents**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B35?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Multimodal-0ea5e9?style=flat-square)
![OpenRouter](https://img.shields.io/badge/OpenRouter-000000?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Protocols & Infra**

![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-6366f1?style=flat-square)
![A2A](https://img.shields.io/badge/A2A-Agent_to_Agent-ec4899?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Design**

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square&logo=adobephotoshop&logoColor=white)
![Illustrator](https://img.shields.io/badge/Illustrator-FF9A00?style=flat-square&logo=adobeillustrator&logoColor=white)

---

## Experience

**AI Automation Intern, OliveSoft** *(Jun 2026 to Aug 2026)*
Built a daily n8n monitoring automation for 22 Boomi integration flows of a live client, cutting manual review by up to two hours a day. Also forecast seven-day load-shedding risk in Tunisia for an internal hackathon, backtested on real STEG notices.

**Agentic AI Engineering Intern, Talan** *(Jul 2025 to Aug 2025)*
Built the code analyser and module aggregation agents of LegacyLens, a LangGraph multi-agent system, and co-built the team's A2A agent communication.

**UI/UX Design Intern, DK Soft** *(Jun 2025 to Jul 2025)*
Redesigned the visual identity of the ForsaTaw mobile app and the Itech University web portal in Figma, Photoshop and Illustrator.

**Smart Manager, MOMSoft (PFA)** *(Nov 2025 to Apr 2026)*
Designed a Medallion lakehouse (Bronze, Silver, Gold) unifying IoT, PLC, ERP and HR data, with Data Vault 2.0 modeling for full historical traceability. The proof of concept went into production with several industrial clients.

---

## Education

**ENET'Com Sfax**: Engineering Degree in Data Engineering & Decision Systems (IDSD)
*Sep 2024 to Sep 2027 (expected)*

**IPEIS Sfax**: Preparatory Cycle, Mathematics and Physics
*Sep 2022 to Jun 2024*

---


<div align="center">

*Open to PFE opportunities, research collaborations, and ambitious projects.*

**adam.ghorbel510@gmail.com · +216 50 367 500**

</div>
