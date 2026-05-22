# AI Search Agent

An intelligent web search agent using **FastAPI**, **Streamlit**, and **Serper API**.  
It extracts keywords from user queries, searches the web, ranks results, and displays them with AI summaries.

## 🚀 Tech Stack
- **Frontend:** Streamlit  
- **Backend:** FastAPI  
- **Search Engine:** Serper API  
- **AI Model:** LangChain + OpenAI  

## ⚙️ Setup
```bash
git clone https://github.com/Unknown-guy-369/content-recommendation-agent.git   
cd content-recommendation-agent
pip install -r requirements.txt
```
## Run
### Backend
```bash
py -m uvicorn ai_agent:app 
```

## Frontend
```bash
py -m streamlit run frontend.py
```
