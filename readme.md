# AI-Finance Portfolio – Thomas Le Joubioux

**Applying Machine Learning to Corporate Finance, Credit Risk, Energy Transition & Strategic Advisory**

![1766844119907](https://github.com/user-attachments/assets/eae1887c-5f5f-484a-b4c6-1e41c87b45ba)

## Overview

Collection of applied ML projects bridging **20+ years of corporate finance, investment control, due diligence, private equity and energy project leadership** with modern machine learning.

Focus areas:
- **Explainable AI** for credit & investment risk (SHAP, interpretability for regulated environments)
- **Renewables & energy forecasting** (time-series ML for solar production, CAPEX/OPEX optimisation)
- **Privacy-first GenAI** for strategic advisory (local LLM deployment, RAG on governance/risk data)

All projects emphasize **business impact**, **robustness**, and **explainability** — aligned with ECB/EBA standards, board-level decision-making, and energy transition goals (REPowerEU, Net Zero).

## Featured Projects

| Project | Description | Key Technologies | Business Relevance | Status |
|---------|-------------|------------------|--------------------|--------|
|Machine learning model forecasting French national onshore wind power production using ENTSO-E data and meteorological features.| Python, Pandas, ENTSO-E API, Open-Meteo, Feature Engineering, LightGBM, XGBoost | Time-series model improving day-ahead wind generation forecasts for grid and energy market operations.| Completed – validated on 2015–2025 historical data -|
| Corporate Credit Risk Modeling | Default prediction on 80k+ Nasdaq/NYSE firm-years. SHAP reveals industry & profitability drivers (majorgroup, EBIT, retained earnings). | LightGBM, Random Forest, SMOTE, SHAP | Due diligence, PE screening, governance (LJ Advisory, Global Equity) | Active – Notebook + SHAP plots [Code](https://github.com/globaltom-git/corporate-credit-risk-modeling) | 
| Solar Production Forecasting | Hourly solar output prediction for Europe (France focus). ENTSO-E + Open-Meteo data, time-series features. | XGBoost, Pandas, cyclical encoding, rolling stats | Time-series model improving day-ahead solar generation forecasts for grid and energy market operations. | Active – API integration [Code](https://github.com/globaltom-git/France-7-days-solar-production-forecast-) |
| Legal Due Diligence Automation | Clause & risk extraction from M&A data rooms (PDF/DOCX/TXT). Detects key red flags (change of control, unlimited liability, governing law). | TF-IDF + KMeans clustering, multilingual embeddings, NLTK, sentence-transformers| Accelerates legal due diligence in M&A deals; cuts review time by 80 %; fully transparent & local (no external LLM) | Ready-to-run (tested on real data room)
| Financial Statement Analytics with ML | Applied ML to real P&L financials of a road transport group, revealing actionable insights and hidden patterns while comparing and improving method performance. | Clustering, Regression, unsupervised patterns | Real-world financial analysis, operational efficiency insights (transport/logistics sector) | Completed – Jan 2026 |
| Local LLM Advisory Lab | Secure, privacy-first LLM deployment for financial & strategic advisory (RAG on governance risks, consortium docs). | Ollama/Mistral, LlamaIndex, prompt engineering | RGPD-compliant advisory, risk governance (publication: "Du risque de gouvernance en consortium") | Active – Proof-of-concept |

## Why This Portfolio?

- **From traditional finance to AI-augmented** — fusing international M&A, energy transition, and ML for measurable value.
- **Senior perspective** — not just code, but linkage to real-world outcomes (due diligence, project finance, board reporting).
- **Explainable & regulated-ready** — SHAP, robustness testing, business context for stakeholders in banking, PE/VC, energy, advisory.

## Technologies Stack

- Python 3.11+
- ML: scikit-learn, LightGBM, XGBoost, SHAP
- Data: Pandas, NumPy
- GenAI: Ollama, LlamaIndex/Mistral
- Viz: Matplotlib, Seaborn
- Environment: JupyterLab, virtualenv

## Contact & Connections

Open to collaborations, advisory roles, or discussions in:
- AI for credit/investment risk
- Renewables forecasting & energy finance
- Privacy-first GenAI in strategic advisory

- LinkedIn: [Thomas Le Joubioux](https://www.linkedin.com/in/thomas-le-joubioux-financial-business-advisory)
- Email: contact@lj-avisory.com
- Location: Greater Paris Metropolitan Region

Feedback, issues, or forks welcome!

Last updated: January 2026
