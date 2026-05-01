
# International Student Survival using Retrieval-Augmented Generation (RAG)

##  Overview

This project presents a Retrieval-Augmented Generation (RAG) system designed to assist international students by providing accurate, context-aware answers based on institutional documents.

The system combines document retrieval with large language models (LLMs) to reduce hallucination and improve factual accuracy.

---

##  Objectives

- Provide reliable answers to international student queries
- Reduce hallucination in LLM responses
- Compare performance of multiple open-source models

---

##  Models Used

- Llama 3.1
- Mistral 7B
- Phi-3 Mini

All models were run locally using **Ollama**.

---

##  System Architecture

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

##  Example Query

---

## 📊 Results Summary

| Model   | Accuracy | Reasoning | Hallucination |
|--------|---------|----------|--------------|
| Llama  | 2.0     | 2.6      | 1.0          |
| Mistral| 2.2     | 3.0      | 1.0          |
| Phi    | 2.0     | 3.2      | 1.2          |

---

##  Key Findings

- Mistral provides the best balance between accuracy and reasoning
- Llama produces more stable and grounded responses
- Phi shows strong reasoning but higher hallucination

---

##  Installation

### 1. Clone Repository

```bash
git clone https://github.com/your-username/International-Student-Survival-RAG.git
cd International-Student-Survival-RAG
### 2. Install Dependencies
pip install -r requirements.txt

### 3. Install Ollama
Download from: https://ollama.com
Run models:
ollama run llama3
ollama run mistral
ollama run phi

###How to Run
python main.py
