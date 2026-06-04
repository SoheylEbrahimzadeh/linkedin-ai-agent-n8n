# 🤖 LinkedIn AI Content Agent — n8n

Auto-generate and publish professional LinkedIn posts using an AI agent.

## How It Works

1. Send a LinkedIn post URL to your Telegram bot
2. AI rewrites it in your personal tone and style
3. A matching image is generated automatically
4. You get a preview in Telegram — approve or reject
5. Approved posts go live on LinkedIn instantly

## Why Use This?

- ⏱ Saves time — each post ready in seconds
- 📈 Consistent posting = more reach and visibility
- 🎯 Personalized tone matching your personal brand
- 🖼 Auto-generated images relevant to the topic
- 💬 Focus on what matters: replies, DMs, networking

## Tech Stack

| Tool | Purpose |
|------|---------|
| n8n | Automation engine |
| Google Gemini 2.5 Pro | AI writing |
| Gemini Imagen | Image generation |
| Telegram Bot | Control & approval |
| ConnectSafely.ai | LinkedIn post scraping |
| LinkedIn OAuth | Post publishing |

## Setup

1. Import `linkedin_post_workflow.json` into n8n
2. Connect your credentials (Telegram, Gemini, LinkedIn)
3. In the `Security Check` node → set your Telegram User ID
4. In the `Load Your Persona` node → customize your writing style
5. Activate the workflow

## Configuration

Replace these placeholders in the workflow before use:
- `YOUR_TELEGRAM_USER_ID`
- `YOUR_LINKEDIN_PERSON_ID`
- Persona details in the `Load Your Persona` node
