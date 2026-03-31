# K-Drama News Digest to Telegram

## Summary

This workflow automates a niche media digest for K-drama and Asian entertainment news. It collects updates from multiple RSS feeds, fetches article pages, extracts useful content, uses AI to prepare post text, and sends the result to Telegram with an image.

## What it demonstrates

- Multi-feed content aggregation
- Entertainment/news automation for a themed audience
- HTTP and HTML parsing inside n8n
- AI-assisted text preparation
- Merging structured and scraped data
- Telegram publishing with media

## Workflow logic

1. Several RSS triggers listen to drama-related sources.
2. Feed items are merged into a single flow.
3. Article pages are downloaded through HTTP Request.
4. Relevant HTML content is extracted.
5. AI prepares publishable text.
6. JavaScript combines image and text fields.
7. Telegram sends the final post as a photo message.

## Why it is good for a portfolio

This workflow is useful in a portfolio because it shows that you can build themed editorial automation, not just generic bot flows. It has a clear audience, multiple integrations, and a finished delivery channel.

## Setup notes

- Recreate Telegram credentials
- Recreate Google Gemini credentials
- Replace the Telegram chat ID
- Review feed quality and posting frequency before production use
