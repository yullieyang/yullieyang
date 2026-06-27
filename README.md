# Hi, I'm Yullie 👋

**Data scientist** working on experimentation, machine learning, and AI / LLM systems — defining metrics, designing and analyzing A/B tests, and evaluating whether models (statistical or LLM-based) are reliable enough to ship. Background in regulated, high-stakes settings including the **Federal Reserve Board**, with a focus on rigor, calibration, and reproducibility.

- 💼 **Quantitative Analyst**, CoStar Group — Boston, MA (2025 – Present)
- 🧪 **Data Scientist / Consultant**, Guidehouse — McLean, VA (2024 – 2025)
- 🏛 **Graduate Intern** (Summer 2023), **Board of Governors of the Federal Reserve System** — Division of International Finance
- 🎓 Master of Applied Science in Computer Science, **University of Pennsylvania** (in progress)
- 🎓 M.S. Business Analytics, **University of Maryland, College Park** (December 2023)
- 🌏 B.A. Global Political Economy, **Waseda University**, Tokyo (September 2022)
- 📍 San Francisco Bay Area

## What I'm focused on

Experimentation, evaluation, and applied AI: designing and analyzing A/B tests (North Star metrics, power / MDE, CUPED variance reduction, guardrails); building and evaluating LLM and agentic AI systems for reliability, calibration, and evidence grounding with human-in-the-loop review; and reproducible Python / SQL analysis that is auditable end to end. The question I care about most — whether a model, statistical or LLM-based, actually does what it claims.

## Featured work

| Repo | What it is |
|---|---|
| **[agentic-ai-evaluation-platform](https://github.com/yullieyang/agentic-ai-evaluation-platform)** | Reproducible study of LLM-based QA agents on synthetic model-monitoring anomaly review: 15 labelled scenario types, a deterministic rule baseline, a schema-constrained agent + reviewer agent, four prompt conditions, and evaluation spanning precision/recall, confidence calibration (ECE, Brier), unsupported-claim analysis, and paired statistical testing (McNemar, permutation, Benjamini–Hochberg). Streamlit research dashboard; runs fully offline via a deterministic mock provider; 54 passing tests. Synthetic data. |
| **[product-ab-experiment](https://github.com/yullieyang/product-ab-experiment)** | End-to-end A/B test on 100K simulated users: North Star metric + guardrails, sample-ratio-mismatch trust check, two-proportion z-test, power/MDE, CUPED variance reduction, Bonferroni-corrected segmentation, ship/no-ship decision memo, and an ARIMA monitoring forecast. Reproducible synthetic data with an embedded ground-truth effect. |
| **[r-macro-trade-commodity-forecast](https://github.com/yullieyang/r-macro-trade-commodity-forecast)** | Reproducible R pipeline: 13 FRED macro / trade / commodity series → quarterly panel with implicit trade deflators and terms of trade → 8-quarter `auto.arima` forecasts for net exports, real GDP, and WTI → distributed-lag FX pass-through regression on U.S. trade prices. CI + Quarto Pages dashboard. |
| **[cre_stress_test](https://github.com/yullieyang/cre_stress_test)** | Portfolio-demo stress-testing workflow on 100% public data (FRED + Google Mobility + Boston Zoning). Python package + R/auto.arima companion + SQLAlchemy persistence + Streamlit dashboard. pytest + CI. Personal project; does not reflect any employer's internal data or models. |
| **[llm-research-workflow-assistant](https://github.com/yullieyang/llm-research-workflow-assistant)** | Prompt templates, sample outputs, and a human-in-the-loop checklist for using AI coding tools responsibly in recurring research workflows (data QA, code review, brief review, documentation drafting). |
| **[model-output-qa-dashboard](https://github.com/yullieyang/model-output-qa-dashboard)** | Streamlit dashboard for quarterly model-release QA: compares prior vs. current model-output extracts, runs fixed checks (missing values, duplicate keys, schema drift, out-of-range, scenario coverage), computes row-level deltas, and exports a Markdown review report with a human-reviewer checklist. Synthetic data. |
| **[yullieyang.github.io](https://yullieyang.github.io)** | Personal portfolio site (GitHub Pages) — bio, background, and featured projects. |

## Toolbox

- **Languages:** Python, R, SQL
- **Data & infra:** SQLite / PostgreSQL / SQLAlchemy, AWS, Azure, Power BI, Tableau, FRED
- **Engineering:** Git, GitHub Actions, Streamlit, `make`-driven pipelines, pytest, R Markdown / Quarto
- **Experimentation:** A/B testing, North Star / guardrail metric design, power / MDE analysis, CUPED variance reduction, confidence calibration (ECE, Brier)
- **Modeling:** classification under class imbalance, SHAP explainability, ARIMA / `auto.arima`, distributed-lag regression
- **AI / LLM:** LLM & RAG evaluation, agentic workflows, prompt experimentation, human-in-the-loop systems, retrieval-quality analysis, LangChain, LangGraph, Claude API, Claude Code

## How I use AI tools

I treat AI coding tools as support for scaffolding, refactoring, and documentation review — not as substitutes for analyst judgment. Analytical logic, assumptions, validation checks, and final outputs are independently verified. Every repo that uses an LLM in its workflow includes a `CLAUDE.md` defining how the model should behave, a clear human-review step before outputs are shared, and explicit limitations of what the AI-assisted output represents.

## Contact

📬 [yullieyang@gmail.com](mailto:yullieyang@gmail.com)  ·  🌐 [yullieyang.github.io](https://yullieyang.github.io)  ·  💼 [LinkedIn](https://linkedin.com/in/yullie-yang)
