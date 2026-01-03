# 📚 Personal RAG System for Technical Books

A Retrieval-Augmented Generation (RAG) system built to query and refresh technical concepts directly from a personal collection of O’Reilly and other ML/AI books.  
Instead of manually searching PDFs, this system allows you to ask natural language questions and receive **contextual, referenced answers** from the original source material.

---

## 🚀 Why This Project?

While working on multiple Machine Learning and GenAI projects, I often remembered studying a concept earlier in one of my books but had to waste time manually searching chapters to find it again.

This project solves that problem by turning your technical library into a **queryable knowledge base**.

---

## 🧠 What It Does

- Ingests technical books and documents (currently supports PDF)
- Chunks content for efficient retrieval
- Stores and uses **book-level metadata** for precise referencing
- Retrieves relevant context and answers questions with citations
- Designed to scale across multiple data sources and formats

---

## 🛠️ Tech Stack

- **LangChain** – Pipeline orchestration and RAG framework  
- **Sentence Transformers** – Semantic embeddings  
- **ChromaDB** – Vector database for fast retrieval  
- **Git** – Version control

---

## 📂 Project Structure

Langchain-project/
├── data/
│   └── PDFs/
├── chunks/
│   └── processed_text/
├── metadata/
│   └── book_info/
├── src/
│   ├── ingestion.py
│   ├── chunking.py
│   ├── retrieval.py
│   └── app.py
├── requirements.txt
└── README.md




