# Question Answering for Concrete technology with LLMs (POC)

This repository hosts a Proof of Concept (POC) project integrating Large Language Models (LLM) with a chatbot tailored for the domain of Concrete Technology. This innovative project aims to leverage cutting-edge natural language processing (NLP) techniques to provide intelligent conversational interfaces for professionals and enthusiasts in the field of concrete science and engineering.

## Installation

You can install the required dependencies using pip. First, clone this repository:

```bash
git clone <This Repository>
cd your_repository
```

Then, install the dependencies:

```bash
pip install -r requirements.txt
```

## Data Folder
Create a folder named `data` in the root directory of the project. This is where you should store your dataset files.

## Environment Variables
Before running the application, make sure to declare the following environment variables in a .env file:

```bash
OPENAI_API_KEY=your_openai_api_key
GOOGLE_API_KEY=your_google_api_key
```

Replace your_openai_api_key and your_google_api_key with your actual API keys.

## Usage
To run the application, execute the following command:

```bash
streamlit run main.py
```
This will start the application and open it in your default web browser.

