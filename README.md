# RAG-Chatbot-
```python?code_reference&code_event_index=3
# Define the README content
readme_content = """# RAG-Based Financial Analysis Chatbot (Microsoft 2025 Annual Report)

A production-grade **Retrieval-Augmented Generation (RAG)** pipeline built to perform deep-dive financial analysis on complex corporate documents. This project focuses on **Context Engineering** to reduce token costs and eliminate hallucinations in financial reporting.

## 🚀 Overview
Traditional LLMs often struggle with large documents due to context window limits. This system implements a **modular RAG architecture** that:
1.  **Chunks** large PDFs into semantically meaningful segments.
2.  **Indexes** these segments using high-performance vector embeddings.
3.  **Retrieves** only the most relevant context for a user's specific query.
4.  **Generates** answers using the **Gemini 1.5 Flash** model, strictly constrained to the retrieved data.

## 🛠️ Tech Stack
* **LLM:** Google Gemini 1.5 Flash (via `google-generativeai`)
* **Vector Database:** FAISS (Facebook AI Similarity Search)
* **Embeddings:** Sentence-Transformers (`all-MiniLM-L6-v2`)
* **Frameworks:** LangChain (Orchestration), PyPDF (PDF Processing)
* **Interface:** IPython Widgets (Interactive Notebook UI for rapid testing)

## 📊 Evaluation Framework (The RAG Triad)
To ensure the system meets "Product-Ready" standards for reliability, I implemented an **LLM-as-a-Judge** evaluation module. The system is measured on:
* **Faithfulness:** Is the answer derived *only* from the context?
* **Relevancy:** Does the answer actually address the user's query?

## 💡 Key Features
* **Interactive Query Widget:** Test multiple queries instantly without re-processing the PDF, saving time and compute.
* **Financial Logic Mastery:** Optimized to handle complex financial data from the **Microsoft 2025 Annual Report**, including revenue segments and tax anomalies.
* **Token Efficiency:** Only relevant snippets are sent to the LLM, significantly reducing API overhead.

## 📂 Project Structure
```text
├── RAG_Chatbot.ipynb      # Main development notebook
├── Microsoft_2025_AR.pdf  # Sample financial dataset
└── README.md              # Project documentation
```


*Developed by Akshat | Computer Science Engineering & AI Product Management.*
"""



