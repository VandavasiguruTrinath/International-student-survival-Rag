# International Student Survival using Retrieval-Augmented Generation (RAG)

## 📌 Overview

This project presents a Retrieval-Augmented Generation (RAG) system designed to assist international students by providing accurate, context-aware answers based on institutional documents.

The system combines document retrieval with large language models (LLMs) to reduce hallucination and improve factual accuracy.

---

## 🎯 Objectives

- Provide reliable answers to international student queries
- Reduce hallucination in LLM responses
- Compare performance of multiple open-source models

---

## 🧠 Models Used

- Llama 3.1
- Mistral 7B
- Phi-3 Mini

All models were run locally using **Ollama**.

---

## ⚙️ System Architecture

The system follows a standard RAG pipeline:

1. User Query
2. Embedding Generation
3. Vector Search (FAISS)
4. Retrieval of Top-K Chunks
5. Response Generation using LLM

---

## 📂 Dataset

The dataset consists of institutional documents related to:

- Visa and immigration
- Enrollment requirements
- Student services
- Tuition and fees
- Academic policies

---

## ❓ Example Query
