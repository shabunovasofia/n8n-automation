# AI Science News Digest with Content Filter

## Summary

This workflow builds an automated content pipeline that collects articles from several RSS feeds, filters out unwanted topics, extracts page content, generates text with AI, pairs the generated text with an article image, and publishes the result to Telegram.

## What it demonstrates

- Multi-source RSS ingestion
- Content extraction from article pages
- JavaScript data transformation inside n8n
- Topic filtering and moderation logic
- Google Gemini integration for AI-generated output
- Telegram channel publishing

## Workflow logic

1. RSS triggers monitor multiple content sources.
2. A JavaScript node blocks unwanted topics and unsafe categories.
3. The workflow merges incoming feed data.
4. The article page is fetched with HTTP Request.
5. HTML content is extracted from the page.
6. Gemini generates the final text.
7. Another JavaScript node combines image and generated text into one payload.
8. Telegram publishes the final post with an image.

## Why it is good for a portfolio

This is one of the strongest files in the folder because it shows real orchestration work: aggregation, moderation, extraction, AI processing, transformation, and delivery in one end-to-end automation.

## Setup notes

- Recreate Telegram credentials
- Recreate Google Gemini credentials
- Replace the destination Telegram chat ID
- Check whether the RSS feeds are still active before reuse
