# RAG (Retrieval-Augmented Generation) Application

This project demonstrates how to build a RAG application using PDF documents as a data source. It leverages a combination of open-source libraries, including `llama-index`, `transformers`, and `PyPDF2`, to create a vector store index and generate text-based responses.

## Table of Contents
- [Features](#features)
- [Installation](#installation)


## Features
- Extracts text from PDF documents to create a knowledge base.
- Builds or loads a vector store index from extracted documents.
- Uses a Hugging Face embedding model for document vectorization.
- Employs a text generation pipeline for generating responses to queries.

## Installation
Ensure you have Python installed and run the following commands to install the required libraries:

```bash
pip install llama-index
pip install llama-index-embeddings-huggingface
pip install PyPDF2
pip install transformers
pip install torch
pip install accelerate
