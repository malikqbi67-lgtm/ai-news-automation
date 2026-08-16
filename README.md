# 🤖 AI News Automation

An automated AI-powered news aggregation and summarization workflow built with **n8n**, **Google Gemini**, **RSS**, and **Telegram**.

The system automatically collects the latest articles from an RSS feed, extracts their content, processes them with Google Gemini, and sends a concise Arabic news summary to Telegram.

## 🚀 How It Works

```text
Schedule Trigger
       ↓
    RSS Read
       ↓
      Limit
       ↓
   Edit Fields
       ↓
  HTTP Request
       ↓
   HTML Extract
       ↓
  Edit Fields
       ↓
   Aggregate
       ↓
 Google Gemini
       ↓
 Telegram
