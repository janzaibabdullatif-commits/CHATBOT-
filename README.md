# Groq AI Chatbot

A simple terminal-based AI chatbot built with Python, powered by the Groq API and OpenAI's GPT-OSS model. Supports real-time streaming responses and conversation memory.

## Features

- Real-time streaming responses
- Conversation memory (remembers previous messages in the session)
- Fast inference powered by Groq
- Simple terminal interface

## Requirements

- Python 3.9+
- A Groq API key ([get one here](https://console.groq.com/keys))

## Setup

1. Clone the repository:
   ```bash
   git clone https:[//github.com/your-username/your-repo-name.git](https://github.com/janzaibabdullatif-commits/CHATBOT-)
   cd [your-repo-name
   ```](https://github.com/janzaibabdullatif-commits/CHATBOT-)

2. Create a virtual environment and activate it:
   ```bash
   python -m venv .venv
   .venv\Scripts\Activate.ps1   # Windows PowerShell
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file in the project root and add your Groq API key:
   ```
   GROQ_API_KEY=your_api_key_here
   ```

5. Run the chatbot:
   ```bash
   python chatbot.py
   ```

## Usage

Type your message and press Enter to chat. Type `quit`, `exit`, or `bye` to stop.

## Tech Stack

- Python
- [Groq API](https://groq.com/)
- OpenAI GPT-OSS model (via Groq)

## License

This project is open source and available for personal or educational use.
