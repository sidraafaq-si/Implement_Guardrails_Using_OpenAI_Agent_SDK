# Implement_Guardrails_Using_OpenAI_Agent_SDK

This project builds an AI-powered chat agent using Chainlit and OpenAI-compatible models (e.g., Gemini) that answers only Python-related questions. It uses a custom input guardrail system to detect and reject non-Python inputs.

🚀 Features
✅ Filters out non-Python questions using guardrails
🧠 Answers Python questions using the Gemini model via OpenAI-compatible API
🛡️ Input validation using a secondary agent (Input Guardrails Checker)
💬 Real-time interaction via Chainlit
🛠️ Technologies Used
Python 3.10+
Chainlit – interactive LLM chat UI
OpenAI-compatible API client
Gemini via OpenAI API endpoint
Pydantic – for model validation
dotenv – for managing secrets
📦 Installation
Clone the repo:

git clone https://github.com/your-username/python-guardrails-agent.git
cd python-guardrails-agent
