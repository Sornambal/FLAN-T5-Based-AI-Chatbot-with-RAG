# 🤖 AI Notes Chatbot

A simple, offline, intelligent chatbot that answers questions based on uploaded course notes using **FAISS**, **SentenceTransformers**, and **FLAN-T5**.

---

## 🧠 Features
- Upload `.pdf`, `.docx`, or `.txt` files
- Extracts and preprocesses text automatically
- Builds vector embeddings using **SentenceTransformer (MiniLM)**
- Uses **FAISS** for similarity-based retrieval
- Generates answers using **FLAN-T5-base**
- Clean **Gradio-based** chat interface (no API key required)

---

## 🧩 Tech Stack
- **Python 3.10+**
- **SentenceTransformers**
- **FAISS**
- **Transformers (FLAN-T5)**
- **Gradio**
- **PyMuPDF**
- **python-docx**

---

## ⚙️ Setup Instructions

### 1️⃣ Clone or Copy the Project
If using Google Colab, skip cloning — just copy all cells directly.

If using locally:
```bash
git clone https://github.com/yourusername/ai-notes-chatbot.git
cd ai-notes-chatbot
