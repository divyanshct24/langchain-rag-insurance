# 🧠 LangChain RAG Project – Insurance Domain

This beginner-friendly project builds a **Retrieval-Augmented Generation (RAG)** system using LangChain and Hugging Face to answer questions from real insurance documents.

## 📌 Project Objective

To build an AI assistant that can read long insurance PDFs and answer user questions by retrieving relevant information and generating intelligent answers.

## 🛠️ Tech Stack

- [LangChain](https://python.langchain.com/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
- [Gradio](https://gradio.app/)
- [SentenceTransformers](https://www.sbert.net/)
- Google Colab + Google Drive

## 🧱 How It Works

1. Load PDFs from Google Drive
2. Split the documents into small text chunks
3. Embed chunks using Hugging Face sentence transformers
4. Store the embeddings in a FAISS vector store
5. Retrieve relevant chunks based on a user query
6. Generate an answer using FLAN-T5 model from Hugging Face
7. Interact using a simple Gradio interface

## ✅ Features

- No API key required (free open-source model)
- Fully functional inside Google Colab
- Can be customized for any PDF-based domain (HR, Legal, Healthcare)

## 🚀 How to Run

1. Open the `rag_insurance_colab.ipynb` notebook in Google Colab
2. Upload your insurance documents to Google Drive
3. Follow the notebook cells to install packages and run the pipeline
4. Use the chatbot interface to ask questions

## 📄 Example Questions

- "What is excluded from the policy?"
- "Does this insurance cover floods?"

---

## 📂 Repository Structure

```
📁 langchain-rag-insurance/
├── rag_insurance_colab.ipynb
├── README.md
├── requirements.txt
└── LangChain_RAG_Insurance_Project_Report.pdf
```

## ✍️ Author

This project was built as part of a GenAI course project to showcase how LangChain and Hugging Face can be used for insurance industry use cases.