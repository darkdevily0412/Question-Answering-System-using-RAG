# Question-Answering-System-using-RAG
Create a robust and user-friendly QA system based on RAG allowing users to ask questions and receive accurate answers based on PDF documents.

This project demonstrates the integration with an API that provides access to a pre-trained LLM like GPT, the extraction and storage of text from a PDF document into a vector store, and the development of a user interface for asking questions and receiving answers based on the provided PDF.

# Overview
Integration with LLM API
PDF Text Extraction and Vector Storage
User Interface for Querying the PDF
Documentation and Results

## Integration with LLM API

We have integrated our system with an API providing access to a pre-trained LLM like GPT. This allows us to utilize the language model's capabilities for understanding and generating human-like text.

## PDF Text Extraction and Vector Storage

We have used the following tools and libraries to extract text from a PDF document and store it in a vector store:

PyPDF2 for extracting text from PDF files
Langchain for text splitting and embedding
ChromaDB as the vector database

The text from the PDF document is split into chunks using a text splitter and then embedded using OpenAI embeddings. The embedded vectors are stored in ChromaDB for efficient querying and comparison.

## User Interface for Querying the PDF

We have developed a user interface using Flask, a lightweight web framework for Python. Users can input their questions, and the system will return answers based on the content of the provided PDF document.

## Documentation and Results
To be added based on the actual implementation and results.
