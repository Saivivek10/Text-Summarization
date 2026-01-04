# LangChain: Summarize Text From YouTube or Website

This project is a **Streamlit web application** that leverages the **LangChain framework** to summarize content from YouTube videos or websites. It uses the **Groq API** and a language model (`llama-3.1-8b-instant`) to generate concise summaries of the provided content.

## Features

- **Summarize YouTube Videos**: Extracts and summarizes the content of YouTube videos.
- **Summarize Website Content**: Fetches and summarizes text from any valid website URL.
- **Customizable Prompt**: Uses a flexible prompt template to generate summaries.
- **Interactive UI**: Built with Streamlit for an easy-to-use interface.
- **Secure API Integration**: Requires a Groq API key for accessing the language model.

## Project Structure

- `app.py`: The main Streamlit application that handles user input, validates URLs, and generates summaries.
- `text_summarization.ipynb`: A Jupyter Notebook demonstrating various summarization techniques using LangChain.
- `requirements.txt`: Lists all the dependencies required to run the project.
- `apjspeech.pdf`: A sample PDF file used for testing document summarization.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
