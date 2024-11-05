Conversational PDF Q&A System with LangChain, Hugging Face, and Chroma DB
This project provides a conversational Q&A system capable of answering questions based on a PDF document using embeddings and vector search. Leveraging LangChain, Hugging Face embeddings, and ChromaDB, it delivers concise and context-aware answers to user queries from any document provided.

📖 Features
PDF Document Loading and Splitting: Efficiently loads a PDF and splits it into manageable text chunks.
Embedding Generation: Uses Hugging Face embeddings (BAAI/bge-large-en-v1.5) to convert document text into vectorized format.
Vector Storage with Chroma DB: Stores document embeddings in a persistent vector database to support fast, accurate retrieval.
Conversational Retrieval Chain: A conversational interface for interacting with document-based knowledge, backed by memory to retain context across exchanges.
Customizable Prompting: Provides concise answers based on context and keeps responses brief.
🛠️ Installation
To get started, clone the repository and install the necessary packages:

bash
Copy code
git clone https://github.com/yourusername/conversational-pdf-qa.git
cd conversational-pdf-qa
pip install -r requirements.txt
🔍 Project Structure
Document Loading & Splitting: PyPDFLoader is used to load and split the PDF document.
Embedding with Hugging Face: We use HuggingFaceBgeEmbeddings to create embeddings of the document.
Chroma DB Vector Store: Stores these embeddings in a vector database for easy retrieval.
Conversational Q&A Chain: ConversationalRetrievalChain with prompt tuning and memory management.
