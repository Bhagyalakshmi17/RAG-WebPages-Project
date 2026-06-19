# RAG WebPages Project

## Overview
This project demonstrates a simple Retrieval-Augmented Generation (RAG) pipeline using web scraping, text chunking, embeddings, similarity search, and FLAN-T5 answer generation.

## Technologies Used
- Python
- BeautifulSoup
- Requests
- LangChain
- Sentence Transformers
- Scikit-learn
- Hugging Face Transformers

## Workflow

### Step 1: Web Scraping
Extract text content from a Wikipedia article using BeautifulSoup.

### Step 2: Text Chunking
Split the extracted text into smaller chunks for retrieval.

### Step 3: Embeddings
Convert text chunks into vector embeddings using Sentence Transformers.

### Step 4: Similarity Search
Find the most relevant chunk using cosine similarity.

### Step 5: Prompt Construction
Build a prompt using the retrieved context and user question.

### Step 6: Load FLAN-T5 Model
Load Google's FLAN-T5 model for answer generation.

### Step 7: Answer Generation
Generate answers based on retrieved context.

## Sample Question
Why is NLP important?

## Sample Generated Answer
NLP is closely associated with artificial intelligence and enables computers to understand and process human language.

## Files Included
- RAG_WebPages.ipynb
- Web Scraping Screenshot
- Text Chunking Screenshot
- Embeddings Screenshot
- Similarity Search Screenshot
- Prompt Construction Screenshot
- FLAN-T5 Loading Screenshot
- Generated Answer Screenshot


