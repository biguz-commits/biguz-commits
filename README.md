# 👋 Hi, I'm Tommaso Biganzoli

**AI Engineer & Backend Developer — LLMs, NLP, Agents & SaaS**

📍 Milan, Italy · 📧 [tommasobiganzoli@gmail.com](mailto:tommasobiganzoli@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/tommaso-biganzoli-055b24244) · [CV](./Tommaso_Biganzoli.pdf)

---

## 🚀 About Me

I design and ship **AI-powered systems** and **scalable SaaS**.
At **Hekanize** I build **LLM agents**, **recommendation engines**, and **microservices** with a strong focus on **evaluation, reliability, and product impact**.

---

## 🧰 Tech Stack (short & sharp)

* **AI/ML**: LLMs, Agentic Workflows, RAG, Transfomers
* **Python**: FastAPI, LangChain/LangGraph, CrewAI, PyTorch/TF, Pandas
* **Backend**: PHP (Laravel), SQL, REST, Redis, GraphQL
* **Cloud/DevOps**: AWS (Bedrock|S3), Docker, GitHub Actions
* **Data**: pgvector, ChromaDB, Matplotlib/Plotly

---

## ⭐ Featured Projects

### 1) Finance Crew — *Market Data → Risk → Insights*

Multi-agent pipeline for **portfolio analytics**: fetches market data, computes **returns, risk & exposures**, and surfaces **actionable metrics** for rebalance/reporting.

* **Highlights**

  * Crews & tools orchestration (researcher + risk analyst flows)
  * Metrics: volatility, beta/correlation, concentration, target vs exposure
  * Clean tool interface for plug-and-play pipelines (data → risk → report)

* **Stack**

  * Python, CrewAI, FastAPI, Pandas, yfinance

* **Quick peek**

  ```bash
  # Run analytics (example)
  uv run python run_fin_crew.py --tickers AAPL,MSFT,SPY --window 365
  ```

> 🔎 Focus: robust **tool design**, clear **interfaces**, and **reusable** risk routines.

---

### 2) Web Scraping Agent — *Data Extraction with Guardrails*

Agentic scraper that retrieves **structured data** from websites with **content filters** ready for analytics or RAG.

* **Highlights**

  * Crawl + parse 
  * Easily pipe results to vector DB or downstream task

* **Stack**

  * Python, LangChain tools, FastAPI

* **Quick peek**

  ```bash
  # Extract structured data from a target URL
  uv run python scrape.py --url https://example.com --schema product
  ```

> 🧱 Focus: **repeatable** scraping with **validations** and **clean contracts** for LLM workflows.

---

### 3) Thesis — *Amazon Reviews Recommender (LLM + BERT + Graph)*

Full pipeline for **product recommendations** using **Amazon Reviews 2023**: embeddings, sentiment/topic signals, **LangGraph agents**, and **vector search** with **ChromaDB/pgvector**.

* **Repo**: [biguz-commits/Thesis](https://github.com/biguz-commits/Thesis)

* **Highlights**

  * BERT embeddings + sentiment for richer item profiles
  * Agentic orchestration (classification → retrieval → generation)
  * Evaluation tracks (precision, hallucination checks, LLM-as-Judge)

* **Quick peek**

  ```bash
  # Demo: semantic retrieval + recommendation
  uv run python recommend.py --query "budget wireless earbuds for running"
  ```

> 🎯 Focus: **quality of retrieval**, **explainability**, and **eval discipline** for LLM recommenders.

---

## 🗂 Repo Guide

* **Finance Crew** → `finance_crew/` (agents, tools, metrics, reports)
* **Web Scraping Agent** → `web_scraping_agent/` (schemas, crawlers, exporters)
* **Thesis** → [`/Thesis`](https://github.com/biguz-commits/Thesis) (end-to-end recsys, evaluation, docs)

> Tip: I keep code **modular** (tools/agents/services) so each piece is easy to reuse across projects.

---

## 📈 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=biguz-commits\&show_icons=true\&theme=tokyonight)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=biguz-commits\&layout=compact\&theme=tokyonight)

---

## 🤝 Let’s Collaborate

I’m open to projects in **AI Engineering, Agents, Recommenders, and Data Products**.
Ping me on [LinkedIn](https://www.linkedin.com/in/tommaso-biganzoli-055b24244) or email **[tommasobiganzoli@gmail.com](mailto:tommasobiganzoli@gmail.com)**.

---

### Notes for Reviewers / Recruiters

* Strong bias toward **production-ready** code and **evaluation-first** mindset
* Comfortable owning **end-to-end**: data, models, API, infra, and CI
* I value **clear interfaces**, **observability**, and **tests** over cleverness

---

