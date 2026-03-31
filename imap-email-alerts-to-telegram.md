# IMAP Email Alerts to Telegram

## Summary

This workflow monitors an email inbox through IMAP and forwards new message details to Telegram in a formatted notification.

## What it demonstrates

- IMAP integration in n8n
- Real-time or polling-based email monitoring
- Data cleanup and formatting through Set/Edit Fields
- Telegram notification delivery

## Workflow logic

1. IMAP email trigger watches the mailbox.
2. Email metadata is prepared for output.
3. A Telegram message is generated with sender, subject, recipient, date, and text.
4. The notification is delivered to Telegram.

## Why it is good for a portfolio

This is a smaller workflow, but it is still worth showing as a compact practical automation. It proves experience with server-side triggers, message formatting, and alerting workflows.

## Setup notes

- Recreate IMAP credentials
- Recreate Telegram credentials
- Replace the target Telegram chat ID
- Check mailbox permissions and trigger mode
