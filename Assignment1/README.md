# RAG Assignment – Agentic AI

## Objective

Build a simple Retrieval Augmented Generation (RAG) system using LangChain and HuggingFace.

## Features

* Loads text data from a file
* Splits text into chunks
* Converts text into embeddings
* Stores embeddings using FAISS
* Retrieves relevant context for user query
* Generates answers using GPT-2

## How to Run

1. Create virtual environment

```
python -m venv venv
venv\Scripts\activate
```

2. Install dependencies

```
pip install -r requirement.txt
```

3. Run the project

```
python app.py
```

## Example

Ask:

```
What is AI?
```

The system retrieves relevant context and generates an answer.

## Tools Used

* Python
* LangChain
* FAISS
* HuggingFace Transformers
* Sentence Transformers

