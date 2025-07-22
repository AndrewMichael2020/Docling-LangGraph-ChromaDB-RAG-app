# Docling-LangGraph-ChromaDB-RAG-app

> A hybrid document QA pipeline powered by OCR, Docling, LangChain, LangGraph, and ChromaDB.

---

## ✍️ Original Author

This project was originally authored by **Hailey T. Quach** as part of IBM’s work on Retrieval-Augmented Generation (RAG) systems using LangGraph. You can find the original repository at:  
👉 [https://github.com/HaileyTQuach/docchat-docling](https://github.com/HaileyTQuach/docchat-docling)

The original codebase integrates IBM technologies and open-source LLM ecosystem tools to support multi-agent document question answering.

---

## 🔄 Fork Purpose

This fork builds on Hailey’s foundational work, with the goal of:

- **Customizing the RAG pipeline** for QA use cases involving scanned or structured documents
- Adding **OCR and scanned PDF processing** support with Docling
- Exploring **LangGraph** for agent workflows
- Using **ChromaDB** for hybrid semantic + keyword search
- Integrating **secure `.env`-free public workflows**

---

## 📦 Components

- `Docling`: For OCR and PDF-to-Markdown/JSON conversion
- `LangGraph`: Agent graph coordination framework
- `LangChain`: LLM tools and chain utilities
- `ChromaDB`: Fast vector and keyword search backend
- `Gradio`: Simple UI interface for QA demo

---

## ⚠️ Security Notice

All `.env` or API key references have been removed from commit history to comply with GitHub’s **Push Protection** rules.  
Please insert your own OpenAI (or other provider) key in a local `.env` file:

```bash
OPENAI_API_KEY=<your-key-here>
```

Never commit secrets to version control.

---

## 🛠️ Usage (Example)

```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate

# Install requirements
pip install -r requirements.txt

# Run a test
python test/test1.py
```

---

## 🤝 Credits

- **Hailey T. Quach** – Author of original repository and IBM fellow
- **IBM Research** – For their contributions to Docling and agent orchestration models
- **LangChain & LangGraph** – Open-source contributors and maintainers
- **ChromaDB Team** – For modern hybrid vector search
- **OpenAI** – For LLM APIs used in this prototype

---

## 📄 License

MIT (follow upstream repo license)
