Conversational AI & Text Intelligence
 Overview

This project demonstrates how Large Language Models (LLMs) and Transformer pipelines can work together to build intelligent, multi-purpose conversational systems.
It combines OpenAI GPT-4o-mini for creative text generation with Hugging Face pipelines for understanding and classifying user inputs — forming the foundation of a modern AI assistant.

=>Key Features
1. OpenAI Powered Chatbots

Implemented multiple chatbot personalities using openai and OpenAI clients:

Coder Bot; answers programming and C++-related prompts.

Keyword Extractor; summarizes and extracts keywords from user text.

Poetic Chatbot; responds artistically with human-like creativity.

Demonstrated message roles: system, user, and optional assistant messages.

Tuned output with parameters like temperature, max_tokens, and structured prompts.

2.Hugging Face Transformers Integration

Sentiment Analysis

Used pre trained models via pipeline("sentiment-analysis") to determine emotional tone.

Zero-Shot Classification

Applied facebook/bart large-mnli to classify new text into user-defined categories (e.g., travel, dancing, cooking).

Demonstrated contextual understanding and classification without explicit retraining.

=>Tech Stack

Python • OpenAI API • transformers • Hugging Face • pandas
