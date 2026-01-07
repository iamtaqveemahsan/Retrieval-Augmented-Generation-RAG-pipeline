# Retrieval-Augmented-Generation-RAG-pipeline
This RAG workflow automates document ingestion and AI retrieval using n8n and LangChain. It monitors Google Drive for new files, converts them into OpenAI embeddings, and stores them in Pinecone. An AI Agent uses this index to provide accurate answers based on custom data. It ensures the bot only answers from provided support documents.
