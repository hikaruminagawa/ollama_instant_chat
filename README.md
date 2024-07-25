# Instant Chat with Ollama

This repository contains a Streamlit application for instant chat using the Ollama language model.

## Prerequisites

Before running the application, ensure you have the following installed:

- Python 3.7 or higher
- [Ollama](https://ollama.com) library
- [Streamlit](https://streamlit.io) library

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/ollama-chat.git
    cd ollama-chat
    ```

2. Install the required Python packages:
    ```sh
    pip install ollama streamlit
    ```

## Usage

1. To run the application, use the following command:
    ```sh
    streamlit run ollama-chat.py
    ```

2. To change the language model (LLM), modify the `selected_llm` variable in the `ollama-chat.py` file:
    ```python
    selected_llm = 'llama3'  # Change this to your desired LLM
    ```

## Example

Run the application with the default settings:
```sh
streamlit run ollama-chat.py
