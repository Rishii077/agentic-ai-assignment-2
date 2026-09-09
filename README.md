# Document RAG Agent

An Agentic AI assignment project that reads PDF, DOCX, and TXT documents and answers user questions using Retrieval-Augmented Generation (RAG).

## Features
- Upload PDF, DOCX, and TXT files
- Extract and split document text into chunks
- Create embeddings using OpenAI
- Retrieve relevant content using cosine similarity
- Generate evidence-based answers with source citations

## Run locally

```bash
py -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
streamlit run app.py
