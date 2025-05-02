
# 🔎 Search Engine ChatBot


An AI-powered chatbot built with LangChain, powered by Llama3 via Groq, and integrated with DuckDuckGo, Wikipedia, and Arxiv to fetch real-time, informative answers.

🚀 Live Demo



## ✨ Features


- 🔍 Multi-source Search: Queries DuckDuckGo, Wikipedia, and Arxiv simultaneously.
- 🤖 Llama3 via Groq: Uses the blazing-fast Llama3 model served by Groq API for high-quality responses.

- 📚 Academic-Grade Answers: Pulls summaries from Arxiv and Wikipedia using LangChain tools.

- 💬 Chat Interface: Clean and interactive chat experience with Streamlit.

- 🔐 Secure API Input: Users enter their Groq API key directly in the UI sidebar — no hardcoding required.

- 🧠 Agent-Based Reasoning: Powered by LangChain’s Zero-Shot ReAct Agent for better decision-making.

- 🌐 No Setup Required for End Users: Just click and try on the live app.


## Tech Stack

**Python:** Core backend logic


**Streamlit:** Interactive web frontend


**LangChain:**  Agent framework, tool orchestration

**DuckDuckGo Tool	:** Web search

**Wikipedia Tool	:**  Encyclopedia search

**Arxiv Tool	:**  Academic paper search

**Groq + Llama3	:**  Large Language Model (LLM) backend




## ⚙️ How to Run Locally
 

1. Clone the Repository


```bash
git clone https://github.com/bhardwaj2-6/Search_Engine_ChatBot.git
cd Search_Engine_ChatBot
```

2. Set Up a Virtual Environment (Optional)


```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. Install Dependencies

```bash
pip install -r requirements.txt
```

4. Run the App



```bash
streamlit run app1.py
```


## 🧪 Example Prompt






```javascript
User: What are the latest advancements in quantum computing?

Chatbot: (Searches DuckDuckGo + Wikipedia + Arxiv → Summarizes via Llama3 → Returns synthesized answer)

```


## 🧠 How It Works


1. Takes user input from chat.

2. Uses LangChain agent to choose appropriate tools.

3. Fetches data from:

        🔎 DuckDuckGo for general search

        📘 Wikipedia for factual summaries

        📄 Arxiv for academic content

4. Uses Groq-hosted Llama3 to combine and summarize results.

5. Responds in real time in the chat window.

