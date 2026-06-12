# HR Interactive Interview Agent

## Overview

An AI-powered interactive interview preparation agent built using LangChain and Google Gemini.

The agent simulates an HR interviewer that helps candidates practice interviews by asking questions, reviewing answers, and providing constructive feedback.

The project also includes an interactive healthcare-style conversational agent workflow for practicing question-based conversations.

## Features

- AI HR interviewer simulation
- Interview question generation
- Candidate answer evaluation
- Constructive feedback
- Conversational memory using LangGraph
- Gemini LLM integration
- Interactive command-line conversation

## Tech Stack

- Python
- LangChain
- LangGraph
- Google Gemini
- Google Colab

## Project Structure

```
.
├── hrinteractiveagent.ipynb
└── README.md
```

## Installation

Install dependencies:

```bash
pip install -U langchain
pip install -U langchain-google-genai
pip install -U langgraph
```

## API Key Security

No API keys or secrets are included in this repository.

Use environment variables or secret managers.

Example:

```python
from google.colab import userdata

api_key = userdata.get("YOUR_GOOGLE_API_KEY")
```

Do not:
- Upload API keys to GitHub
- Commit `.env` files
- Hardcode credentials inside notebooks

## Workflow

```
User
 |
 ↓
Interactive Agent
 |
 ↓
Gemini Model
 |
 ↓
Questions + Feedback
```

## Example Use Cases

- Interview preparation
- Mock HR rounds
- Communication practice
- AI coaching assistants

## Future Improvements

- Add resume analysis
- Add job description matching
- Add voice interview support
- Add web interface
- Add evaluation scoring system

## License

Educational project.
