# 🧠 Mental Health Check-In Agent (No-Code AI Bot)

This is a no-code AI-powered mental health check-in agent built using **n8n**, **Telegram**, and **Azure OpenAI** (GPT). It automatically checks in with users, analyzes their emotional responses, and sends back kind, supportive replies.

---
##🌟 Features
🔁 Automated Emotional Check-Ins — Periodically checks in with users every hour to ask how they’re feeling
📬 Inactivity Detection — Tracks when a user was last seen and follows up if they go silent for too long
🧠 Memory-Driven Support — Stores user replies and timestamps in Google Sheets to build emotional context
💬 Empathetic GPT Responses — Uses Azure OpenAI to send thoughtful, caring replies based on the user’s emotions
📈 No-Code Architecture — Built entirely with n8n.io, no backend code required
📊 Live Memory Log — All conversations are logged and can be viewed or analyzed via connected Sheets
📥 Email & Telegram Support — Can work via multiple channels like Email, Telegram, and expandable to web UI
🚀 UI-Ready — Easily integratable with front-end using n8n Webhooks for a future custom web interface



---

## ⚙️ Tech Stack

🔧 **n8n** – No-code workflow automation  
📊 **Google Sheets** – Memory for storing replies and timestamps  
🧠 **Azure OpenAI (GPT)** – Emotional and empathetic AI replies  
💬 **Telegram Bot API** – Messaging platform (v1)  
⏱ **Cron (via n8n)** – Hourly check-in scheduler  

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


