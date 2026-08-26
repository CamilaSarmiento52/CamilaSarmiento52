# Data Scientist | LLM Pipelines & Predictive Modeling | Python

I build AI systems that turn business problems into measurable outcomes. Data Scientist and AI Engineer with 8+ years of experience across private and research sectors. I move between modern LLM systems and classical ML: RAG assistants, LLM agents, document extraction pipelines, and predictive models.

---

## What I build

**🤖 RAG assistants & LLM agents**
Chat assistants over your documents that answer with citations you can check. I build the retrieval (hybrid search over Postgres/pgvector), the agent logic (LangGraph), and the evaluation (RAGAS golden sets, Langfuse tracing), so quality is measured and every change can be tested.

**🎯 LLM pipelines & structured extraction**
Turn unstructured documents (reports, PDFs, clinical notes) into clean, validated, structured data ready for downstream analytics.

**⚡ Predictive modeling & forecasting**
ML models for demand forecasting, risk estimation, and classification problems.

**🔬 Computer vision & medical imaging AI**
Deep learning pipelines for image classification and clinical outcome prediction, including explainability outputs for clinical and research teams.

**🛠️ End-to-end ML systems**
Full pipeline ownership from raw data to deployed model — ETL, feature engineering, model training, evaluation, and monitoring.

---

## Results

📌 Built a RAG assistant for contract clause research over 40 SEC material contracts: LangGraph agent, hybrid pgvector + full-text retrieval, and a code-level validation step that checks every citation against the retrieved text before the answer is shown to the user. Evaluated with RAGAS on a golden set of 40 hand-verified cases: 0 fabricated citations, 0.97 faithfulness on single-document questions. Deployed on Cloud Run with Langfuse tracing on every turn.

📌 Built an agentic receipt-capture and expense-splitting system: a Telegram bot sends the receipt photo to a vision model, extracts the line items, asks the user to confirm each one, and writes the result to Supabase, Google Sheets, and Gmail. 

📌 Built a computational pathology pipeline predicting treatment response from H&E whole slide images using vision foundation models — AUC 0.788 on an 18-patient cohort, establishing proof of concept for a larger prospective study.

📌 Designed an LLM extraction pipeline to structure clinical information from oncology pathology reports — 0.88 accuracy across three cancer types, benchmarked against multiple open-source biomedical models. Manual data entry for cancer registries is a known bottleneck in clinical workflows; a pipeline like this has the potential to significantly reduce that burden, freeing clinical staff for higher-value tasks and improving data consistency across registries.

📌 Improved demand forecasting accuracy by 5% for manufacturing components using LightGBM, reducing exposure to contractual penalties tied to production shortfalls.

---

## How I work

✅ I start by understanding the business problem — what decision the output needs to support, what the data actually looks like, and what success means in your context.

✅ I work in structured phases: problem definition, data exploration, modeling, evaluation, and delivery. You know where we are at every stage.

✅ I communicate proactively — you get updates at each milestone and relevant decisions or changes are communicated as they arise.

✅ I deliver documented, working code your team can maintain and build on.

---

I hold a BSc in Mathematics, an MSc in Data Science, and I am currently a PhD researcher in Data Science at NOVA IMS in collaboration with the Champalimaud Foundation, one of Europe's leading biomedical research centres. My work spans insurance, telecoms, IT, and biomedical research. Different industries bring different ways of framing problems, and that range of experience shapes how I approach new ones.
