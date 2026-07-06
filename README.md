# 🩺 From Accuracy to Clinical Nuance

> **A Comparative Study of ICD-10 Coding Models Across Classical, Deep, and LLM Paradigms**

**Master's Thesis Project**  
**MSc Data Science — Sapienza University of Rome**

---

## 📖 Overview

Medical coding plays a critical role in healthcare by transforming clinical narratives into standardized **ICD-10 codes** used for disease surveillance, hospital reimbursement, epidemiological research and healthcare planning. Despite significant advances in Artificial Intelligence, automated ICD-10 coding remains a challenging task due to the complexity of clinical language, the large number of diagnostic categories and the long-tail distribution of medical codes.

This project presents a comprehensive comparative study of **Classical Machine Learning**, **Deep Learning**, **Transformer-based models**, and **Large Language Models (LLMs)** for automated ICD-10 coding.

Rather than focusing solely on predictive accuracy, the research investigates how modern AI systems perform across multiple dimensions including clinical reliability, calibration, computational efficiency and rare disease prediction. The project also explores **Retrieval-Augmented Generation (RAG)** to improve LLM performance using external ICD-10 medical knowledge.

---

# 🎯 Research Objectives

This research was designed to:

- Compare multiple generations of ICD-10 coding models
- Evaluate the effectiveness of Large Language Models for clinical coding
- Investigate Retrieval-Augmented Generation (RAG) for medical knowledge retrieval
- Improve prediction of rare ICD-10 diagnoses
- Measure clinical reliability beyond traditional accuracy metrics
- Compare computational efficiency and scalability of modern AI approaches

---

# 🏗️ End-to-End AI Pipeline

> *(Architecture diagram will be added here.)*

```text
Clinical Death Certificates
            │
            ▼
Data Cleaning & Preprocessing
            │
            ▼
Medical Text Translation
            │
            ▼
Feature Engineering
            │
            ▼
ICD-10 Knowledge Base
            │
            ▼
Embedding & Retrieval
            │
            ▼
Model Training / Inference
            │
 ┌──────────┼──────────┐
 ▼          ▼          ▼
Classical   Deep      LLMs
 Models    Learning
            │
            ▼
 Retrieval-Augmented Generation
            │
            ▼
 ICD-10 Prediction
            │
            ▼
 Model Evaluation
```

---

# 🤖 AI Models Evaluated

The study compares multiple generations of AI models.

| Category | Models |
|-----------|--------|
| Classical Machine Learning | TF-IDF + Random Forest, TF-IDF + XGBoost |
| Deep Learning | Word2Vec + LSTM |
| Transformer Models | DistilBERT, BERT |
| Large Language Models | Llama, Gemma, Mistral, Qwen |
| Retrieval-Augmented Generation | LangChain + ChromaDB + LLM |

This comparative approach highlights the strengths and limitations of each modelling paradigm for automated ICD-10 coding.

---

# 📊 Evaluation Metrics

Unlike many medical coding studies that report only predictive accuracy, this research evaluates models across multiple complementary dimensions.

Performance metrics include:

- Accuracy
- Precision
- Recall
- Micro-F1 Score
- Macro-F1 Score
- Rare-Class F1
- Top-k Accuracy
- Hierarchical Accuracy
- Expected Calibration Error (ECE)
- Training Time
- Inference Time

These metrics provide a more comprehensive assessment of clinical usefulness and model reliability.

---

# 🧠 Retrieval-Augmented Generation (RAG)

A Retrieval-Augmented Generation (RAG) pipeline was implemented to enhance LLM predictions using external ICD-10 medical knowledge.

The RAG workflow combines:

- ICD-10 knowledge base
- Embedding models
- ChromaDB vector database
- LangChain retrieval
- Prompt engineering
- Large Language Models

By providing clinically relevant context during inference, the RAG pipeline aims to improve coding accuracy and reduce hallucinations.

---

# 🏥 Dataset

The experiments were conducted using anonymized mortality records containing clinical descriptions and corresponding ICD-10 codes.

Dataset preparation included:

- Medical text preprocessing
- Translation and normalization
- ICD-10 code validation
- Feature engineering
- Train, validation and test splitting

The resulting dataset supports large-scale multi-class ICD-10 classification across a diverse range of medical conditions.

---

# 📂 Repository Structure

```text
from-accuracy-to-clinical-nuance/
│
├── architecture/
├── data/
├── docs/
├── notebooks/
├── screenshots/
├── src/
├── thesis/
├── README.md
├── LICENSE
└── requirements.txt
```

---

# 📚 Documentation

Comprehensive technical documentation is available in the **docs** folder.

| Document | Description |
|-----------|-------------|
| architecture.md | End-to-End AI Architecture |
| dataset.md | Dataset Preparation |
| preprocessing.md | Data Cleaning & Feature Engineering |
| rag.md | Retrieval-Augmented Generation Pipeline |
| llm.md | Prompt Engineering & Large Language Models |
| evaluation.md | Experimental Setup & Evaluation Metrics |
| results.md | Comparative Results & Discussion |

---

# 🚀 Key Contributions

- Comprehensive comparison of Classical ML, Deep Learning, Transformers and LLMs
- Retrieval-Augmented Generation for ICD-10 coding
- Multi-dimensional evaluation beyond predictive accuracy
- Investigation of rare disease classification
- Clinical reliability and calibration analysis
- Scalable AI workflow for automated medical coding

---

# 🔮 Future Work

Potential extensions include:

- Fine-tuning larger medical LLMs
- Multilingual clinical coding
- Hierarchical ICD-10 prediction
- Real-time clinical decision support
- Explainable AI (XAI) for medical coding
- Integration with Electronic Health Record (EHR) systems

---

# 🎓 Academic Context

This repository accompanies the Master's thesis:

**From Accuracy to Clinical Nuance: A Comparative Study of ICD-10 Coding Models Across Classical, Deep, and LLM Paradigms**

Submitted in partial fulfillment of the requirements for the **MSc in Data Science** at **Sapienza University of Rome**.

---

# 👨‍💻 Author

**Ousainou Panneh**

**Data Engineer | AI Engineer | Data Scientist**

Master's in Data Science — Sapienza University of Rome
