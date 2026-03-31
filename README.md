# n8n Workflow Portfolio

This repository contains selected n8n workflows that are suitable for a public portfolio.

## Recommended workflows

### `telegram-ai-assistant-gemini.json`
Telegram bot with access control and AI responses via Google Gemini. Demonstrates chat automation, LLM integration, memory, and conditional branching.

Description: [telegram-ai-assistant-gemini.md](/Users/sshabunova/Documents/n8n/telegram-ai-assistant-gemini.md)

### `ai-science-news-digest-with-filter.json`
Automated science and entertainment news digest: collects articles from multiple RSS feeds, filters unsafe topics in JavaScript, extracts article content, generates AI text, and publishes to Telegram.

Description: [ai-science-news-digest-with-filter.md](/Users/sshabunova/Documents/n8n/ai-science-news-digest-with-filter.md)

### `kdrama-news-digest-to-telegram.json`
Automated entertainment digest for K-drama and Asian drama news. Combines multiple RSS sources, extracts article pages, prepares text and images, and posts results to Telegram.

Description: [kdrama-news-digest-to-telegram.md](/Users/sshabunova/Documents/n8n/kdrama-news-digest-to-telegram.md)

### `imap-email-alerts-to-telegram.json`
Compact utility workflow that monitors email via IMAP, formats the message details, and forwards new email notifications to Telegram.

Description: [imap-email-alerts-to-telegram.md](/Users/sshabunova/Documents/n8n/imap-email-alerts-to-telegram.md)

## Files not recommended for GitHub showcase

### `xo2ju16lWlUr8pHY-dramacuting.json`
Empty workflow without nodes.

### `XaYkwj3l9FkCd7uQ-My_workflow_2.json`
Working draft of the news digest, but weaker than the selected version because it has fewer sources and less complete filtering logic.

### `YwK3S2LGO8isSqpo-My_workflow_3.json`
Looks like an intermediate draft of the entertainment digest. It is simpler than the selected version and contains a duplicated Reddit source.

## Notes for publication

- The workflow content was not changed.
- File names were updated only to make the repository easier to understand.
- Credentials are not stored directly in these exports, but the workflows still reference Telegram, IMAP, and Gemini credentials that will need to be recreated in another n8n instance.
- Some workflow nodes contain hardcoded chat IDs and access rules. That is acceptable for a portfolio export, but you may want to replace them before making the repository public.
