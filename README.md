# Prithivi Raj Mohanta

I build AI tools that read Japanese text, and I measure how well each one works. Below are three projects, each with its data, its numbers and where it falls short.

**Currently (2026-10-25):** studying for JLPT N2 (syllabus started 2026-10-25), taking N2 on 6 Dec 2026; CRM extraction evaluation upgrade in progress.

| Project | What it does | Who it helps | Numbers (from the repo README) |
|---|---|---|---|
| [JP meeting notes → CRM fields](https://github.com/Retro099/jp-meeting-to-crm-fields) | Pulls 5 CRM fields as JSON from Japanese meeting notes with an LLM, with prompt-injection defenses | Sales teams who re-type notes into a CRM | 60.0% exact match (90/150) on 30 synthetic notes; attack success 45% → 6.7% on 40 self-written attacks; 30% → 10% on 20 unseen attacks (1 run) |
| [Credit card fraud detection](https://github.com/Retro099/credit-card-fraud-detection) | XGBoost model that flags fraud when only 0.172% of transactions are fraud, with SHAP explanations | Fraud and risk teams | Recall 0.84, precision 0.88, PR-AUC 0.88 (98 test frauds, single split) |
| [Japanese RAG retrieval eval](https://github.com/Retro099/japanese-rag-eval) | Compares keyword (BM25) and dense (bge-m3) search on a Japanese government white paper | Teams building search or RAG over Japanese documents | hit@5 98%, MRR 0.87 on 42 AI-drafted questions (15 hand-checked) |
