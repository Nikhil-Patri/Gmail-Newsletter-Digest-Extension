# Gmail-Newsletter-Digest-Extension
A Chrome extension that automatically processes your Gmail inbox to identify, summarize, and create a digest of newsletters. Built with Python backend and Chrome extension frontend.

Features:
Automatically identifies newsletters in your Gmail inbox

Generates concise summaries of newsletter content

Creates a well-formatted markdown digest

Secure Gmail API integration

Powered by Google's Gemini AI for intelligent processing

Configurable number of emails to process

Real-time processing and updates


Project Structure
gmail-extension/
├── backend/                 # Python backend
│   ├── agent/              # AI agent for email processing
│   │   ├── agent.py        # Main agent logic
│   │   ├── llm.py          # LLM integration
│   │   └── tools.py        # Email processing tools
│   ├── app.py              # Flask server
│   └── logging_config.py   # Logging configuration
├── extension/              # Chrome extension
│   ├── manifest.json       # Extension manifest
│   ├── popup.html         # Extension popup UI
│   ├── popup.js           # Popup logic
│   └── styles.css         # Extension styles
└── logs/                  # Application logs
