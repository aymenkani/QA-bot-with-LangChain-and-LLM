# QA Bot with LangChain and Watsonx LLM

A question-answering bot that uses **LangChain**, **IBM Watsonx LLMs**, and **vector embeddings** to answer queries based on the content of uploaded PDF documents.  
The bot provides a simple **Gradio web interface** where users can upload a PDF, ask natural language questions, and receive precise answers grounded in the document.

---

## 🚀 Features
- 📄 Upload PDF documents and query them directly  
- 🤖 Powered by **Watsonx LLMs** for natural language understanding  
- 🔍 Uses **LangChain** for retrieval-augmented generation (RAG)  
- 📚 Stores document chunks in a **Chroma vector database** with embeddings  
- 🌐 Easy-to-use **Gradio interface**  

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/aymenkani/QA-bot-with-LangChain-and-LLM.git
   cd QA-bot-with-LangChain-and-LLM

2. (Optional but recommended) Create and activate a virtual environment:
    ```python
    python3 -m venv .venv
    source .venv/bin/activate   # On Windows use: .venv\Scripts\activate


▶️ Usage

Run the bot locally:
```python
python3 qabot.py
