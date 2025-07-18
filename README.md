# 🤖 AI-Agentic Chatbot with FastAPI

An intelligent, customizable AI chatbot powered by **LangGraph**, **Groq**, **OpenAI**, **Tavily**, **FastAPI**, and **Streamlit**. Supports multiple LLMs, real-time web search, and a fully interactive frontend for natural conversations. Built with love ❤️ for developers and learners exploring next-gen agentic LLM apps.

---

## 🚀 Features

- 🔌 **Supports Multiple LLM Providers**: Choose between **Groq (LLaMA 3, Mixtral)** and **OpenAI (GPT-4o-mini)**.
- 🧠 **Custom AI Behavior**: Define your own system prompt to change your AI’s personality and goals.
- 🔍 **Optional Web Search**: Enable real-time search using **Tavily API** to enhance chatbot responses.
- 🖥️ **Streamlit Frontend**: Simple and modern UI to chat with your AI agents.
- ⚡ **FastAPI Backend**: Lightweight and efficient API server to handle chat requests.
- 🛠️ **Built with LangGraph**: Harness the power of ReAct agents with tool support.

---

## ⚙️ Tech Stack

| Layer        | Technology              |
|--------------|--------------------------|
| Frontend     | Streamlit                |
| Backend      | FastAPI                  |
| LLMs         | Groq (LLaMA, Mixtral), OpenAI (GPT-4o) |
| Agent Logic  | LangGraph (ReAct agent)  |
| Web Search   | Tavily API               |
| Deployment   | Localhost (Uvicorn)      |

---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Muhammadumer33/ai-agentic-chatbot-fastapi.git
cd ai-agentic-chatbot-fastapi

2️⃣ Create a Virtual Environment
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
3️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Setup Environment Variables
Create a .env file in the root directory:

env
Copy
Edit
GROQ_API_KEY=your_groq_api_key
OPENAI_API_KEY=your_openai_api_key
TAVILY_API_KEY=your_tavily_api_key
▶️ Running the App
Step 1: Run the FastAPI Backend
bash
Copy
Edit
python backend.py
It will be live at: http://127.0.0.1:9999/chat

Step 2: Run the Streamlit Frontend
bash
Copy
Edit
streamlit run frontend.py
