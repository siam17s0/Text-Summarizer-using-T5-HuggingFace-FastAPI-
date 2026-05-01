# Text-Summarizer-using-T5-HuggingFace-FastAPI-
A machine learning project that performs **abstractive text summarization** using a fine-tuned **T5-small transformer model**.   The model is deployed using **FastAPI** with a simple web interface.

## Features
* Fine-tuned T5 transformer model
* Abstractive text summarization
* FastAPI backend for real-time inference
* Simple HTML/CSS/JS frontend
* Clean preprocessing pipeline
* Model saving & loading support

##  Model Details
* Model: `t5-small (HuggingFace Transformers)`
* Task: Text Summarization
* Dataset: SAMSum (or custom dialogue dataset)
* Framework: PyTorch + Transformers

## Project Pipeline
* Data Cleaning (regex, lowercasing, noise removal)
* Tokenization using T5Tokenizer
* Fine-tuning T5 model
* Model evaluation & saving
* FastAPI deployment
* Frontend integration (HTML + JS)

## Tech Stack
* Python
* PyTorch
* HuggingFace Transformers
* FastAPI
* HTML, CSS, JavaScript

## How to Run

### Install dependencies
pip install -r requirements.txt 

## Run FastAPI server
uvicorn app:app --reload

## Open browser
http://127.0.0.1:8000

## Example
""" 
Reporter: In today's technology news, artificial intelligence continues to expand rapidly across industries, from healthcare to finance and education. Recent reports suggest that AI adoption has significantly increased over the past few years.

Reporter: Companies are investing heavily in machine learning systems to automate tasks, improve decision-making, and enhance customer experiences. However, this growth has also raised questions about job displacement and ethical concerns.

Expert: AI systems are becoming more capable due to advances in deep learning and access to large datasets. These models can now perform complex tasks such as language understanding, image recognition, and even code generation.

Expert: At the same time, there are valid concerns about bias in AI models, as they often reflect the data they are trained on. Ensuring fairness and transparency is becoming a key area of research.

Reporter: Governments and organizations are beginning to introduce regulations to guide the development and deployment of AI technologies. The goal is to balance innovation with accountability.

Expert: Another challenge is explainability. Many modern AI systems, especially deep neural networks, operate as “black boxes,” making it difficult to understand how decisions are made.

Reporter: Experts also highlight the importance of responsible AI development, including data privacy, security, and long-term societal impact.

Expert: Looking ahead, collaboration between researchers, policymakers, and industry leaders will be crucial to ensure that AI systems are developed and used in a safe and beneficial way.
"""


