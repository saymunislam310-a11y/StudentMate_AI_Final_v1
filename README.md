# StudentMate AI - Updated

## What changed
- Real AI chat backend via OpenAI Responses API.
- Bangla Unicode + English conversation.
- Conversation context in the current chat.
- Image upload for AI image understanding.
- Image generation and image-edit endpoints.
- Student-friendly AI interface with New Chat, image tools, copy button and suggestions.
- Study timer keeps the default 25 minutes and adds 45, 50, 60, 90, 120 minute presets plus custom minutes.
- Task page now shows completion progress and a clear step-by-step completion guide.
- Refreshed student-friendly backgrounds and cards.

## Run locally

1. Install Python 3.11+.
2. Open a terminal in this folder.
3. Run:
   `pip install -r requirements.txt`
4. Copy `.env.example` to `.env`.
5. Put your real OpenAI API key in `.env`:
   `OPENAI_API_KEY=...`
6. Run:
   `python app.py`
7. Open `http://127.0.0.1:5000`

Never put the API key in HTML/JavaScript or publish it to GitHub.

The AI uses the OpenAI Responses API. Image generation/editing requires access to the configured image model and normal API billing/limits.
