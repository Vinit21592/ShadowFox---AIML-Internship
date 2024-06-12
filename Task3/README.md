# RAG Application
End to end RAG application using langchain as framework and Pinecone ChromaDB as vectordb

# Introduction
------------
The is a application that allows you to chat with PDF documents. You can ask questions about the PDFs using natural language, and the application will provide relevant responses based on the content of the documents. This app utilizes a language model to generate accurate answers to your queries. Please note that the app will only respond to questions related to the loaded PDFs.

# How It Works
------------
![PDF-LangChain](https://github.com/Vinit21592/End-to-End-MultiPDF-ChatBot/assets/78821357/c73f1d85-8d6f-426c-af4c-ab103d962a30)

The application follows these steps to provide responses to your questions:

1. PDF Loading: The app reads multiple PDF documents and extracts their text content.

2. Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

3. Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

4. Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

5. Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.


# Techstack Used
------------
- Python
- LangChain
- Flask
- Meta Llama2 OR google/flan-t5-xxl
- Pinecone
