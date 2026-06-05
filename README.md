# Hi, I'm Hong-Yun (Steven) Chang 👋

**Data Scientist / ML Engineer** who ships ML as *systems*, not notebooks — with a bias for
honest measurement, leakage-free evaluation, and models that survive contact with production.

🎓 Master of Data Science @ Monash University &nbsp;·&nbsp; 📍 Melbourne, VIC &nbsp;·&nbsp; 🔍 Open to Data Scientist / ML Engineer roles &nbsp;·&nbsp; 📬 ste057770@gmail.com

---

## What I care about (and what my repos demonstrate)

- **No leakage, by test.** Point-in-time feature stores and unit-tested label alignment — not
  backtests that quietly peek at the future. *(see [stock-etl-pipeline](https://github.com/steven-ml-ds/stock-etl-pipeline))*
- **No training/serving skew, by construction.** Batch and streaming share one feature module
  and one persisted pipeline, with a skew regression test in CI. *(see [building-energy-spark-pipeline](https://github.com/steven-ml-ds/building-energy-spark-pipeline))*
- **Scores become decisions.** Calibration, cost-sensitive thresholds, and value-weighted
  prioritisation — so a model's output maps to an action and an ROI. *(see [customer_churn_prediction](https://github.com/steven-ml-ds/customer_churn_prediction))*
- **Honest results.** I report when the simple baseline wins and when going neural doesn't pay —
  measurement I'd trust enough to act on.

---

## 🛠️ Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Machine Learning**  
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat&logo=xgboost&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![SHAP](https://img.shields.io/badge/SHAP-1A5276?style=flat)

**Data & MLOps**  
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**Visualisation**  
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Shiny](https://img.shields.io/badge/R%20Shiny-276DC3?style=flat&logo=r&logoColor=white)

---

## 📂 Featured Projects

Each repo opens with an **Impact / Decision** section — the question, the decision it drives, and what it's worth — before the implementation detail.

| Project | What it shows | Tech |
|---------|---------------|------|
| [**stock-etl-pipeline**](https://github.com/steven-ml-ds/stock-etl-pipeline) | A leakage-free quant **evaluation rig**: point-in-time features (tested), as-of S&P 500 membership, walk-forward IC vs baselines after costs. Honest ≈0-IC result, cleanly measured. | Airflow, MongoDB, MinIO, DuckDB, Docker |
| [**building-energy-spark-pipeline**](https://github.com/steven-ml-ds/building-energy-spark-pipeline) | Batch ML **+** real-time streaming forecasting that **eliminates training/serving skew by construction** — one shared feature module, one persisted pipeline, skew regression test in CI. | PySpark, Kafka, Docker |
| [**customer_churn_prediction**](https://github.com/steven-ml-ds/customer_churn_prediction) | Business churn case study: cost-sensitive thresholds, SHAP, Platt calibration (ECE 0.16→0.02), CLV-weighted retention prioritisation, FastAPI serving. | scikit-learn, XGBoost, SHAP, FastAPI |
| [**nlp-intent-slot-filling**](https://github.com/steven-ml-ds/nlp-intent-slot-filling) | Four-model SLU on ATIS (LogReg/CRF/BiLSTM-CRF/**JointBERT**) with seed-backed results and an honest error analysis — JointBERT: slot F1 0.954, intent acc 0.976. | PyTorch, BERT, CRF |
| [**arxiv-rag**](https://github.com/steven-ml-ds/arxiv-rag) *(WIP)* | Personal RAG chatbot over arXiv AI/ML papers — ingestion → embeddings → retrieval → chat API. | Python, FastAPI, embeddings, LLM |
| [**australian-property-market-spark**](https://github.com/steven-ml-ds/australian-property-market-spark) | NSW property analysis comparing RDD vs DataFrame vs Spark SQL with partitioning strategies. | PySpark, Spark SQL |
| [**australia-tourism-dashboard**](https://github.com/steven-ml-ds/australia-tourism-dashboard) | Interactive tourism-trends dashboard with Leaflet maps and Plotly charts. | R, Shiny, Leaflet |

---

## 📊 GitHub

![Steven's GitHub stats](https://github-readme-stats.vercel.app/api?username=steven-ml-ds&show_icons=true&hide_border=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=steven-ml-ds&layout=compact&hide_border=true)
