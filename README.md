# Semantic Book Recommendation System using LLMs & Emotion-Aware Filtering

This project is an intelligent book recommendation system that uses **sentence embeddings**, **semantic search**, and **emotion analysis** to suggest books based on a user's input query. Built using Hugging Face Transformers, LangChain, ChromaDB, and Gradio.

---

## Features

- **Semantic Search**: Understands user queries beyond keywords using Hugging Face sentence embeddings.
- **Emotion-Aware Filtering**: Sorts recommendations based on emotional tone (joy, sadness, surprise, etc.).
- **LLM & Embedding-based Vector Search**: Powered by `sentence-transformers/all-MiniLM-L6-v2`.
- **Interactive Gradio Dashboard**: Clean and user-friendly web UI to explore recommendations.
- **Categorical Filtering**: Filter books by genre or category like Fiction, Nonfiction or Children's fiction, Nonfiction.

---
## Dataset
[Source: 7k+ Books with Metadata – Kaggle](https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata)

Dataset contains titles, authors, descriptions, categories, thumbnail URLs, and emotion scores

## Requirements

Make sure you have Python 3.8+ installed. Then install the required packages: 
<pre> ``` pip install pandas numpy seaborn matplotlib kagglehub ipywidgets python-dotenv \ langchain-community langchain-chroma transformers sentence-transformers notebook gradio ``` </pre>

## Acknowledgements
Thanks to Hugging Face, LangChain, and Gradio for the amazing open-source tools!
