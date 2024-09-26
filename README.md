# Medical Chatbot with FAISS and OpenAI GPT

This is a medical chatbot built using Flask, FAISS (Facebook AI Similarity Search), and OpenAI's GPT models. The chatbot leverages FAISS for efficient retrieval of text from a medical PDF document, which is embedded into vector space. The chatbot uses OpenAI's GPT model to generate responses to user queries.

## Features
- Extracts and embeds text from medical PDFs.
- Uses FAISS for efficient vector-based retrieval.
- Employs OpenAI's GPT models for natural language responses.
- Simple web interface using Flask.

## Requirements
You need the following tools installed to run this project:
- Python 3.8+
- FAISS for efficient vector search.
- Flask for serving the web application.
- PyPDF2 for PDF text extraction.
- LangChain for integrating with FAISS and OpenAI's GPT models.

## Python Dependencies
The required Python packages are listed in `requirements.txt`:
```bash
langchain==0.0.332
flask
flask[async]
pypdf2
python-dotenv
faiss-cpu
openai==0.28.0
tiktoken
-e .
