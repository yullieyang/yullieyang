# Hi, I'm Yullie 👋

**Quantitative analyst** building reproducible financial / economic research workflows and AI-assisted QA / documentation systems. I work at the intersection of **economics, data, and engineering** — turning macro and financial data into versioned, reviewable, decision-ready artifacts.

- 💼 **Quantitative Analyst**, CoStar Group — Boston, MA (2025 – Present)
- 🧪 **Data Scientist / Consultant**, Guidehouse — McLean, VA (2024 – 2025)
- 🏛 **Graduate Intern** (Summer 2023), **Board of Governors of the Federal Reserve System** — Division of International Finance
- 🎓 M.S. Business Analytics, **University of Maryland, College Park** (Dec 2023)
- 🌏 B.A. Global Political Economy, **Waseda University**, Tokyo (2022)
- 📍 Boston, MA

## What I'm focused on

Production-style research-support code: pulling macro / trade / commodity series from authoritative sources (FRED), harmonizing across frequencies, computing derived measures, producing short-horizon forecasts with documented uncertainty, and using AI coding tools responsibly to make recurring QA, code review, and documentation workflows more systematic — packaged so a reviewer can audit every step from Git.

## Featured work

| Repo | What it is |
|---|---|
| **[r-macro-trade-commodity-forecast](https://github.com/yullieyang/r-macro-trade-commodity-forecast)** | Reproducible R pipeline: 13 FRED macro / trade / commodity series → quarterly panel with implicit trade deflators and terms of trade → 8-quarter `auto.arima` forecasts for net exports, real GDP, and WTI → distributed-lag FX pass-through regression on U.S. trade prices. CI + Quarto Pages dashboard. |
| **[cre_stress_test](https://github.com/yullieyang/cre_stress_test)** | Portfolio-demo stress-testing workflow on 100% public data (FRED + Google Mobility + Boston Zoning). Python package + R/auto.arima companion + SQLAlchemy persistence + Streamlit dashboard. pytest + CI. Personal project; does not reflect any employer's internal data or models. |
| **[llm-research-workflow-assistant](https://github.com/yullieyang/llm-research-workflow-assistant)** | Prompt templates, sample outputs, and a human-in-the-loop checklist for using AI coding tools responsibly in recurring research workflows (data QA, code review, brief review, documentation drafting). |
| **[yullieyang.github.io](https://yullieyang.github.io)** | Personal portfolio site (R Markdown + GitHub Pages) with bio, featured projects, and early coursework write-ups. |
| **[cardnews](https://github.com/yullieyang/cardnews)** | Applied LLM tooling demo: Claude API + Puppeteer renders a topic into a 10-slide 1080×1080 visual deck. |

## Toolbox

- **Languages:** R (primary), Python, SQL
- **Data & infra:** FRED, SQLite / PostgreSQL / SQLAlchemy, AWS, Azure, Tableau, Power BI
- **Engineering:** Git, GitHub Actions, R Markdown / Quarto, Streamlit, `make`-driven pipelines, pytest, `testthat`
- **Modeling:** ARIMA / `auto.arima`, distributed-lag regression, classification under class imbalance, SHAP explainability
- **AI / LLM workflows:** Claude API, Claude Code for pair-programming and documentation, prompt-template design, human-in-the-loop review processes

## How I use AI tools

I treat AI coding tools as collaborators on boilerplate, refactoring, and documentation — not as substitutes for analyst judgment. Every repo here that uses an LLM in its workflow includes a `CLAUDE.md` defining how the model should behave, a clear human-review step before outputs are shared, and explicit limitations of what the AI-assisted output represents.

## Contact

📬 [yullieyang@gmail.com](mailto:yullieyang@gmail.com)  ·  🌐 [yullieyang.github.io](https://yullieyang.github.io)  ·  💼 [LinkedIn](https://linkedin.com/in/yullie-yang)
