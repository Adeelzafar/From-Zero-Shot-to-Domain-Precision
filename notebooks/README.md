# Automotive NER: Fine-grained Entity Extraction from Service Reports
Official implementation and datasets for the paper: "Extracting Fine-Grained Technical Entities from Unstructured Automotive Service Reports" 

📌 Project Overview
Automotive service reports are a goldmine for data-driven fault diagnosis, but they are notoriously difficult to process due to:

Domain Jargon: Highly specialized technical terminology.

Low Resource: Lack of publicly available labeled datasets.

Structural Variability: Mix of structured DTCs and unstructured technician notes.

This repository provides a framework to bridge this gap using template-based data synthesis and domain-adapted Transformer models (WG-BERT, RoBERTa), compared against zero-shot baselines (GLiNER).
# Core NLP and Transformer Models
transformers>=4.30.0
torch>=2.0.0
gliner>=0.1.0

# Data Processing and Numerical Operations
pandas>=1.5.0
numpy>=1.24.0
scikit-learn>=1.2.0

# Evaluation and Utilities
seqeval>=1.2.2
tqdm>=4.65.0
accelerate>=0.20.0

# Language Support (if using specific tokenizers)
sentencepiece>=0.1.99
