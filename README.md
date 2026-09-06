# Document Classification Using Traditional Machine Learning and Transformer Models

A comparative Natural Language Processing (NLP) project that evaluates traditional machine learning, BERT, DistilBERT, and ensemble learning approaches for document classification.

## Overview

This project investigates the performance of different document classification approaches across two datasets with different characteristics:

- **AG News** — general news topic classification.
- **MSME Legal Dispute Classification** — domain-specific legal dispute documents.

The project progresses from traditional NLP pipelines using Bag of Words (BoW) and TF-IDF to Transformer-based models using BERT and DistilBERT. A final ensemble model combines BERT and DistilBERT predictions using soft voting.

The objective is to compare how different machine learning and Transformer-based approaches perform on general-domain and domain-specific text classification tasks.

---

## Datasets

### Dataset 1: AG News

The AG News dataset is used for news topic classification. A subset of the dataset was used in this project with four classes:

- World
- Sports
- Business
- Sci/Tech

### Dataset 2: MSME Legal Dispute Classification

The MSME dataset contains legal dispute documents. The project uses samples from four classes:

- Delayed Payment (No Dispute)
- Quality Dispute
- No Formal Contract
- Partial Payment Dispute

---

## Project Workflow

```text
Raw Datasets
     │
     ▼
Text Preprocessing
     │
     ├── Tokenization
     ├── Case Folding
     ├── Stemming
     ├── Punctuation Removal
     └── Stopword Removal
     │
     ▼
Feature Extraction
     │
     ├── Bag of Words (BoW)
     └── TF-IDF
     │
     ▼
Traditional Machine Learning
     │
     ├── Naive Bayes
     ├── Logistic Regression
     └── Support Vector Machine
     │
     ▼
Transformer Models
     │
     ├── BERT
     └── DistilBERT
     │
     ▼
Hyperparameter Experiments
     │
     ▼
Ensemble Learning
     │
     └── Soft Voting
     │
     ▼
Performance Evaluation