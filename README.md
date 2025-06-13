# RAG-Powered First-Aid Chatbot for Diabetes, Cardiac & Renal Emergencies

## 🚀 Project Overview
A Retrieval-Augmented Generation (RAG) chatbot combining:
- 🔍 Local embeddings of 60 vetted medical first-aid facts
- 🌐 Live web search via Serper.dev for fresh evidence
- 🧠 GPT-based answer generation with condition, guidance, medicines, citations

## 🧩 Architecture
![Architecture](architecture.png)

## 📁 Folder Structure
RAG-FirstAid-Chatbot/
├── src/
├── tests/
├── data/
├── README.md
├── requirements.txt
├── architecture.png
└── performance_report.md

## 🧪 Sample Queries (Target: 8/10 accurate)
[List of 10 queries as described]

## ▶️ Run Demo
python src/app.py

## 🌐 Serper.dev Setup
1. Visit https://serper.dev → Get API key
2. Create .env file with your keys

## ✅ Dependencies
faiss-cpu, sentence-transformers, openai, serper, python-dotenv, pytest
