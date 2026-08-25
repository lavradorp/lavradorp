Hi, my name is Pedro Lavrador and welcome to my profile!

Data Engineer experienced in translating complex financial business rules, such as fixed income (CDB, LF, CDI), Receivables Funds, credit and derivatives, into scalable, reliable data pipelines. I build that foundation with ETL/ELT, process orchestration and large-scale data processing.

Alongside that, I'm continuously building a Machine Learning Engineering portfolio, including LLM-based projects (RAG, agents) and ML model benchmarking.

🛠️ Stack

**Languages**: Python, SQL

**Data Engineering**: Pandas, Polars, Apache Airflow, ETL/ELT

**Machine Learning & AI**: Scikit-learn, LangChain, LangGraph, VectorDBs

**Backend & APIs**: FastAPI

**Infrastructure & Architecture**: AWS, Git/GitHub, Docker, BigQuery, Clean Architecture

**Business**: Fixed Income Products, Receivables Funds, Credit, Derivatives


🚀 **Projects**

🤖 **Agent Factory**

A framework for RAG agent built on LangGraph, with every component swappable via YAML.

-**Problem**: LLM agent stacks usually hard-code their provider choices, so swapping an LLM, embeddings, vector store or checkpointer means rewriting application code.

-**Solution**: A pluggable architecture where each component is declared in YAML and resolved at runtime.

-**Key Tech**: Builder, Strategy/Factory/Registry, Facade and Decorator patterns, with Pydantic schema validation and lazy imports, so only the provider your config selects pays its startup cost.


📊 **Gradient Boosting Benchmark**

A reproducible benchmark comparing XGBoost, LightGBM and CatBoost on statistical and computational trade-offs.

-**Problem**: Framework comparisons usually report accuracy alone, ignoring the training time and memory cost that decide what actually ships to production.

-**Solution**: A controlled benchmark running 30 independent executions per model under an identical preprocessing pipeline and data split, reporting mean and standard deviation alongside MAE, RMSE and R².

-**Key Achievement**: Found that averaging RSS deltas across runs decays as 1/N instead of converging, making the memory metric meaningless, so switched to peak allocation, which exposed memory gap between frameworks that the average had hidden.
