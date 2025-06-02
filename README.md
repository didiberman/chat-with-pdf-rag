# 📄 Chat with Your PDF – RAG App using LangChain

A minimal Retrieval-Augmented Generation (RAG) project that lets you **chat with any PDF document** using LangChain, vector embeddings, and a large language model (LLM).

---

## 💡 What It Does

- Accepts a **PDF upload**
- Parses and **chunks** the text
- Generates **embeddings** for semantic search
- Retrieves relevant sections based on user queries
- Uses an LLM to **generate answers** with source-aware context

---

## 🧰 Tech Stack

- `LangChain` – orchestration
- `FAISS` – vector database
- `PyMuPDF` – PDF parsing
- `OpenAI` or `HuggingFace Transformers` – LLM backend
- `Streamlit` or `FastAPI` – interactive interface

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/chat-with-pdf-rag.git
cd chat-with-pdf-rag
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the App

```bash
streamlit run app.py
```

---

## 🧪 Example Use Case

- Upload: *"Gabor Maté - The Myth of Normal.pdf"*
- Ask: *"What’s the difference between trauma and stress?"*
- Output: *"Trauma is a wound to the psyche… (excerpted from page 24)"*

---

## 📁 Project Structure

```
.
├── app.py                 # Streamlit or FastAPI app
├── utils/                 # PDF parsing, chunking, etc.
├── embeddings/            # FAISS vector store
├── data/                  # PDF uploads
├── prompts/               # Prompt templates
├── requirements.txt
└── README.md
```

---

## ✨ Skills Demonstrated

- Document parsing & chunking
- Embedding generation & retrieval (semantic search)
- Context-aware LLM prompting
- Minimal RAG architecture
- Streamlit interface for interaction

---

## 🧠 Author

**Didi Berman**  
AI & Automation Engineer · Focused on MLOps, RAG apps, and trauma-informed tech  
[GitHub](https://github.com/didiberman) | [Website](https://didiberman.com)

---

## 🔖 Repo Name

**`chat-with-pdf-rag`**

---

## 📦 Short Description (≤350 chars)

Chat with any PDF using a simple Retrieval-Augmented Generation (RAG) pipeline. This LangChain-powered app parses your document, embeds it, retrieves the most relevant content for your question, and answers using a large language model.
