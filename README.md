# Textrank
This project demonstrates a text summarization technique using advanced natural language processing (NLP) methods. The core idea is to condense a large piece of text into a concise summary by identifying and ranking the most important sentences.

# Text Summarization Using GloVe Embeddings and PageRank Algorithm

This project implements a text summarization technique using sentence embeddings derived from GloVe (Global Vectors for Word Representation) and the PageRank algorithm to rank sentences based on their importance.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The goal of this project is to summarize a given piece of text by selecting the most important sentences. We achieve this by:
1. Tokenizing the text into sentences.
2. Cleaning and preprocessing the sentences.
3. Removing stopwords.
4. Representing each sentence as a vector using pre-trained GloVe embeddings.
5. Calculating sentence similarity using cosine similarity.
6. Applying the PageRank algorithm on the similarity matrix to rank sentences.
7. Selecting the top-ranked sentences for the summary.

## Installation
To run this project, you'll need to have Python installed along with several packages. You can install the required packages using `pip`:

```bash
pip install numpy pandas nltk scikit-learn networkx


Additionally, download the GloVe embeddings:
wget http://nlp.stanford.edu/data/glove.6B.zip
unzip glove.6B.zip
