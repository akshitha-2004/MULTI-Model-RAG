# MULTI-Model-RAG
**# MultiRAG – Multimodal Retrieval-Augmented Generation

## Overview

MultiRAG is a **Multimodal Retrieval-Augmented Generation (RAG)** system designed to process both **text and images** from documents and enable intelligent retrieval-based responses using Large Language Models (LLMs).

This project extracts content from PDF documents, summarizes textual and visual information, converts them into vector embeddings, stores them in a vector database, and retrieves the most relevant context to generate accurate answers.

## Features

* PDF document processing
* Text extraction and chunking
* Image extraction and semantic image summarization
* Text and image embedding generation
* Vector storage using ChromaDB
* Retrieval-based response generation
* Multimodal search and question answering

## Technologies Used

* Python
* LangChain
* ChromaDB
* Hugging Face Embeddings
* Google Generative AI (Gemini)
* Docling
* Ollama
* Pillow

## Project Workflow

1. Load and process PDF documents
2. Extract text and images
3. Chunk document content
4. Generate summaries for text and images
5. Convert summaries into embeddings
6. Store embeddings in ChromaDB
7. Retrieve relevant information for user queries
8. Generate final responses using an LLM

## Installation

Clone the repository:

```bash
git clone <your-repository-link>
cd <repository-name>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the notebook:

```bash
jupyter notebook
```

Open:

```text
Multirag.ipynb
```

Execute cells sequentially to build the multimodal retrieval pipeline.

## Folder Structure

```text
project/
│
├── Multirag.ipynb
├── chroma_mragdb/
├── data/
├── requirements.txt
└── README.md
```

## Future Improvements

* Support multiple document formats
* Improve retrieval accuracy
* Add web interface
* Enable real-time document uploads
* Optimize vector search performance

## Author

Akshitha Kuchana

## License

This project is for educational and learning purposes.
**
