# Flask PDF Q&A Chatbot

A simple web application built with Flask and LangChain that allows you to upload a PDF document and ask questions about its content.

This project uses a RAG (Retrieval-Augmented Generation) pipeline to provide answers based *only* on the content of the uploaded document.


---

## Features

* **File Upload:** Upload any PDF document.
* **Text Processing:** Extracts text, splits it into manageable chunks, and creates a searchable vector database.
* **Q&A Interface:** Ask natural language questions.
* **AI-Powered Answers:** Uses LangChain and a local LLM (Google's FLAN-T5) to generate answers.

---

## Tech Stack

* **Backend:** Flask
* **AI Orchestration:** LangChain
* **LLM:** Google's FLAN-T5 (via `transformers`)
* **Embeddings:** Sentence-Transformers (`all-MiniLM-L6-v2`)
* **Vector Store:** FAISS (in-memory)
* **PDF Parsing:** PyPDF2 (`pypdf2`)

---

## Project Structure

Before running, make sure your project files are organized as follows:
