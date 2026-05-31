# Anime Recommender System – LLMOps

An LLM-powered semantic anime recommendation engine.

## Tech Stack
- LangChain
- ChromaDB (Vector Database)
- Groq LLM (Llama 3.3 70B)
- Sentence Transformers (HuggingFace)
- Streamlit
- Docker
- Kubernetes

## How It Works
User query → Sentence Transformer converts to vector embedding → 
ChromaDB finds similar anime → Groq LLM generates recommendation → 
Displayed on Streamlit UI

## Run Locally
pip install -r requirements.txt
streamlit run app/main.py
