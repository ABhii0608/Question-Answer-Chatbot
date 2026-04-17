# 💬 Groq Q&A Chatbot with Streamlit

A simple, fast, and interactive **Q&A Chatbot** powered by **Groq** LLM. Built using **LangChain** and **Streamlit**, this application allows users to chat with various high-performance Groq models in a clean conversational interface.

## Features

- **Multiple Groq Models Support**: Choose from latest Llama models and other Groq-hosted models
- **Conversational Memory**: Maintains full chat history across the session
- **Customizable Parameters**: Adjust Temperature and Max Tokens via sidebar
- **LangSmith Tracing**: Integrated for monitoring and debugging LLM calls
- **Secure API Key Input**: Groq API key entered via sidebar (not hardcoded)
- **Clean Chat Interface**: Modern Streamlit chat UI with message history
- **Environment Variable Support**: Uses `.env` file for configuration

## Tech Stack

- **Streamlit** – Frontend & UI
- **LangChain** – Prompt templates, chains, and output parsing
- **Groq** – Fast LLM inference (Llama models)
- **Python** – Backend
- **LangSmith** – Observability and tracing

## Project Structure
<img width="734" height="172" alt="image" src="https://github.com/user-attachments/assets/82e16292-6303-4ca8-87b8-aec2470f9d8d" />

## How to Use

1. Enter your Groq API Key in the sidebar.
2. Select your preferred Groq model from the dropdown.
3. Adjust Temperature and Max Tokens as needed.
4. Start chatting in the main chat window.

Example Prompts:

 - Explain how transformers work in simple terms.
 - Write a Python function to reverse a string.
