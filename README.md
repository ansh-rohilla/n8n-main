# n8n-main

Personal Assistant chatbot interface built with Streamlit and integrated with n8n automated workflows.

## Features

- **Interactive Streamlit UI**: Chat interface for communicating with your AI personal assistant.
- **n8n Automation Integration**: Connects via webhooks to automate:
  - Answering general queries
  - Managing Google Calendar events and meetings
  - Reading, summarizing, and drafting Gmail emails
  - Managing tasks and to-do lists (Google Tasks)
  - Creating and appending notes (Google Docs)
  - Tracking expenses and budgets (Google Sheets)

## Getting Started

### Prerequisites

- Python 3.12+
- [uv](https://docs.astral.sh/uv/) (recommended) or pip
- Running [n8n](https://n8n.io/) instance with the personal assistant workflow active

### Installation

```bash
# Clone the repository
git clone https://github.com/ansh-rohilla/n8n-main.git
cd n8n-main

# Install dependencies using uv
uv sync
```

### Running the Application

```bash
# Run the Streamlit chat application
uv run streamlit run app.py
```
