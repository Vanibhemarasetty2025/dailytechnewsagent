# Tech News Weekly Agent (n8n)

This n8n workflow generates a weekly tech newsletter and emails it.

## Features

- Fetches latest tech articles from [chosen RSS source].
- Uses an LLM to summarise the week into sections (AI, Big Tech, Security, etc.).
- Renders a Medium-style HTML email and sends it to configured recipients.

## Files

- `workflow.json` – exported n8n workflow.
- `env.example` – example of environment variables required.

## Setup

1. Import `workflow.json` into your n8n instance:
   - n8n UI → Workflows → Import from file.
2. Configure credentials:
   - Email (SMTP/Gmail/etc.).
   - LLM / OpenAI API key.
3. Adjust schedule node for when you want the newsletter to run.
4. (Optional) Edit prompt in the AI node if you want different tone/sections.
