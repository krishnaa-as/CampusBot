# ollama-chatbot


# Campus Bot

A Streamlit-based chatbot that can answer questions from a PDF document using LlamaIndex and Ollama.

## Features

- Upload or use a PDF document.
- Ask questions in natural language.
- Chat interface with persistent conversation history.
- Powered by Ollama LLM and embeddings via LlamaIndex.

## Installation & Setup

1. Clone the repository
    ```bash
    git clone https://github.com/krishnaa-as/ollama-chatbot.git
    cd ollama-chatbot

2. Install Python dependencies
    pip install -r requirements.txt

3.Install Ollama
    Pull the Llama model 
        ollama pull llama3.2:1b
    Make sure Ollama is running locally for the chatbot to work.

4.Run the App
    Start the Streamlit app with:
       streamlit run chatbot.py
