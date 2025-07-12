# Restaurant-ReviewAI

## Overview
This project is a simple AI agent built using LangChain, Chroma, and Ollama to provide answers based on restaurant reviews. It processes a CSV file containing realistic restaurant reviews and uses a vector store to retrieve relevant information.

## Features
- Loads and processes restaurant reviews from a CSV file.
- Uses Chroma vector store with Ollama embeddings for efficient retrieval.
- Provides answers to user questions based on retrieved reviews using a language model.

## Prerequisites
- Python 3.x
- Required libraries: `langchain_ollama`, `langchain_chroma`, `pandas`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/tahangz/Restaurant-ReviewAI.git
   cd Restaurant-ReviewAI
2. Install dependencies:
```bash
pip install -r requirements.txt
````

### Install Ollama
```bash
curl -fsSL https://ollama.com/install.sh | sh
```
- Download Ollama and the `mxbai-embed-large` embedding model used in the project
- Download the `llama3.2` model used in the project

## Usage
Ensure the `realistic_restaurant_reviews.csv` file is in the project directory.
Run the main script:
```bash
python main.py
````

## Files
- `README.md`: Project documentation.
- `main.py`: Main script to interact with the AI agent.
- `vector.py`: Handles vector store creation and document embedding.
- `realistic_restaurant_reviews.csv`: Contains the restaurant reviews data.
- `requirements.txt`: Lists project dependencies.
- `chrome_langchain_db/`: Directory for the Chroma vector store (auto-generated).

## Contributing
Feel free to fork the repository and submit pull requests. Issues and feature requests are welcome!
