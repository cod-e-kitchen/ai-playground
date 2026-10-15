## Basic Chatbot with Anthropic Claude API
A beginner-friendly Jupyter Notebook demonstrating how to build a conversational AI chatbot using the Anthropic Claude API in Python.

## This project covers:

- Loading API keys with dotenv
- Sending prompts to Claude
- Managing conversation history
- Creating a multi-turn chatbot
- Using system prompts
- Controlling response creativity with temperature
- Streaming responses in real time
- Working with assistant prefill and stop sequences

## Features
1. Single Prompt Completion
Send a simple prompt to Claude and receive a response.

2. Conversation Memory
Maintain chat history by storing user and assistant messages.

3. Interactive Chatbot
Create a real-time command-line chatbot.

4. System Prompts
Control Claude's behavior using system instructions.

5. Temperature Control
Temperature controls randomness and creativity.

6. Streaming Responses
Receive tokens as they are generated rather than waiting for the full response.

Useful for:
Chat applications
Real-time user interfaces
Faster user experience

7. Assistant Prefill
Guide Claude's output by pre-populating an assistant message.

## Project Structure
.
├── chatbot.ipynb
├── .env
├── README.md
└── requirements.txt
Installation
Clone the Repository
git clone https://github.com/cod-e-kitchen/ai-playground.git
cd ai-playground
Create a Virtual Environment
python -m venv .venv
Activate:

Windows
.venv\Scripts\activate
macOS/Linux
source .venv/bin/activate
Install Dependencies
pip install anthropic python-dotenv
or

pip install -r requirements.txt
Environment Variables
Create a .env file in the project root.

ANTHROPIC_API_KEY=your_api_key_here

## Requirements
anthropic
python-dotenv
jupyter


## Chat Function
Responsible for:

Sending requests to Claude
Applying system prompts
Handling temperature
Returning generated text
Learning Objectives

## This notebook is ideal for developers learning:

Large Language Model (LLM) APIs
Prompt Engineering
Multi-turn conversations
Context management
Streaming responses
Anthropic Claude SDK

## Note
This project is intended for learning and experimentation with the Anthropic Claude API. Do not commit your .env file or API keys to GitHub.

Created as part of the AI Playground project to explore Anthropic Claude API capabilities and conversational AI development.

