# Langchain-Agents
A collection of AI Agents and RAG applications built with LangChain and LLMs. Documenting my journey from basic tools to advanced autonomous systems.
# 🦜🔗 LangChain Agents & RAG Experiments

Welcome to my AI playground! This repository documents my journey learning and building autonomous agents using **LangChain** .

## 🚀 Current Projects

### 1. 📚 PDF Chatbot (RAG)
A "Chat with your Data" bot that allows users to ask questions about PDF documents.
- **Tech:** LangChain, FAISS Vector DB, PyPDFLoader.
- **Model:** Google Gemini 1.5 Flash.
- **Features:**
  - Loads and splits PDF documents.
  - Generates vector embeddings.
  - Retrieves accurate answers using Semantic Search.
  - *Current Focus:* Optimizing retrieval for specific keyword searches (Solving the "Linear Regression" problem).

### 2. 🧮 Math & Utility Agent
A ReAct (Reason + Act) agent designed to solve problems using external tools.
- **Tech:** LangChain Agents, Custom Tools.
- **Tools:** Calculator, Text Reverser.
- **Logic:** Uses the LLM to reason through a problem and select the correct Python function to execute it.

## 🛠️ Tech Stack
- **Language:** Python 🐍
- **Framework:** LangChain
- **LLM:** Google Gemini (via `langchain-google-genai`)
- **Vector Store:** FAISS
- **Environment:** Google Colab / Jupyter

## 🚧 Roadmap
- [ ] Improve RAG retrieval context window.
- [ ] Add a frontend UI (Streamlit).
- [ ] Experiment with "Memory" (Chat History).
- [ ] Deploy the PDF bot as a web app.

---
*This is a learning repository. New experiments are added as I progress!*
