# 📊 Emerging Trends in Software Development

> Synthesizing **90,000+ Stack Overflow survey responses** to map the future of developer technology — using Python & IBM Cognos Analytics.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?logo=pandas&logoColor=white)
![IBM Cognos](https://img.shields.io/badge/IBM%20Cognos-Dashboard-054ADA?logo=ibm&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)

---

## 📌 Project Overview

A data analytics capstone project analyzing the **Stack Overflow Annual Developer Survey** to surface current and emerging technology trends across programming languages, databases, and platforms.

The target audience is technology leaders, hiring managers, and developers looking for evidence-based guidance on skill investment. Findings were delivered as a structured stakeholder report and a multi-tab IBM Cognos Analytics dashboard.

---

## 🗂️ Repository Structure

```
├── notebooks/
│   └── Revenue_Data_and_Building_a_Dashboard.ipynb   # Data wrangling & analysis pipeline
├── report/
│   └── Emerging_Trends.pdf                           # Full presentation / stakeholder report
└── README.md
```

---

## ⚙️ Methodology

### Data Source
Stack Overflow Annual Developer Survey — a self-reported, voluntary survey of professional developers worldwide.

### Data Wrangling Pipeline

| Step | Description |
|---|---|
| **Filtering** | Removed incomplete entries to ensure response quality |
| **Standardization** | Normalized categorical fields for consistent aggregation |
| **Null Handling** | Missing values excluded rather than imputed — preserving survey integrity |
| **Multi-select Explosion** | Multi-answer fields (e.g. "which languages do you use") exploded into individual rows for accurate counting |

### Analysis & Visualization
- Aggregated response counts per technology across current use and desired use dimensions
- Visualized in **IBM Cognos Analytics** across three dashboard tabs: **Current Usage**, **Future Trends**, **Demographics**

---

## 📈 Key Findings

### Programming Languages

| Language | Current Users | Desired Users | Trend |
|---|---|---|---|
| JavaScript | 8,687 | 6,630 | Dominant — lingua franca of web dev |
| Python | #5 currently | #3 desired | Rising fast — driven by AI/ML adoption |
| TypeScript | — | #5 desired | Gaining ground as JS matures at scale |

**Implication:** Python's trajectory makes it the defining language of the data and AI era. TypeScript's rise signals the ecosystem is maturing toward type safety for large-scale applications.

### Databases

| Database | Signal |
|---|---|
| **PostgreSQL** | Jumps from #3 current (4,097) to **#1 desired (4,328)** — generational shift in preference |
| **MongoDB** | #5 current → #2 desired — sustained demand for flexible document stores |
| **Redis** | #6 current → #3 desired — in-memory caching becoming critical infrastructure |

**Implication:** Open-source databases are displacing proprietary options. Cost and flexibility are driving the transition, especially in cloud-native deployments.

### Platforms & Infrastructure

- **Linux, Docker, and AWS** are the top desired platforms — cloud-native skills are no longer optional
- **Google Cloud and Azure** appear prominently alongside AWS in future-desired responses
- **Docker and Kubernetes** adoption will continue accelerating across DevOps teams

### Demographics

- Survey skews **18–34**, male-dominated (93.5%), with bachelor's degrees as the most common qualification
- Useful context for interpreting desired technology signals — this is the next generation of builders

---

## 💡 Actionable Insights

| Audience | Recommendation |
|---|---|
| Tech Recruiters | Prioritize JS/TypeScript and Python skills in hiring pipelines |
| Universities & Bootcamps | Align curricula with PostgreSQL, MongoDB, and cloud tooling |
| DevOps Teams | Plan for continued Docker and Kubernetes adoption |
| Individual Developers | PostgreSQL + Python + any cloud provider is the highest-signal stack to invest in |

---

## 🛠️ Tech Stack

- **Python 3** — Pandas, Jupyter Notebook
- **IBM Cognos Analytics** — Multi-tab interactive dashboard
- **Stack Overflow Developer Survey** — Public dataset

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/emerging-trends-software.git
cd emerging-trends-software
pip install pandas numpy matplotlib jupyter
jupyter notebook notebooks/Revenue_Data_and_Building_a_Dashboard.ipynb
```

---

## 🔗 Links

- 🌐 [Portfolio — egemenerin.com](https://www.egemenerin.com)
- 📊 [IBM Cognos Dashboard](#) *(link to published dashboard)*
- 📧 egemeneriin@protonmail.com

---

## 👤 Author

**Egemen Erin** — Data Analyst  
IBM Data Analytics Capstone | *July 2025*
