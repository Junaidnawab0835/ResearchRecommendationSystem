# Research Paper Recommendation System

Project is a multi-label classifier and semantic recommender system built using arXiv paper metadata. It predicts subject areas for a paper based on its title and abstract and recommends similar papers using Sentence-BERT.

## Features

- Multi-label classification using MLPClassifier from Scikit-learn
- TF-IDF feature extraction on cleaned text
- Semantic search using SentenceTransformer (MiniLM)
- Evaluation with Accuracy
- CLI interface for interactive classification and recommendations

## Dataset

- Source: [arXiv Paper Abstracts on Kaggle](https://www.kaggle.com/datasets/spsayakpaul/arxiv-paper-abstracts)
- Format: `arxiv_data.csv` containing `titles`, `summaries`, and `terms`
- Required Columns: `titles`, `summaries`, `terms`

## Installation

Install dependencies in your environment or Colab:

```bash
pip install pandas numpy scikit-learn sentence-transformers torch joblib kagglehub
