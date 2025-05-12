# 🤖 AI Sales Caller

AI Sales Caller is a voice-driven sales assistant built using **Flask**, **Twilio Voice**, and **Google Calendar API**. It automatically places a phone call, interacts with the user using speech recognition, provides course details, and schedules a Google Meet demo call—all without human intervention.

---

## 🔧 Features

- 📞 Automated voice calls via Twilio
- 🧠 Speech recognition & intent detection
- 📚 Course inquiry responses
- 📅 Demo scheduling via Google Calendar
- 🔗 Google Meet link creation
- 📲 SMS follow-up with meeting link
- ✅ Voice call test endpoint

---

## 🚀 Tech Stack

- **Python** (Flask)
- **Twilio Voice API**
- **Google Calendar API**
- **Dateparser** (natural language datetime parsing)
- **dotenv** for managing secrets

---

## 🧪 How It Works

1. **Initiate Call**: `/call` endpoint makes an outbound call using Twilio.
2. **Conversation Flow**:
   - AI asks
