# Invoice_Extractor
GEN AI Project

This project leverages Google Generative AI to create a Q&A application that can extract and understand information from invoices. Users can upload an image of an invoice and ask questions about its content, and the application will return responses based on the image.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)


## Features
- Upload an image of an invoice
- Generate responses based on the invoice content using Google Generative AI
- Simple Q&A interface

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Invoice_Extractor.git
    cd Invoice_Extractor
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv env
    env\Scripts\activate  # On Windows
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up your Google API key:
    - Create a `.env` file in the project directory.
    - Add your Google API key to the `.env` file:
      ```
      GOOGLE_API_KEY=your_google_api_key
      ```

## Usage

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. In the Streamlit interface:
    - Enter your input prompt in the input box.
    - Upload an image of an invoice using the file uploader.
    - Click the "Tell me about the image" button to get a response from the Gemini model.

## Requirements

- Python 3.x
- streamlit
- google-generativeai
- python-dotenv
- langchain
- PyPDF2
- chromadb
- faiss-cpu



