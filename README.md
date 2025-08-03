# Mortgage AI Assistant

A local Retrieval-Augmented Generation (RAG) assistant tailored for mortgage-related documents.  
It combines OCR, FAISS vector search, and Mistral-7B Instruct LLM to answer user queries via an easy-to-use Gradio interface — all running locally on macOS.

---

## 🚀 Features

- Upload multiple mortgage PDFs and images (PNG)
- OCR text extraction using EasyOCR for accurate content parsing
- Document chunking and embedding with HuggingFace sentence-transformers
- Vector search powered by FAISS with persistent local index
- Powerful local LLM inference using Mistral-7B via `llama-cpp-python` (Metal acceleration)
- Gradio-based chat UI with multi-document context and source citation
- Real-time analytics panel for chunk/token stats and indexing success
- Guardrails to prevent hallucinated or empty responses

---

## 🛠️ Installation & Setup

1. **Clone the repository:**

```bash
git clone https://github.com/atharvabhale/Mortgage_AI_Assistant.git
cd Mortgage_AI_Assistant
