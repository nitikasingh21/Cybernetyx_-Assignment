# FastAPI ChromaDB Document Search

This project demonstrates how to set up a FastAPI server with ChromaDB to ingest documents (TXT, DOCX, PDF) and search them using Sentence Transformer-based embeddings.

## Project Overview

This application provides an API for uploading, indexing, and searching documents using the ChromaDB vector store. It uses FastAPI to serve the endpoints and ChromaDB to store and search document embeddings.

### Key Features:
- **Document Upload**: Upload documents (TXT, DOCX, PDF) to be indexed.
- **Embedding Generation**: Generate embeddings using the Sentence Transformers model.
- **Search Functionality**: Query the documents and retrieve relevant results based on text embeddings.

## Prerequisites

Before running the application, make sure you have the following installed:

- Python 3.10+
- pip (Python package manager)

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/fastapi-chromadb-document-search.git
   cd fastapi-chromadb-document-search
