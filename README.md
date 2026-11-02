# Serverless Anti Spam Bot

A production ready Telegram bot built with Python 3.11 and aiogram 3.x designed to protect groups from spam and bot floods.

## Features
- Cloudflare Workers free serverless deployment support
- AI generated quiz challenges for new members
- Automatic member verification upon join

## Local Setup
1. Clone the repository
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. Copy .env.example to .env and fill in your BOT_TOKEN.
4. Run the bot:
   ```bash
   python main.py
   ```

## Deployment
Deploy easily on Render or Koyeb using Python runtime.