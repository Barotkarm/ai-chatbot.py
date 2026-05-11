# Karm-AI — Local AI Chatbot

A Python terminal chatbot that connects to a locally running LLM
(SmolLM2) via Ollama using the OpenAI-compatible API.

## Tech Stack
- Python 3.x
- OpenAI Python SDK
- Ollama (local LLM runner)
- SmolLM2 model

## Setup & Usage

### 1. Install Ollama
Download from https://ollama.com and run:
```
ollama pull smollm2
ollama serve
```

### 2. Install dependencies
```
pip install -r requirements.txt
```

### 3. Run the chatbot
```
python ai_chat.py
```

## Author
Karm Barot — [github.com/Barotkarm](https://github.com/Barotkarm)
