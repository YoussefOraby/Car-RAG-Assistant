# Car RAG Assistant

A context-aware chatbot that answers car-related questions using a car manual and Retrieval-Augmented Generation (RAG).

## Overview
This project transforms a static car manual into an intelligent assistant that can:
- Explain dashboard warning lights
- Provide recommended actions
- Answer user queries using real documentation

##  How it Works
1. Load car manual (HTML)
2. Split into chunks
3. Convert chunks into embeddings
4. Store in vector database (Chroma)
5. Retrieve relevant chunks based on user query
6. Generate answer using LLM

## Tech Stack
- LangChain
- OpenAI (LLM + Embeddings)
- ChromaDB
