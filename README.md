# AI Email Automation using n8n

An AI-powered email automation project built using n8n, OpenRouter, Gmail, and Simple Memory.

## Project Overview

This project uses an AI agent to understand chat instructions and perform email-related tasks through Gmail. Simple Memory supports conversational context between interactions.

## Features

- Chat-based interaction with an AI assistant
- AI-powered responses using OpenRouter
- Gmail integration for sending emails
- Conversational memory using Simple Memory
- Configurable AI system instructions for professional email assistance

## Technologies Used

- n8n — workflow automation
- OpenRouter — AI model integration
- Gmail — email delivery
- Simple Memory — conversational context

## Workflow Architecture

1. **Chat Trigger:** Receives a message from the user.
2. **AI Agent:** Processes the request using the configured system instructions.
3. **OpenRouter Chat Model:** Generates AI responses.
4. **Simple Memory:** Provides conversational context.
5. **Gmail Tool:** Sends an email when requested by the AI agent.

## Project Files

- `email-automation-public.json` — exported n8n workflow.

## Setup Instructions

1. Install or open an n8n instance.
2. Import the workflow JSON file.
3. Configure your own OpenRouter credentials.
4. Configure Gmail OAuth credentials.
5. Review the workflow settings and test with a non-sensitive recipient.
6. Activate or publish the workflow as required by your n8n setup.

**Note:** Credentials are not included in the public workflow export. You must configure your own credentials before running it.

## Testing

Test the workflow with sample chat instructions and verify the results in Gmail. Use a test recipient and confirm the email content before relying on the automation.

## Future Improvements

- Email classification and priority detection
- Email summarization and reply drafting
- Google Sheets integration for tracking email information
- Human approval before sending emails
- Error handling and execution logging

## Author

Sumit Jadhav
