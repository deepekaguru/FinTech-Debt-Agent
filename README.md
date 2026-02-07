# FinTech-Debt-Agent


An Agentic AI Financial Advisor built to help users navigate debt repayment using real-world market benchmarks. This system utilizes a multi-agent orchestration layer to transform messy financial statements into structured, actionable payoff plans.

**Core Features**

Structured Financial Extraction: Uses LLMs with constrained output to parse debt details (APR, balance, institution) from natural language.

Market-Aware RAG: Integrates the 2025 CFPB Consumer Credit Card Market Report to benchmark user interest rates against national averages.

Autonomous Orchestration: Built with LangGraph to manage state and route logic between specialized Analyst, Researcher, and Nudger agents.

Deterministic Math Tools: Implements Debt Snowball and Debt Avalanche algorithms in pure Python to ensure 100% mathematical accuracy.

**Technical Stack**

Framework: LangGraph / LangChain

LLM: OpenAI GPT-4o

Data Processing: Pandas (for Macro-Enabled Excel parsing)

Database: ChromaDB (Vector Store for RAG)

Frontend: Streamlit
