# 📚 Personal Book Chapter Summarizer

A lightweight AI-powered tool to generate chapter-wise summaries from book PDFs using semantic retrieval and abstractive summarization. Developed as part of a remote research internship at IIT Kanpur.

---

## 🚀 Features

- 🔍 **Semantic Search with FAISS**: Retrieves the most relevant content chunks using sentence-level embeddings.
- 🤖 **Abstractive Summarization**: Utilizes `facebook/bart-large-cnn` for high-quality, context-aware summaries.
- 📄 **PDF Parsing**: Automatically extracts and processes text from user-uploaded book PDFs.
- 🧠 **Custom Retrieval-Augmented Generation (RAG)**: Combines vector search and transformer-based summarization.

---

## 🛠️ Tech Stack

- Python 3.10+
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [SentenceTransformers](https://www.sbert.net/)
- [FAISS](https://github.com/facebookresearch/faiss)
- PyPDF2 for PDF text extraction
- Google Colab (recommended for execution)
