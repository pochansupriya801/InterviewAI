# InterviewAI

AI-powered mock interview platform (Flask + SQLite + OpenAI).

## Setup

1. Create virtual environment (optional):
   ```powershell
   python -m venv venv
   .\venv\Scripts\activate
   ```

2. Install dependencies:
   ```powershell
   python -m pip install -r requirements.txt
   ```

3. Configure environment:
   ```powershell
   Copy-Item .env.example .env
   ```
   Edit `.env` and set `OPENAI_API_KEY`.

4. Run server:
   ```powershell
   python app.py
   ```
   Open http://127.0.0.1:5000

## Notes
- Never commit `.env`.
- SQLite database file is `interviewai.db`.
- Voice input requires Chrome/Edge Web Speech API support.