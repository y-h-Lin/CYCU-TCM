Here's an English README for your script:

# Medical AI Assistant for Taipei City Hospital

This Python script implements an AI-powered medical assistant specifically designed for Taipei City Hospital's Traditional Chinese Medicine (TCM) department. It utilizes advanced natural language processing techniques to provide accurate and informative responses to patient queries.

## Features

- **Dual Response System**: Implements both a pure language model (LLM) and a Retrieval-Augmented Generation (RAG) system for comprehensive answers.
- **Web Scraping**: Automatically retrieves and processes information from specified hospital websites.
- **Vector Database**: Creates and maintains a FAISS vector store for efficient information retrieval.
- **Answer Evaluation**: Utilizes a sophisticated evaluation system to assess the quality of generated responses.
- **NVIDIA AI Integration**: Leverages NVIDIA's AI models for enhanced performance.

## Key Components

- **LLM Model**: Uses Meta's LLaMA 3 70B Instruct model for general language understanding and generation.
- **Embedding Model**: Employs NVIDIA's nv-embedqa-e5-v5 for text embedding.
- **Reranker**: Implements NVIDIA's reranking model for improved retrieval accuracy.

## Evaluation Criteria

The system evaluates responses based on:
- Accuracy
- Completeness
- Harmfulness (inverse scale)

## Setup and Usage

1. Ensure you have the required Python libraries installed.
2. Set up your NVIDIA API key in the environment variables.
3. Run the script to initialize the system and process test queries.

## Output

The script provides:
- Detailed responses for each test question
- Evaluation scores for both pure LLM and RAG responses
- A summary table comparing average scores across evaluation criteria

## Note

This system is designed for research and development purposes. Always consult with healthcare professionals for medical advice.
