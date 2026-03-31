# Telegram AI Assistant with Gemini

## Summary

This workflow implements a Telegram bot that accepts user messages, checks whether the sender is allowed to use the bot, and then generates a response through a Google Gemini model.

## What it demonstrates

- Integration between Telegram and n8n
- AI agent setup with Google Gemini
- Session memory for short conversation context
- Access control through conditional logic
- Separate handling for authorized and unauthorized users

## Workflow logic

1. Telegram trigger receives an incoming message.
2. `If` node verifies the sender ID.
3. Allowed users are passed to the AI Agent.
4. The AI Agent uses Gemini plus memory to generate a reply.
5. The response is sent back to Telegram.
6. Unauthorized users receive a denial message.

## Why it is good for a portfolio

This is a solid showcase piece because it combines chatbot automation, LLM integration, stateful memory, and permission control inside one practical workflow.

## Setup notes

- Recreate Telegram credentials in n8n
- Recreate Google Gemini credentials
- Update the allowed Telegram user ID if needed
- Test in a private Telegram chat before public use
