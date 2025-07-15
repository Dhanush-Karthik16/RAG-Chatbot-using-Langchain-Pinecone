# 🤖 RAG_Chatbot_with_LangChain_and_Pinecone

An intelligent document-based chatbot powered by **LangChain**, **Google Gemini**, and **Pinecone**. This Flask web app uses **Retrieval-Augmented Generation (RAG)** to answer user queries based on uploaded `.txt`, `.pdf`, or `.docx` documents.

## 🚀 Tech Stack
- 🧠 **LLM**: Google Gemini (via LangChain)
- 📚 **Vector Store**: Pinecone (cosine similarity)
- 🧩 **LangChain**: For RAG pipeline, text splitting, and embeddings
- 🗂️ **File Support**: `.txt`, `.pdf`, `.docx`
- 🌐 **Framework**: Flask (with Bootstrap UI + dark mode + chat-style feed)

## 📦 Features
- Upload any document and ask questions about its content
- Chat-style responses with document source snippets
- Dark mode toggle + loading spinner
- RAG pipeline with real-time semantic search

## 📸 Sample Screenshots

<img width="997" height="837" alt="image" src="https://github.com/user-attachments/assets/cedb88f6-e204-403f-b662-f1663bf29012" />

## 📂 File Structure
- Insight chatbot/
- ├── app.py
- ├── templates/
- │   └── index.html
- ├── static/
- │   └── style.css 
- ├── requirements.txt
