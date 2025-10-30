# 👋 Hi, I'm Tommaso Biganzoli

**AI Engineer & Backend Developer — LLMs, NLP, Agents & SaaS**

📍 Milan, Italy · 📧 [tommasobiganzoli@gmail.com](mailto:tommasobiganzoli@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/tommaso-biganzoli-055b24244) · [CV](./Tommaso_Biganzoli.pdf)

---

## 🚀 About Me

I design and ship **AI-powered systems** and **scalable SaaS**.
At **Hekanize** I build **LLM agents**, **recommendation engines**, and **microservices** with a strong focus on **evaluation, reliability, and product impact**.

---

## ⚡ Tech Stack  

**🧠 AI / ML**  
![LLMs](https://img.shields.io/badge/LLMs-000000?logo=openai&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-000000?logo=chainlink&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-5A5A5A?logo=graph&logoColor=white) ![CrewAI](https://img.shields.io/badge/CrewAI-FF6B6B?logo=robotframework&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-2E8B57?logo=knowledgebase&logoColor=white) ![Transformers](https://img.shields.io/badge/Transformers-FFD700?logo=huggingface&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)

**🐍 Languages & Python Ecosystem**  
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=plotly&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white)

**🧩 Backend**  
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white) ![GraphQL](https://img.shields.io/badge/GraphQL-E10098?logo=graphql&logoColor=white) ![REST API](https://img.shields.io/badge/REST-005571?logo=fastapi&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white)

**☁️ Cloud & DevOps**  
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white) ![Bedrock](https://img.shields.io/badge/Bedrock-FF9900?logo=amazonaws&logoColor=white) ![S3](https://img.shields.io/badge/S3-569A31?logo=amazons3&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

**🗄️ Data & Storage**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-0064A5?logo=postgresql&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-000000?logo=chromadb&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?logo=duckdb&logoColor=black) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-323330?logo=python&logoColor=white)

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



## 🤝 Let’s Collaborate

I’m open to projects in **AI Engineering, Agents, Recommenders, and Data Products**.
Ping me on [LinkedIn](https://www.linkedin.com/in/tommaso-biganzoli-055b24244) or email **[tommasobiganzoli@gmail.com](mailto:tommasobiganzoli@gmail.com)**.

---

### Notes for Reviewers / Recruiters

* Strong bias toward **production-ready** code and **evaluation-first** mindset
* Comfortable owning **end-to-end**: data, models, API, infra, and CI
* I value **clear interfaces**, **observability**, and **tests** over cleverness

---

## 🎧 When I Debug, I Listen To...

<a href="https://open.spotify.com/playlist/37i9dQZF1DZ06evO1lPLb3" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/19/Spotify_logo_without_text.svg" width="28" alt="Spotify Logo" />
  <b> Peggy Gou </b>
</a>



