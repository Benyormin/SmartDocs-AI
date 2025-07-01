# 📄 SmartDocs AI – Gemini-Powered RAG Q&A App

SmartDocs AI is a NotebookLM-style document assistant built using the **RAG (Retrieval-Augmented Generation)** approach. Upload documents or add URLs, ask natural language questions, and get accurate, source-backed answers powered by **Google's Gemini 2.5 Flash** via LangChain.

## 🚀 Features

- ✅ Upload and process multiple file types: `.pdf`, `.csv`, `.txt`, `.xlsx`
- 🌐 Add and query content from multiple URLs
- 🧠 Uses Gemini 2.5 Flash as the LLM via LangChain
- 📚 Embedding via `sentence-transformers/all-MiniLM-L6-v2`
- 🔍 Fast document retrieval using FAISS vector store
- 🌍 Share the app via public `ngrok` tunnel
- 💡 RAG pipeline: split → embed → store → retrieve → answer with sources

---

## 🛠️ Tech Stack

| Component        | Technology                            |
|------------------|----------------------------------------|
| UI               | Streamlit                              |
| LLM              | Google Gemini 2.5 Flash                |
| Embedding Model  | MiniLM (`sentence-transformers`)       |
| Retriever        | FAISS                                  |
| File Support     | PDF, CSV, Excel, TXT                   |
| Hosting (Dev)    | ngrok tunnel                           |
| Framework        | LangChain                              |

---

## 📦 Installation

```bash
git clone https://github.com/your-username/smartdocs-ai.git
cd smartdocs-ai
pip install -r requirements.txt
