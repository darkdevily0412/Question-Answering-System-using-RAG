# Question-Answering-System-using-RAG 💡

Create a robust and user-friendly QA system based on RAG (Retrieval-Augmented Generation) that allows users to ask questions and receive accurate answers based on PDF documents. 📄

## Overview 📊

- Integration with LLM API 🤖
- PDF Text Extraction and Vector Storage 💻
- User Interface for Querying the PDF 📝
- Documentation and Results 📄

## Importance and Impact 💡

Question-Answering (QA) systems are becoming increasingly important in today's world, where information is abundant and constantly changing. A QA system that can accurately and efficiently extract information from PDF documents can have a significant impact on various industries, including education, healthcare, finance, and legal.

By integrating a QA system with a pre-trained LLM (Language Model), we can leverage the language model's capabilities for understanding and generating human-like text. This can lead to more natural and accurate answers to user queries.

Moreover, by storing the embedded vectors of the text in a vector database like ChromaDB, we can efficiently query and compare the vectors, leading to faster and more accurate answers.

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

## Workflow 🔄

- Development: Develop the QA system using Python, Flask, PyPDF2, Langchain, and ChromaDB.
- Testing: Test the system using Jupyter Notebook and Hugging Face.
- Deployment: Deploy the system using a cloud service provider.
- Monitoring: Monitor the system for any issues and make necessary updates.
