# AI Appointment Agent (SaaS-Oriented MVP)

This project is a conversational AI scheduling agent designed as a SaaS-ready MVP.

It automates appointment booking through natural language conversations, verifies real-time availability, suggests alternative time slots, and maintains conversation state.

Built with a scalable architecture mindset.

---

## 🚀 Features

- Natural language intent detection (OpenAI)
- Procedure, date and time extraction
- Real-time availability check (Supabase)
- Automatic suggestion of next available slots
- Stateful conversation management
- Intelligent interpretation of user replies
- Appointment confirmation flow
- Conversation lifecycle management
- SaaS-ready architecture principles

---

## 🏗 Architecture

Telegram → ngrok → n8n → OpenAI → Supabase

- **n8n**: Orchestration & workflow automation
- **Supabase**: Database & persistence layer
- **OpenAI API**: Natural language processing
- **Telegram Bot API**: User interface layer
- **ngrok**: Local webhook tunneling

---

## 🧠 System Design Highlights

- Stateful conversation stored in database
- Availability conflict prevention
- Dynamic suggestion engine
- Modular workflow structure
- Prepared for multi-tenant SaaS expansion

---

## 🗄 Database Structure

- `agendamentos`
- `conversas`
- (Expandable to multi-tenant structure)

---

## 📌 Future Improvements

- Multi-tenant architecture
- Admin dashboard
- Subscription management
- Plan-based feature gating
- Web interface
- Multi-channel support (WhatsApp, Webchat)

---

## 💡 Purpose

This project was built as a foundation for a scalable SaaS platform focused on intelligent conversational booking systems for service-based businesses.

---

## ⚙️ Setup

1. Configure environment variables
2. Import n8n workflow
3. Setup Supabase database
4. Configure Telegram bot token
5. Start n8n with webhook URL
6. Expose via ngrok (if running locally)

---

## 👨‍💻 Author

Pedro Mattos
