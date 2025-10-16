# ChatWithPDF — Agentic PDF Conversational Agent 📄🤖


[![Watch Demo](https://img.youtube.com/vi/1JOF6l-LdlqLCC72-UNIT_QtzZdvQZ6ig/0.jpg)](https://drive.google.com/file/d/1JOF6l-LdlqLCC72-UNIT_QtzZdvQZ6ig/view?usp=drive_link)

**Demo Video**:  
[▶️ Watch the demo on Google Drive](https://drive.google.com/file/d/1JOF6l-LdlqLCC72-UNIT_QtzZdvQZ6ig/view?usp=drive_link)

---
### Project Link :
https://drive.google.com/drive/folders/1V8p1bRjuiW_kcJSs47c0N1_dyw4CAlqe?usp=drive_link

## 🔍 Project Overview

**ChatWithPDF** is an AI-powered conversational agent built using **LangChain** and **OpenAI**, which allows users to upload PDFs and interact with their content naturally via chat. The system also supports multiple tools (e.g. news, weather, Python REPL) to behave like a versatile agent.

This project demonstrates my skills in:  
- Agentic AI with tool orchestration  
- Document retrieval and embedding-based search  
- FastAPI + backend integration  
- Practical engineering for deployable AI systems  

---

## ✨ Key Features

- **PDF Upload & Q&A**: Upload one or more PDF documents, and ask questions that refer to their contents.  
- **Multi-Tool Integration**:
  - Document Retrieval / Embedding search  
  - News fetching tool  
  - Weather tool (OpenMeteo)  
  - Python REPL tool (execute code on the fly)  
- **Contextual Chat**: Maintains chat history and dynamically chooses appropriate tools for queries.  
- **Scalable & Extensible**: Easy to add new tools and modules in future.  

---

## 🛠️ Tech Stack

| Component | Technology / Library |
|-----------|----------------------|
| Language Model & Agent | OpenAI GPT (gpt-3.5-turbo) + LangChain |
| Web Framework | FastAPI |
| PDF Processing & Retrieval | PyPDF, embeddings, vector store (Chroma / FAISS, etc.) |
| Tools Integration | Custom tool modules: `news_tool`, `weather_tool`, `python_repl_tool` |
| Hosting / Deployment | (You can host it on any server or cloud) |
| Demo & Assets Storage | Google Drive |

---

## 🏗 Architecture & Flow

1. **User uploads PDF(s)** via the FastAPI endpoint.  
2. **PDF content is parsed** and stored in a vector store (embeddings).  
3. **User sends a natural-language query**.  
4. The **LangChain agent** considers the query, previously loaded tools, and chat history.  
5. It **decides which tool to call** (e.g. retrieval, weather, Python REPL).  
6. **Tool returns result** → Agent synthesizes answer → returns to user.  




Flow chart (simplified in Markdown):
ChatWithPDF/
│
├── app/
│   ├── agent_service.py
│   ├── tools/
│   │   ├── news_tool.py
│   │   ├── weather_tool.py
│   │   └── python_repl.py
│   ├── retrievers/
│   │   └── add_doc.py
│   └── config.py
│
├── main.py
├── pdfloader.py
├── requirements.txt
├── .gitignore
└── README.md



🚀 Skills & Highlights

Built a function-calling agent with LangChain

Integrated PDF document Q&A using embeddings & retrieval

Developed tools for news, weather, and code execution in one agent

Solid backend structure with FastAPI and modular tool architecture

Demonstrated full-stack AI engineering — from prototype to demo-ready

📌 Connect With Me
LinkedIn:https://www.linkedin.com/in/lekheshwari-ukey-data-scientist/
