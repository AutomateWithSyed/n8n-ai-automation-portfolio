# n8n AI Automation Portfolio

A collection of AI agents and automation workflows built using n8n, Google Gemini, and Google Sheets. Each workflow follows the same core pattern: a trigger that starts the process, an AI or logic layer that processes information, and an action that automatically delivers the result.

## Projects

### 1. E-commerce Customer Support Agent (Alex)

An AI-powered chatbot that handles customer support for an e-commerce store, available 24/7.

**What it does:**
- Answers customer questions about orders, products, returns, and shipping
- Remembers conversation context within a session using Simple Memory
- Stays on topic and politely declines unrelated requests
- Hands off naturally when a query falls outside its scope

**Tech stack:** n8n, Google Gemini, Simple Memory

**Flow:** Chat trigger → AI Agent (Gemini) → Response with memory

---

### 2. Lead Collection Agent

An automated lead capture system that turns website form submissions into organized, actionable data with zero manual work.

**What it does:**
- Captures visitor details through a web form (name, email, phone, inquiry)
- Automatically saves every submission to a Google Sheet in real time
- Runs continuously with no human intervention required

**Tech stack:** n8n, Google Sheets API (OAuth2)

**Flow:** Form trigger → Append Row to Google Sheets

---

## About

Built by Syed Abdullah, an AI Chatbot and Workflow Automation Specialist based in Lahore, Pakistan.

I help businesses automate customer support, lead capture, and repetitive workflows using n8n and AI.

**Upwork:** [Add your Upwork profile link here]

## Usage

Each `.json` file in this repository is an exportable n8n workflow. To use one:

1. Open your n8n instance
2. Click **Import from File** (or paste the JSON via the workflow menu)
3. Configure your own credentials (Google Gemini API key, Google Sheets OAuth, etc.)
4. Activate the workflow
