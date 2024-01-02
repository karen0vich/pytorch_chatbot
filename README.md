# PyTorch Contextual Chatbot

Implementation of a Contextual Chatbot in PyTorch.

This project provides a simple yet insightful implementation of a chatbot using PyTorch. The goal is to offer a beginner-friendly codebase, allowing users to grasp the fundamentals of chatbot development.

## Features

- **PyTorch Implementation:** The chatbot is built using PyTorch, making it accessible for those interested in machine learning with this framework.
- **Customizable:** Tailor the chatbot to your specific use case by modifying the intents.json file with relevant patterns and responses. Simply re-run the training process for an updated model.

## Installation

1. **Create an Environment:**
   - Choose your preferred environment manager (e.g., conda or venv).
   - Create and activate a virtual environment.

    ```bash
    mkdir myproject
    cd myproject
    python3 -m venv venv
    ```

    - Activate the virtual environment.

    **Mac / Linux:**

    ```bash
    . venv/bin/activate
    ```

    **Windows:**

    ```bash
    venv\Scripts\activate
    ```

2. **Install NLTK:**
   - Install the NLTK library.

    ```bash
    pip install nltk
    ```

   - If you encounter an error during the first run, install the 'punkt' tokenizer.

    ```bash
    python -m nltk.downloader punkt
    ```

## Usage

1. **Train the Model:**
   - Run the training script to generate the data.pth file.

    ```bash
    python train.py
    ```

2. **Run the Chatbot:**
   - Execute the chatbot script to engage in a conversation.

    ```bash
    python chat.py
    ```

Feel free to explore and customize the intents.json file to enhance the chatbot's responses according to your requirements.

