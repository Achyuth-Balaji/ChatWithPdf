# 📘 Conversational PDF Q&A System

A conversational Q&A system built to answer questions based on PDF documents. This project leverages LangChain, Hugging Face embeddings, and ChromaDB for efficient document retrieval and accurate, context-aware responses.

## 🔥 Key Features 

PDF Document Loading and Splitting: Efficiently loads a PDF and splits it into manageable text chunks.

Embedding Generation: Uses Hugging Face embeddings (BAAI/bge-large-en-v1.5) to convert document text into vectorized format.

Vector Storage with Chroma DB: Stores document embeddings in a persistent vector database to support fast, accurate retrieval.

Conversational Retrieval Chain: A conversational interface for interacting with document-based knowledge, backed by memory to retain context across exchanges.

Customizable Prompting: Provides concise answers based on context and keeps responses brief.


