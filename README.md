# Medical Chatbot

A medical chatbot application that uses OpenAI's GPT models and FAISS for embedding and retrieving medical text information from a PDF document.

## Project Structure


## Getting Started

### Prerequisites

Ensure you have Python 3.8+ installed. Clone the repository and install dependencies.

```bash
# Clone the repository
git clone https://github.com/your-repo/medical-chatbot.git

# Navigate to the project directory
cd medical-chatbot

# Install the required Python packages
pip install -r requirements.txt

# OR for development purposes
pip install -e .
```
Set Up Environment Variables
Create a .env file in the project root with the following values:
```bash
# .env file
OPENAI_API_KEY=your-openai-api-key
OPENAI_API_BASE=https://api.openai.com/v1
```

Create FAISS Index
Before running the chatbot, create the FAISS index for the PDF document.
```bash
# Run the script to generate the FAISS index
python store_index.py
```
Running the Application
Run the Flask application:
```bash
# Start the Flask server
python app.py
```
 
