Skip-Gram with Negative Sampling on Wikipedia
📌 Project Overview

This project presents a from-scratch implementation of the Skip-Gram model with Negative Sampling (SGNS) trained on a large-scale Wikipedia text corpus. The goal is to learn meaningful word embeddings and evaluate their quality through similarity analysis, analogy reasoning, and bias inspection.

The learned embeddings are compared against Gensim’s Word2Vec implementation using cosine similarity. In addition, the project evaluates semantic relationships via word analogy tasks and explores social bias in word embeddings, inspired by the discussion in Chapter 5 of the referenced material.

📚 Dataset

Corpus: Wikipedia text dump (enwik8)

Source: https://mattmahoney.net/dc/textdata.html

Size: ~100 MB

Description: Cleaned and preprocessed English Wikipedia text

🧠 Project Objectives

Implement Skip-Gram with Negative Sampling (SGNS) from scratch without relying on Gensim’s internal training routines

Train word embeddings on a large Wikipedia corpus

Compare custom-trained embeddings with Gensim Word2Vec using cosine similarity

Evaluate embeddings using word analogy tasks (e.g., semantic and syntactic relationships)

Analyze and identify social bias present in the learned word embeddings
