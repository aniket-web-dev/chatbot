# 📚 PDF Chatbot using Streamlit + LangChain + OpenAI
![Screenshot 2025-06-11 174911](https://github.com/user-attachments/assets/f9e820ae-3211-45b5-8234-81412837510d)
![Screenshot 2025-06-11 175031](https://github.com/user-attachments/assets/ae064006-3a42-44aa-a1dd-5c5d90b79460)
![Screenshot 2025-06-11 175122](https://github.com/user-attachments/assets/87ad24c2-41cc-4e12-b61c-efb31265bdba)

A simple chatbot that lets users upload PDF documents and ask questions about the content. It uses OpenAI's `gpt-3.5-turbo`, LangChain for text processing, and FAISS for similarity search.

## 🧠 Features

- Upload a PDF file and extract all pages
- Split content into manageable chunks
- Generate semantic embeddings using OpenAI
- Store & search using FAISS vector database
- Ask questions from the uploaded document
- Display answer using GPT-based LLM

---

## 📂 Project Architecture
![Architecture](https://github.com/user-attachments/assets/a75f7c3e-998e-4d3b-8edd-48978e2cca87)

## Create Virtual Environment
  python -m venv venv 
  
## Install Dependencies

pip install streamlit PyPDF2 langchain openai tiktoken faiss-cpu

## Set OpenAI API Key

OPENAI_API_KEY="sk-xxxxx"  

## 🚀 Run the App

streamlit run chatbot.py

