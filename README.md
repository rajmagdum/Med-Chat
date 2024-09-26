# Medical Chatbot
A medical chatbot application that uses OpenAI's GPT models and FAISS for embedding and retrieving medical text information from a PDF document.

## Project Structure
### Prerequisites

Ensure you have Python 3.8+ installed. Clone the repository and install dependencies.

## Clone the repository
```bash
git clone https://github.com/your-repo/medical-chatbot.git
```
## Navigate to the project directory
```bash
cd medical-chatbot
```
## Install the required Python packages
```bash
pip install -r requirements.txt
```
## OR for development purposes
```bash
pip install -e .
```
Set Up Environment Variables
Create a .env file in the project root with the following values:
## .env file
```bash
OPENAI_API_KEY=your-openai-api-key
OPENAI_API_BASE=https://api.openai.com/v1
```

Create FAISS Index
Before running the chatbot, create the FAISS index for the PDF document.

## Run the script to generate the FAISS index
```bash
python store_index.py
```
## Running the Application

### Start the Flask server
```bash
python app.py
```
 
