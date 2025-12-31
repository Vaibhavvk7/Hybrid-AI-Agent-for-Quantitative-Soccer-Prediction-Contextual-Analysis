# Hybrid-AI-Agent-for-Quantitative-Soccer-Prediction-Contextual-Analysis

A Hybrid AI Agent for Quantitative Football Prediction & Contextual Analysis

A two-stage AI system that combines statistical modeling with real-time contextual reasoning to generate professional-grade football match analyses. Instead of relying solely on historical data or black-box predictions, this system fuses machine learning with live web intelligence to deliver transparent, explainable insights.

**🚀 Key Capabilities**

**🧠 Dual-Engine Intelligence**
Uses a fast XGBoost model for probabilistic match prediction, enhanced by a context-aware LLM layer for qualitative reasoning.

**🌐 Real-Time RAG Pipeline**
Retrieves live data including injuries, form, news, and head-to-head stats via multi-source web search and full-text enrichment.

**📊 Structured, Explainable Output**
Produces analyst-style reports covering model agreement, conflicts, market efficiency, and risk assessment.

**💾 Persistent Analytics Logging**
All predictions and LLM analyses are stored in Supabase, enabling traceability and post-match evaluation.

**🕹️ Interactive Interface**
Gradio-based UI allows users to seamlessly move from raw odds to deep analytical insights.

**🧩 System Workflow**

**Stage 1: Statistical Prediction**

User inputs match odds
XGBoost model outputs win/draw probabilities
Prediction is logged with a unique session ID

**Stage 2: Contextual Deep Dive**
RAG pipeline generates targeted search queries
Live web data is retrieved and fully parsed
LLM synthesizes statistical + contextual inputs
Final structured report is generated and stored

**🛠️ Technology Stack**

| Layer     | Tools                                         |
| --------- | --------------------------------------------- |
| ML & AI   | XGBoost, Scikit-learn, Google Gemini          |
| Backend   | Python, Pandas, NumPy                         |
| Retrieval | Tavily, Google CSE, DuckDuckGo, BeautifulSoup |
| Database  | Supabase                                      |
| Frontend  | Gradio                                        |
