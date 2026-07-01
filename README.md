# Translator Chatbot (English → French)

An interactive command-line chatbot that translates English sentences into French using a pre-trained MarianMT model from Hugging Face Transformers.

## Description
This chatbot lets you type any English text and instantly see its French translation, with a charming **typewriter effect** that prints characters one by one – simulating real‑time typing. It’s built using the Hugging Face `transformers` library and runs in Google Colab or locally.

The project demonstrates how easy it is to access state‑of‑the‑art NLP models with only a few lines of code.

## Features
- **English‑to‑French translation** – powered by the `google-t5/t5-base` model (or MarianMT, fallback).
- **Live typing animation** – each character appears with a slight delay for a realistic feel.
- **Clean command‑line interface** – simple prompt, type `quit` to exit.
- **Runs in Colab or any Python environment** – minimal dependencies.

## Setup & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/baw4menna/translator-chatbot.git
   cd translator-chatbot
