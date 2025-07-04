# Product Recommendation Agent

Telegram-based product recommender. Built with:

- Telegram Bot API  
- Gemini Pro API (Google AI)  
- Notion API (for product database)

No bells. No whistles. 

---

## 💡 What It Does

You send a product inquiry via Telegram.  
It replies with a curated recommendation from a Notion database, powered by Gemini.

---

## ⚙️ Stack

- **Telegram Bot API** – Handles input/output.
- **Gemini Pro (LLM)** – Parses, reasons, answers.
- **Notion API** – Stores and retrieves product info.
- **n8n** – Orchestrates everything.

---

## ▶️ Usage

1. Clone this repo.
2. Set up your `.env` file with:
    ```
    TELEGRAM_TOKEN=
    GEMINI_API_KEY=
    NOTION_TOKEN=
    NOTION_DB_ID=
    ```
3. Deploy your bot with [n8n](https://n8n.io) (self-hosted or cloud).

---

## 🧠 Flow Overview

