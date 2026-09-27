# 🔬 ResearchMind — AI Research Agent

A multi-agent AI system that collaborates to deliver polished research reports on any topic.

**Four specialized AI agents:**
1. **Search Agent** — Gathers top web results via DuckDuckGo
2. **Reader Agent** — Scrapes & extracts deep content from URLs
3. **Writer Chain** — Drafts structured research reports
4. **Critic Chain** — Reviews & scores the report

## Tech Stack
- **Streamlit** — Frontend UI
- **LangChain** — Agent orchestration
- **Groq** (Llama 3.1) — Fast, free cloud LLM
- **DuckDuckGo** — Web search
- **BeautifulSoup** — Web scraping

## Setup

1. Get a free API key from [Groq Console](https://console.groq.com/)
2. Set `GROQ_API_KEY` in Streamlit secrets or `.env`
3. Install: `pip install -r requirements.txt`
4. Run: `streamlit run app.py`
