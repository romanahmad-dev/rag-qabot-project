# rag-qabot-project

# 🧠 RAG Q&A Bot with LangChain and Watsonx.ai

This project is part of the Coursera capstone for the course **"Generative AI Applications with RAG and LangChain"**. It demonstrates how to build a document-based question-answering bot using LangChain, vector databases, embeddings, and a large language model (LLM).

---

## 🔗 Open in Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/romanahmad-dev/rag-qabot-project/blob/main/rag_app.ipynb)

---

## 📌 Project Tasks Overview

| Task No. | Description |
|----------|-------------|
| ✅ **Task 1** | Load PDF/Text document using LangChain loaders |
| ✅ **Task 2** | Apply text splitting to segment content |
| ✅ **Task 3** | Embed documents using `Watsonx.ai` / Hugging Face |
| ✅ **Task 4** | Store embeddings in Chroma vector DB |
| ✅ **Task 5** | Implement retriever to fetch top matches |
| ✅ **Task 6** | Build a QA chatbot with Gradio interface |

---

## 📸 Screenshots (included in this repo)

- `pdf_loader.png` – Document loading output  
- `code_splitter.png` – Text splitting code/results  
- `embedding.png` – Embedding values from query  
- `vectordb.png` – Chroma vector DB and top 5 search results  
- `retriever.png` – Retriever returning top 2 relevant chunks  
- `QA_bot.png` – Gradio chatbot answering document-based questions

---

## 🔧 Technologies Used

- **LangChain**
- **Watsonx.ai** (`ibm/slate-125m-english-rtrvr`)
- **Hugging Face Transformers** (for fallback)
- **ChromaDB**
- **Gradio (UI)**
- **Python + Google Colab**

---

## ⚠️ Note

> Watsonx.ai API access was not available at the time of development, so **Hugging Face models** were used to demonstrate the functionality. The code is fully compatible with Watsonx APIs and can be easily switched by updating credentials and model IDs.

---

## 👨‍💻 Author

**Roman Ahmad Khan**  
📧 [GitHub Profile](https://github.com/romanahmad-dev)  
🎓 Final Year Student – BSCS  

---

## 📄 License

This project is provided for educational purposes under Coursera's academic use guidelines.
