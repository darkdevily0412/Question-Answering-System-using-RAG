# Question-Answering-System-using-RAG 💡
Create a robust and user-friendly QA system based on RAG allowing users to ask questions and receive accurate answers based on PDF documents. 📄

## Overview 📊
- Integration with LLM API 🤖
- PDF Text Extraction and Vector Storage 💻
- User Interface for Querying the PDF 📝
- Documentation and Results 📄

## Integration with LLM API 🤖
We have integrated our system with an API providing access to a pre-trained LLM like GPT. This allows us to utilize the language model's capabilities for understanding and generating human-like text. 💬

## PDF Text Extraction and Vector Storage 💻
We have used the following tools and libraries to extract text from a PDF document and store it in a vector store:
- [PyPDF2](https://pypi.org/project/PyPDF2/) for extracting text from PDF files 📄
- [Langchain](https://github.com/hwchase17/langchain) for text splitting and embedding 📊
- [ChromaDB](https://www.chromadb.org/) as the vector database 💻

The text from the PDF document is split into chunks using a text splitter and then embedded using OpenAI embeddings. The embedded vectors are stored in ChromaDB for efficient querying and comparison. 🔍

## User Interface for Querying the PDF 📝
We have developed a user interface using Flask, a lightweight web framework for Python. Users can input their questions, and the system will return answers based on the content of the provided PDF document. 💬

## Documentation and Results 📄
To be added based on the actual implementation and results. 📝

## Technologies Used 🛠️
- [Python](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [PyPDF2](https://pypi.org/project/PyPDF2/)
- [Langchain](https://github.com/hwchase17/langchain)
- [ChromaDB](https://www.chromadb.org/)
