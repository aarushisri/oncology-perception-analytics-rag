# Oncology Perception Analytics Assistant (RAG)

AI-powered oncology research intelligence assistant built using Retrieval-Augmented Generation (RAG), ChromaDB, Sentence Transformers, and Gemini.

## Business Problem

Pharmaceutical and healthcare organizations generate thousands of research publications, clinical studies, and scientific articles every year. Traditional keyword search methods often fail to identify meaningful relationships across large volumes of unstructured data.

This project demonstrates how AI-powered Retrieval-Augmented Generation (RAG) can be used to transform unstructured oncology research into actionable, executive-ready insights.

The solution enables users to ask natural language questions and receive evidence-based responses grounded in relevant oncology publications.

---

## Project Objectives

- Analyze large volumes of oncology research publications
- Enable semantic search across unstructured medical literature
- Generate executive-ready insights using Large Language Models (LLMs)
- Demonstrate AI-enabled analytics aligned with pharmaceutical analytics use cases
- Showcase Retrieval-Augmented Generation (RAG) architecture for healthcare intelligence

---

## Technology Stack

| Component | Technology |
|------------|------------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Embedding Model | Sentence Transformers (all-MiniLM-L6-v2) |
| Vector Database | ChromaDB |
| Large Language Model | Gemini 2.5 Flash |
| Development Environment | Google Colab |
| Domain | Oncology Research Analytics |

---

## Dataset

The project uses publicly available oncology and healthcare research publications containing:

- Research article titles
- Publication summaries
- Research topics and classifications
- Source publication metadata

Dataset Size:

- ~10,000 oncology research publications
- Sample subset of 500 documents used for prototype development

---

## Solution Architecture

```text
User Query
     ↓
Sentence Transformer Embeddings
     ↓
ChromaDB Vector Search
     ↓
Top Relevant Research Articles
     ↓
Gemini 2.5 Flash
     ↓
Executive Insight Generation
```

---

## Workflow

### 1. Data Preparation

- Loaded oncology publication dataset
- Removed incomplete records
- Combined titles and summaries into searchable documents
- Created development sample for rapid prototyping

### 2. Embedding Generation

- Generated semantic embeddings using Sentence Transformers
- Converted research articles into vector representations

### 3. Vector Database Creation

- Stored embeddings inside ChromaDB
- Enabled semantic similarity search

### 4. Retrieval

- User query converted into embeddings
- Most relevant oncology publications retrieved

### 5. Insight Generation

- Retrieved documents passed to Gemini
- Gemini generates:
  - Executive Summary
  - Key Themes
  - Emerging Trends
  - Strategic Implications
  - Supporting Evidence

---

## Sample Query

```text
What are emerging trends in targeted cancer therapy?
```

### Example Output

#### Executive Summary

Emerging trends in targeted cancer therapy are focused on harnessing and modifying the body's own immune system to combat cancer, particularly solid tumors.

#### Key Themes

- Immunomodulation within the Tumor Microenvironment
- Advanced Cell-Based Therapies
- Targeting Solid Tumors

---

## Screenshots

### Semantic Retrieval

![Retrieval Results](screenshots/retrieval_results.png)

### RAG Insight Generation

![RAG Output](screenshots/rag_output.png)

---

## Key Capabilities Demonstrated

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Databases
- LLM-Powered Insight Generation
- Knowledge Synthesis
- Unstructured Data Analytics
- AI-Driven Decision Support
- Healthcare Research Intelligence

---

## Future Enhancements

- Biomedical-specific embedding models
- Source citation generation
- Topic-based filtering
- Interactive dashboard using Streamlit
- Full dataset deployment
- Agentic AI workflows
- Evaluation framework for hallucination detection

---

## Author

**Aarushi Srivastava**

https://www.linkedin.com/in/aarushi-srivastava/



LinkedIn: https://linkedin.com/in/aarushi-srivastava
