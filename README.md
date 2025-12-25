# 🚀 AI Engineering Projects

Welcome to **AI_Engineering** — a collection of hands-on AI projects and experiments I built while completing  
**The AI Engineer Course: Complete AI Engineer Bootcamp** on Udemy.

This repository focuses on *practical AI engineering*, covering NLP, Large Language Models (LLMs), vector databases, AI agents, and real-world applications.

---

## 📚 About This Repository

This repo contains multiple independent projects and notebooks, each demonstrating a core AI concept or tool commonly used by AI Engineers today.

Topics covered include:
- Natural Language Processing (NLP)
- Transformer-based models (BERT, XLNet, GPT)
- Hugging Face ecosystem
- LangChain & AI agents
- Vector databases & embeddings
- Speech recognition
- Streamlit AI applications

All projects were built for learning and experimentation purposes, with a strong focus on **implementation**, not just theory.

---

## 📁 Project Structure & Contents

### 📌 BERT_QA
Question Answering systems built using **BERT-based transformer models**.  
These notebooks show how to extract answers from context text using modern NLP architectures.

---

### 📌 Fake_News_Identifier
An NLP classification project that detects **fake vs real news** using text preprocessing, feature extraction, and machine learning models.

---

### 📌 GPT
Experiments with **GPT-style generative models**, including text generation and prompt-based interactions.

---

### 📌 HuggingFace_Transformers
Hands-on examples using the **Hugging Face Transformers** library:
- Tokenization
- Model loading
- Inference
- Embeddings
- NLP pipelines

---

### 📌 LangChain
Projects demonstrating **LangChain**, a framework for building AI applications by chaining LLM calls with logic, memory, tools, and external data sources.

---

### 📌 LangGraph
Examples of structuring and orchestrating AI workflows using **LangGraph**, useful for agent-based and multi-step reasoning systems.

---

### 📌 Speech_Recognition
Speech-to-text implementations showing how to convert spoken audio into text using AI models and Python libraries.

---

### 📌 Streamlit_Interview_Agent
A **Streamlit-based AI agent** that interacts with users in real time.  
This project demonstrates how to deploy AI logic inside a simple web interface.

---

### 📌 XLNET_Text_Classification
Text classification tasks implemented using **XLNet**, highlighting alternatives to BERT for language understanding tasks.

---

### 📌 vectorDB
Hands-on examples with **vector embeddings and vector databases**, including:
- Creating embeddings
- Storing vectors
- Semantic search & retrieval  
A key building block for RAG (Retrieval-Augmented Generation) systems.

---

## 🧠 Skills Demonstrated

By exploring this repository, you’ll see practical experience with:

- Python for AI
- NLP pipelines
- Transformer architectures
- Generative AI
- LangChain & AI agents
- Vector databases
- Streamlit apps
- Speech recognition systems

---

## 🚀 How to Run the Projects

1. Clone the repository:
   ```bash
   git clone https://github.com/youssef456/AI_Engineering.git
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux / macOS
   venv\Scripts\activate      # Windows

3. Install dependencies:
   ```bash
   pip install -r requirements.txt

6. Run notebooks or applications:
    ```bash
   jupyter notebook
    # or
    streamlit run Streamlit_Interview_Agent/app.py
