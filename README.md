# Book Embedding and Similarity Search with Faiss

This repository contains a notebook that demonstrates how to create a book similarity search system using text embeddings. The process involves loading a dataset of books, generating embeddings for each book's description, and then using Faiss (a library for efficient similarity search) to find the most similar books.

## Overview

In this project, we perform the following steps:

1. **Data Loading**: Download a dataset of books and load it into a pandas DataFrame.
2. **Data Preprocessing**: Clean and preprocess the data by removing missing values, duplicates, and normalizing text.
3. **Textual Representation**: Format the book data into a textual representation that includes relevant metadata such as title, authors, description, and more.
4. **Embedding Generation**: Use an external API to generate sentence embeddings for each book description.
5. **Faiss Indexing**: Create a Faiss index to store and efficiently search through the embeddings.
6. **Search Similarity**: Use Faiss to perform similarity searches and retrieve the most similar books based on a query book.
7. **Search Similarity**: Use Faiss to perform similarity searches and retrieve the most similar books based on a query book.

## Requirements

Before running the code, make sure to install the following dependencies:

- Python 3.x
- `faiss`
- `sentence-transformers`
- `requests`
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `kagglehub`

You can install the necessary packages using pip:

```bash
pip install faiss-cpu sentence-transformers requests pandas numpy matplotlib scikit-learn kagglehub
```
