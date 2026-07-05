# 🚀 PaperMind AI
### AI-Powered Research Paper Assistant using Semantic Search, Scientific NLP, and Retrieval-Augmented Generation (RAG)

<p align="center">
  <img src="images/banner.png" width="100%">
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![NLP](https://img.shields.io/badge/NLP-Research-green?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-Vector%20Search-red?style=for-the-badge)
![Sentence Transformers](https://img.shields.io/badge/Sentence--Transformers-Embeddings-orange?style=for-the-badge)
![SciSpaCy](https://img.shields.io/badge/SciSpaCy-NER-purple?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Q%26A-black?style=for-the-badge)

</p>

---

# 📖 Overview

PaperMind AI is an intelligent research paper assistant designed to make literature exploration faster and more effective.

Instead of only searching papers, the system helps users:

- 🔍 Discover relevant research papers using Semantic Search
- 📄 Understand papers through AI-generated summaries
- 💡 Explain complex papers in simple language
- 🧬 Extract scientific entities automatically
- 📊 Analyze research trends and statistics
- 🎯 Discover potential research gaps
- 🤖 Ask questions directly from retrieved papers using Retrieval-Augmented Generation (RAG)

The project combines multiple NLP techniques into a single end-to-end research workflow.

---

# 🎯 Motivation

Researchers often spend hours finding, reading, and comparing papers.

PaperMind AI aims to reduce that effort by combining modern NLP, vector search, scientific entity extraction, analytics, and RAG into one platform.

---

# ✨ Features

## 🔍 Semantic Search

Retrieve relevant research papers using

- Sentence Transformers
- FAISS Vector Search

instead of traditional keyword matching.

---

## 📄 Search → Summarize → Explain

Every retrieved paper can be

- summarized
- simplified
- explained in beginner-friendly language

using Large Language Models.

---

## 🧬 Scientific Named Entity Recognition

Extracts

- Methods
- Algorithms
- Datasets
- Metrics
- Scientific Terms

using **SciSpaCy**.

---

## 🏷 Automatic Keyword Extraction

Uses **KeyBERT** to automatically generate meaningful keywords for every research paper.

---

## ⚡ Hybrid Search

Improves retrieval quality by combining

- Semantic Similarity
- Scientific Entities
- Keywords

instead of relying only on embedding similarity.

---

## 🧠 Topic Clustering

Groups similar research papers using

- K-Means Clustering

to help users explore research domains.

---

## 📊 Research Analytics Dashboard

Visualizes

- Publication Trends
- Top Authors
- Popular Keywords
- Research Topics

through interactive charts.

---

## 🎯 Research Gap Finder

Helps identify

- less explored topics
- underrepresented research directions

for future work.

---

## 📈 Trend Analysis

Analyzes how research topics evolve over time.

---

## 🤖 Retrieval-Augmented Generation (RAG)

Users can ask questions such as

> "What are the latest applications of Large Language Models in Healthcare?"

The system retrieves relevant papers and generates context-aware answers grounded in the retrieved research instead of relying solely on the LLM's internal knowledge.

---

## 🖥 Interactive Gradio Interface

A complete web interface allowing users to

- Search
- Analyze
- Summarize
- Explore Trends
- Ask Questions

from one dashboard.

---

# 🏗 System Architecture

```
                User Query
                     │
                     ▼
        Sentence Transformer Embeddings
                     │
                     ▼
             FAISS Vector Database
                     │
          Top Relevant Research Papers
                     │
        ┌────────────┴────────────┐
        ▼                         ▼
Scientific NER              Keyword Extraction
        │                         │
        └────────────┬────────────┘
                     ▼
              Hybrid Re-ranking
                     │
                     ▼
      Search → Summarize → Explain
                     │
                     ▼
         Analytics & Trend Analysis
                     │
                     ▼
             RAG Question Answering
                     │
                     ▼
                Final Response
```

---

# 📷 Demo

## Semantic Search

![Semantic Search](images/semantic-search.png)

---

## Summarize & Explain

![Summary](images/summarize-explain.png)

---

## Scientific NER

![NER](images/scientific-ner.png)

---

## Topic Clustering

![Topic Clustering](images/topic-clustering.png)

---

## Research Analytics

![Analytics](images/analytics-dashboard.png)

---

## RAG Question Answering

![RAG](images/rag-qa.png)

---

# 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Language | Python |
| NLP | Sentence Transformers, SciSpaCy, KeyBERT |
| Retrieval | FAISS |
| LLM | Hugging Face Transformers |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Interface | Gradio |
| Data Source | arXiv API |

---

# 📦 Installation

```bash
git clone https://github.com/Guru3536/papermind-ai.git

cd papermind-ai

pip install -r requirements.txt
```

Launch the notebook

```bash
jupyter notebook papermind_ai.ipynb
```

or

Open the notebook directly in Google Colab.

---

# 🚀 Future Improvements

- PDF Upload Support
- Citation Generation
- Multi-document RAG
- Agentic Research Workflow
- LangGraph Integration
- Pinecone / Chroma Vector Database
- Cross-paper Comparison
- Personalized Research Recommendations

---

# 🙏 Acknowledgements

The foundational Semantic Search and Search → Summarize → Explain pipeline for this project was developed under the guidance of my mentor.

Building upon that foundation, I independently extended the platform by implementing:

- Scientific Named Entity Recognition (SciSpaCy)
- Hybrid Search
- Keyword Extraction
- Topic Clustering
- Research Analytics Dashboard
- Research Gap Finder
- Trend Analysis
- Retrieval-Augmented Generation (RAG) Question Answering
- Integrated Gradio Interface

This project has been an incredible learning experience in combining modern NLP and AI techniques into a practical research assistant.

---

# ⭐ If you found this project interesting,

consider giving it a ⭐ on GitHub!

