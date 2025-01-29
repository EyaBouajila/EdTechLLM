# Codebasics Retrieval Q&A 🌱
![Screenshot 2025-01-30 004331](https://github.com/user-attachments/assets/1e161483-22f5-4391-b69a-447b5b71fbd9)



## Overview
This project is a **Q&A system** that allows users to query a knowledge base and receive relevant answers. The knowledge base is built from a CSV file containing FAQs, which is processed into a **vector database** using FAISS. The system retrieves the most relevant information and generates answers using **Google Gemini (gemini-1.5-flash)**.

## Features
- **Streamlit UI** for user interaction
- **FAISS vector database** for efficient retrieval
- **Google Gemini-powered QA system** for accurate responses
- **CSV-based knowledge base** that can be updated easily
- **On-demand vector database creation** via a button click

## Technologies Used
- **Python**
- **Streamlit** for the web interface
- **LangChain** for retrieval and LLM integration
- **FAISS** for vector storage
- **HuggingFace Embeddings** for document representation
- **Google Gemini API** for generating responses
- **dotenv** for managing API keys
