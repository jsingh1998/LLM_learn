# FastAPI AI Chat API with API Key Authentication

This FastAPI application provides an endpoint to generate AI responses using the Mistral model from Ollama. API requests require a valid API key with available credits.

## Features
- **API Key Authentication**: Uses API keys with credit limits to control access.
- **Ollama Integration**: Calls the Mistral model to generate AI responses.
- **Dependency Injection**: Uses FastAPI's `Depends` to verify API keys.
- **Environment Variables**: Loads API keys from a `.env` file.
