# 🧠 Multimodal RAG for PDF Understanding

A **Multimodal Retrieval-Augmented Generation (RAG)** pipeline designed to understand complex PDF documents containing **text, tables, images, charts, and diagrams**.

Unlike traditional text-based RAG systems, this project combines **textual and visual information** to provide more complete and context-aware answers.

## 🚀 Project Overview

The pipeline processes multimodal PDF documents, transforms their content into searchable representations, and retrieves the most relevant information for a given user query.

The retrieved context is then provided to a **Vision LLM**, which combines textual and visual information to generate a grounded answer.

### 🔄 Architecture

```text
PDF Documents
     │
     ▼
Text + Images + Tables + Charts
     │
     ▼
Multimodal Processing
     │
     ├── Text Embeddings
     └── Image / Visual Summaries
             │
             ▼
       Pinecone Vector DB
             │
             ▼
        User Question
             │
             ▼
      Relevant Retrieval
             │
             ▼
        Vision LLM
             │
             ▼
       Context-Aware Answer
```

## 🛠️ Technologies

* **Python**
* **LangChain** – RAG pipeline orchestration
* **Hugging Face / Sentence Transformers** – embeddings
* **Pinecone** – vector database and similarity search
* **Vision LLMs** – visual understanding and generation
* **PDF processing** – extraction of text and visual content

## ✨ Key Features

* 📄 Multimodal PDF understanding
* 🖼️ Image, chart and diagram processing
* 🔎 Semantic vector retrieval
* 🧩 Text + visual context combination
* 🤖 Vision LLM-based question answering
* 📚 Context-aware and grounded responses

## 🎯 Why Multimodal RAG?

Traditional RAG mainly works with extracted text, which can lead to the loss of important information contained in **figures, charts, tables, and diagrams**.

This project addresses this limitation by making both **textual and visual information searchable and usable during generation**.

## 📌 Use Cases

* Research papers and technical documentation
* Scientific reports
* Financial and business reports
* Educational documents
* Complex PDF knowledge bases

## 👩‍💻 Author

**Oumaima Hleli**
AI Engineer | Data Science | Generative AI | RAG

