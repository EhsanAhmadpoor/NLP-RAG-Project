# RAG-Based Book Recommendation System 📚🤖

This project implements a book recommendation system using Retrieval-Augmented Generation (RAG) techniques. The system retrieves relevant book descriptions from a large dataset and generates recommendations based on user queries using transformers models.

## Features
- Text similarity-based document retrieval using `sentence-transformers`.
- Text generation using various models from Hugging Face.
- Book recommendations based on user inputs using RAG.
- Utilizes datasets from Hugging Face for corpus generation.

## Models
- **Retriever**: `sentence-transformers/all-MiniLM-L6-v2`
- **Generators**: `microsoft/Phi-3-mini-128k-instruct`, `GPT-2`, `T5-small`

## Technologies
- Python
- Transformers (Hugging Face)
- Sentence-Transformers
- Hugging Face Datasets

## Usage
1. Customize the corpus and queries in the notebook for your own use case.
2. Use the retriever to find relevant documents based on user input.
3. Generate meaningful recommendations using different text generation models.

## Dataset
The project uses the [Goodreads Book Descriptions](https://huggingface.co/datasets/booksouls/goodreads-book-descriptions) dataset available on Hugging Face.
