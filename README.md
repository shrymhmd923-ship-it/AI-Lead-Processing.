# AI Lead Processing

## Overview
AI Lead Processing is an AI-powered workflow built with n8n and Ollama. It analyzes potential customer inquiries, classifies lead priority, and routes leads automatically.

## Features
- Collects customer information.
- Uses an AI model to analyze customer messages.
- Classifies lead priority as High, Medium, or Low.
- Sends Telegram notifications for high-priority leads.
- Routes other leads for further review.

## Workflow
1. Receive lead information.
2. Analyze the message using an AI model.
3. Parse the AI response into structured fields.
4. Check the lead priority.
5. Send a Telegram alert for high-priority leads or mark other leads for review.

## Tools Used
- n8n
- Ollama
- Qwen 2.5
- Telegram Bot API
- JavaScript

## Example Use Case
A business receives an inquiry about AI automation services. The workflow analyzes the inquiry, assigns a priority, and notifies the sales team when the lead is classified as high priority.

## Setup
1. Import the exported workflow JSON into n8n.
2. Configure Ollama and the required AI model.
3. Configure Telegram credentials and Chat ID.
4. Execute the workflow and test it with sample lead data.

## Security
Never publish Telegram bot tokens, API keys, passwords, or other credentials.

## Project Status
Completed as a practical AI automation portfolio project.
