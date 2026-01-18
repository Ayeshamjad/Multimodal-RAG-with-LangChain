# Multimodal RAG with LangChain

Multi-modal Retrieval-Augmented Generation pipeline for PDFs using LangChain. Extracts and processes **text**, **tables**, and **images** from documents.

## Features
- High-res PDF partitioning with Unstructured.io
- Handles text, tables, images (base64), formulas
- Smart chunking (`by_title`)
- ChromaDB vector store
- Groq / OpenAI LLM 
