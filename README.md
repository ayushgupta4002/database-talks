# 📊 Database Talks

**Database Talks** is an LLM-powered FastAPI application that lets you interact with your database using natural human language. It translates user queries to SQL, validates them, executes them on a connected database, and returns results in a human-readable format.

---

## 🚀 Features

- 💬 Query your database using plain English.
- 🧠 Uses **LangChain**, **LangGraph**, and **Google Gemini (via LangChain)**.
- 🛠️ Validates and fixes SQL queries automatically.
- 📥 Executes SQL queries and presents readable output.
- 🔌 Easily integrable with any PostgreSQL database.

---

## 🛠 Tech Stack

- [FastAPI](https://fastapi.tiangolo.com/)
- [LangChain](https://www.langchain.com/)
- [LangGraph](https://www.langgraph.dev/)
- [Google Gemini via LangChain](https://python.langchain.com/docs/integrations/chat/google_generative_ai)
- PostgreSQL

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory:

```env
GOOGLE_API_KEY=your_google_gemini_api_key
DATABASE_URL=your_postgres_connection_string
