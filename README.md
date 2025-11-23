# Tech News Weekly — Automated Newsletter Agent

This project automates **weekly tech news learning** using **n8n** and **OpenAI**.  
It sends a curated “This Week in Tech” newsletter to your Gmail — summarising the biggest stories in AI, Big Tech, security, startups, and more.

Built by a working mom who still wants to keep up with the chaos of tech.  

---

## 🧠 How It Works

- Uses an **n8n Scheduled Trigger** (weekly – you can change the time/day)
- Pulls the latest articles from a tech RSS feed (e.g. Wired / TechCrunch)
- Sends the article list to OpenAI to:
  - pick the most important stories
  - group them by theme
  - write a **Medium-style HTML newsletter**
- Emails the final digest to your inbox automatically

---
## Demo Pictures


## ⚙️ Setup

1. **Clone this repo**

   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>/tech-news-agent
