# 🤖 Telegram → AI → Gmail Automation

## 📌 Project Overview

This project is an automation workflow created using **n8n** that connects Telegram, OpenAI and Gmail.

The workflow receives a message from Telegram, processes the request using an AI language model, converts the AI response into structured JSON using JavaScript, and finally sends the generated email through Gmail.

This project was created for **learning, automation practice and understanding API integration using n8n**.

---

## 🔄 Workflow

```text
Telegram
   │
   ▼
Telegram Trigger
   │
   ▼
Basic LLM Chain
   │
   ▼
OpenAI Chat Model
   │
   ▼
JavaScript
   │
   ▼
Gmail
   │
   ▼
Email Sent
