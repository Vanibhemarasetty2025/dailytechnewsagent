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
<img width="806" height="847" alt="Screenshot 2025-11-23 at 3 07 09 PM" src="https://github.com/user-attachments/assets/6ce99b1a-56d7-42d0-82b5-6657f0a81975" />
<img width="1230" height="340" alt="Screenshot 2025-11-23 at 3 06 43 PM" src="https://github.com/user-attachments/assets/e2b0133c-a9e8-46d4-8c0a-654d9c7ab77d" />
<img width="1117" height="812" alt="Screenshot 2025-11-23 at 3 09 03 PM" src="https://github.com/user-attachments/assets/18bc5876-44ae-467b-ba00-4a493e17564f" />



## ⚙️ Setup

## ⚙️ Setup
1. Clone this repo.
2. Import `n8n_workflow.json` into your n8n instance.
3. Configure credentials:
   - Gmail OAuth2 (send access)
   - OpenAI API key
4. Update `startDate` in the “Select Concept” node.
5. Activate workflow.
