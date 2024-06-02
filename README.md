# Chat with Documents Project

![Python](https://img.shields.io/badge/python-3.9+-blue.svg)
![LlamaIndex](https://img.shields.io/badge/LLama_Index-Integrated-orange)
![License](https://img.shields.io/badge/license-MIT-green)

## Introduction 📖

This project demonstrates an innovative approach to interacting with various document formats using AI models. It leverages the power of the LlamaIndex, Gemini, and OpenAI models to embed and respond to user queries, providing a seamless chat experience with documents.

## Table of Contents 📑

- [Introduction](#introduction-)
- [Installation](#installation-)
- [Usage](#usage-)
- [Features](#features-)
- [Dependencies](#dependencies-)
- [Configuration](#configuration-)
- [Documentation](#documentation-)
- [Examples](#examples-)
- [Troubleshooting](#troubleshooting-)
- [Contributors](#contributors-)
- [License](#license-)

## Installation 💾

To set up the project environment, ensure you have Python installed on your system. Then, clone this repository and install the required dependencies:

```bash
git clone <repository-url>
cd <repository-name>
pip install -r requirements.txt
```

## Usage 🚀
First of all make sure to add your **LLMs API keys.**

To start the Streamlit application, navigate to the project directory and run:

```bash
streamlit run chat_with_documents_final_1.py
```

In the application, choose between different models for embedding and responses through the UI.

## Features ✨

- Chat with documents in formats like .csv, .docx, .ipynb, .md, .pdf, .ppt, and .txt.
- Select between different AI models for embedding and responses:
  - **Gemini**: For embedding and responses.
  - **OpenAI**: For embedding and responses.
  - **Custom**: A mix of Gemini for embedding and OpenAI for responses.
- Streamlit-based UI for easy interaction.

## Dependencies 📦

- Python 3.9+
- streamlit
- llama_index
- Other dependencies listed in `requirements.txt`.

## Configuration 🔧

Configuration options are primarily within the Streamlit UI, allowing users to select the model for embedding and responses.

## Documentation 📚

The project includes the following Jupyter notebooks for detailed insights and customizations:
- `chat_with_documents_gemini.ipynb`: Uses Gemini for both embedding and responses.
- `chat_with_documents_gemini_openai.ipynb`: Gemini for embedding and OpenAI for responses.
- `chat_with_documents_openai.ipynb`: OpenAI for both embedding and responses.

## Examples 📝

Refer to the Jupyter notebooks for examples on how the models are utilized for chatting with documents.

## Troubleshooting 🛠️

If you encounter any issues, first ensure all dependencies are correctly installed and that you're running the Streamlit application from the project's root directory.

## Contributors 🤝

To contribute to this project, please fork the repository, make your changes, and submit a pull request. For major changes or enhancements, please open an issue first to discuss what you would like to change.

## License 📄

This project is licensed under the MIT License - see the LICENSE file for details.
