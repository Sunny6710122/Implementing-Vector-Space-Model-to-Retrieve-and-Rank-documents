# Implementing Vector Space Model to Retrieve and Rank Documents 📚🔍

This repository contains the implementation of a **Vector Space Model (VSM)** for retrieving and ranking documents based on their relevance to a query. The project leverages **TF-IDF scoring** and provides a user-friendly GUI for interaction.

## VSM Model Overview 🧠

This code implements a **basic Vector Space Model (VSM)** for text processing and retrieval using **natural language processing (NLP)** techniques. It computes **Term Frequency-Inverse Document Frequency (TF-IDF)** scores to rank and retrieve documents based on query relevance.

### Features 🌟

- **Text Preprocessing**: 🛠️ Includes text cleaning, stemming with PorterStemmer, and stopword removal.
- **TF-IDF Calculation**: 📊 Computes term frequency-inverse document frequency for terms in the corpus.
- **Query Processing**: 🔍 Processes text queries and computes their vector representation based on indexed terms.
- **Relevance Scoring**: 📈 Scores and ranks documents using cosine similarity with the query.

## Modules Required 🛠️

- **`numpy`**: For handling arrays and matrices.
- **`json`**: To store and retrieve TF-IDF vectors in JSON format.
- **`nltk`**: For stemming words (PorterStemmer).
- **`re`**: For regular expression-based text processing.
- **`streamlit`**: To run the `K21-4562_A2.py` application.

## File Structure 📂

- **`Stopword-List.txt`**: Contains a list of stopwords.
- **`ResearchPapers/`**: Directory with text documents in `.txt` format, each having a unique identifier.

---

Feel free to explore and experiment with the Vector Space Model for information retrieval and ranking! 🚀✨
