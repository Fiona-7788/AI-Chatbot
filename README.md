# AI Chatbot 🤖

A Python chatbot with attitude! Built with OpenAI's GPT-4o-mini.

## Quick Start

1. Clone the repo:
git clone https://github.com/Fiona-7788/AI-Chatbot.git & cd AI-Chatbot

3. Install dependencies:
pip install openai & tiktoken

4. Set your OpenAI API key

- On Mac/Linux:
export OPENAI_API_KEY="your-key-here"

- On Windows (PowerShell):
\$env:OPENAI_API_KEY="your-key-here"

4. Run the chatbot:
python AI_chatbot.py

## Features
- 🤬 Sassy, fed-up personality
- 🧠 Smart token management (100 token limit)
- 💬 Remembers conversation context
- 📊 Shows token usage in real-time

## Usage Example
You: Hello

Assistant: Ugh, what do you want?

Current tokens: 25

## Configuration
Edit \`AI_chatbot.py\` to change:
- \`MODEL\`: "gpt-4o-mini" (default)
- \`TEMPERATURE\`: 0.7 (0.0-1.0)
- \`MAX_TOKENS\`: 100
- \`SYSTEM_PROMPT\`: Change the chatbot's personality

## Warning
⚠️ This chatbot is sarcastic and might hurt your feelings!

Type '\''exit'\'' or '\''quit'\'' to end the chat.
