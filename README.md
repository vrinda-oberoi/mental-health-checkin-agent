# 🧠 Mental Health Check-In Agent (No-Code AI Bot)

This is a no-code AI-powered mental health check-in agent built using **n8n**, **Telegram**, and **Azure OpenAI** (GPT). It automatically checks in with users, analyzes their emotional responses, and sends back kind, supportive replies.

---

## 💡 Features

- 🔔 Sends automated check-in messages every 2 minutes via Telegram
- 💬 Uses Azure OpenAI to analyze user emotions
- 💛 Sends supportive replies like a digital wellness buddy
- 🤖 100% No-Code — built entirely in [n8n.io](https://n8n.io)
- 🛠️ Can be extended with Sheets, dashboards, or reminders

---

## ⚙️ Tech Stack

- [n8n](https://n8n.io) – No-code workflow automation
- Telegram Bot API – For user interaction
- Azure OpenAI (GPT) – For mood detection and response
- Cron (Custom) – For scheduling check-ins every 2 minutes

---

## 📂 File Included

- `mental-health-checkin-workflow.json`  
  → This is the complete export of the n8n workflow.

---

## 📦 How to Use

1. Clone or download this repository.
2. Import the `.json` file into your n8n instance:
   - Open n8n
   - Go to **"Import from File"**
   - Select the `.json` file
3. Update the following:
   - Telegram credentials (Bot Token, Chat ID)
   - Azure OpenAI credentials (API Key, endpoint)
4. Set the workflow to **Active**.
5. You’re ready! The bot will start checking in via Telegram on schedule.

---

## 🚀 Future Improvements

- Mood logging in Google Sheets
- Only trigger during 8 AM to 10 PM
- Personalized self-care suggestions (music, journaling, breathing)
- Deployment on WhatsApp or Web chat

---

## 🎥 Demo Video

Watch the demo here:  
🔗 [Click to view on Google Drive](https://drive.google.com/file/d/1kJo3GCn_gxXuqMX12EJjmvjv7mhIQkpK/view?usp=sharing)


## 👩‍💻 Created By

**Vrinda Oberoi**  
Built during the **AI Agents Hackathon**  
🌐 [n8n.io](https://n8n.io) | 💬 Telegram | 🧠 Azure OpenAI


