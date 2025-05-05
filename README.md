# Retrieval-Augmented Generation (RAG) System for Open-Domain QA

## 📖 Project Description

This project implements an open-domain question answering (ODQA) system using a Retrieval-Augmented Generation (RAG) pipeline. It combines dense retrieval (Sentence-BERT + FAISS) with extractive QA (DeBERTa, BERT, RoBERTa) to answer factual questions from a Wikipedia corpus.

## 🚀 Features

- Dense semantic search using SBERT and FAISS.
- Fast retrieval (~30ms latency) even for large corpora.
- Extractive QA models return answers grounded in retrieved evidence.
- Supports custom questions for testing.
- Includes embedding space visualization (t-SNE).
- Modular code for easy extension.

## 🛠️ Requirements

- Python 3.8+
- Libraries:
  - `transformers`
  - `sentence-transformers`
  - `faiss`
  - `matplotlib`
  - `evaluate`
  - `scikit-learn`
  - `jupyter`

## 📂 Repository Structure

- `NLP_Project.ipynb` – Main Jupyter Notebook containing the full RAG pipeline.
- `NLP Project Final.pptx` – Slides presenting the project overview and results.
- `README.md` – Documentation file.
- `/figures/` – Contains images and charts (QA analysis, latency plots, embedding visualizations).
- `requirements.txt` – (Optional) Python dependencies list for easy setup.

## 👥 Team

- Yeswanth Labba (ylabb1@unh.newhaven.edu)
- Nagasai Jaja (njaja1@unh.newhaven.edu)
- Sravanthi Kadari (skada9@unh.newhaven.edu)

## 📄 References

- Lewis, P., et al. (2020). *Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks*. NeurIPS. https://arxiv.org/abs/2005.11401
- Reimers, N., & Gurevych, I. (2019). *Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks*. EMNLP. https://arxiv.org/abs/1908.10084
- He, P., et al. (2021). *DeBERTa: Decoding-enhanced BERT with Disentangled Attention*. ICLR. https://arxiv.org/abs/2006.03654
- Johnson, J., Douze, M., & Jégou, H. (2019). *Billion-scale similarity search with GPUs*. FAISS. https://github.com/facebookresearch/faiss
- Devlin, J., et al. (2019). *BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding*. NAACL. https://arxiv.org/abs/1810.04805
- Liu, Y., et al. (2019). *RoBERTa: A Robustly Optimized BERT Pretraining Approach*. arXiv. https://arxiv.org/abs/1907.11692
- Hugging Face Transformers Library. https://github.com/huggingface/transformers
- Hugging Face Evaluate Library. https://github.com/huggingface/evaluate

## 🔧 Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/Yeswanth-Labba/rag-qa-system.git
cd rag-qa-system
pip install -r requirements.txt

