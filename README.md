# NLP Text Classification: Embedding Comparison Study

This repository contains two Google Colab notebooks developed as part of a Natural Language Processing study. The notebooks' comments are written in Spanish and are intended to be executed in the Google Colab environment using Python.

## Overview

The objective of this project is to compare different text representation techniques and language models across two text classification tasks:

1. **Sentiment Analysis**
2. **Multi-label Classification of Scientific Texts**

The study evaluates the impact of different embedding methods on classification performance and analyzes the advantages and limitations of each approach.

## Embedding Methods Evaluated

The following text representation techniques are compared:

* TF-IDF
* Word2Vec
* GloVe
* FastText
* BERT Base (Fine-Tuning)

## Repository Structure

```text
├── sentiment_analysis.ipynb
├── scientific_text_multilabel_classification.ipynb
└── README.md
```

## Methodology

For each task, several text representations are generated and used to train classification models. Traditional embedding approaches are compared against a fine-tuned Transformer model (BERT Base).

The experiments focus on:

* Data preprocessing
* Feature extraction
* Model training
* Performance evaluation
* Comparative analysis of results

## Requirements

The notebooks are designed to run on Google Colab.

Main libraries used include:

* Python 3
* NumPy
* Pandas
* Scikit-learn
* Gensim
* NLTK
* Transformers (Hugging Face)
* PyTorch

## Language

The notebooks, comments, explanations, and outputs are written in Spanish.

## Academic Context

This repository was created as supporting material for academic work in Natural Language Processing and Machine Learning. The code is provided to facilitate reproducibility of the experiments and results.

## Author

Nolhan Denis Alonso Guignon

BSc in Mathematics and Data Science

Complutense University of Madrid
