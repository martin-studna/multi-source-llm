# Retrieval-Augmented Generation (RAG) for Q&A

This repository demonstrates how to create a RAG system for Q&A using multiple data sources.

## Data Sources
1. **Langchain Documentation**: Scraped using `WebBaseLoader` and stored in a FAISS vector database.
2. **Wikipedia**: Retrieved using `WikipediaApiWrapper`.
3. **arXiv**: Research papers fetched using `ArxivApiWrapper`.

## Features
- Combines structured data and language model for enhanced Q&A.
- Integrates information from diverse and authoritative sources.

## Contents
- `rag_system.ipynb`: Jupyter notebook with implementation details and code.

## Usage
Run the provided notebook to set up the RAG system and start answering questions using integrated data sources.