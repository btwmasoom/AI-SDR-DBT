# 🤖 AI Voice Agent Platform  

A next-generation **AI Voice Automation System** that lets you:  
- 📞 Buy phone numbers instantly  
- 🔊 Make outbound calls with **multiple AI voices**  
- 🎙️ Let AI **answer incoming calls** just like a human  
- 📅 Handle **scheduling & bookings**  
- 📝 Auto-generate **leads & CRM entries**  
- 📊 Track usage, costs & insights with an **animated dashboard**  

Built with **Next.js + React + Tailwind + Recharts** on the frontend and **Python FastAPI** on the backend.  
The platform is designed for **sales teams, support desks, and businesses** who want to automate voice calls with AI.  

---

## ✨ Features  

✅ **Phone Numbers Marketplace** – Instantly buy/manage numbers  
✅ **Outbound & Inbound Calls** – Call any number, receive calls on your AI assistant  
✅ **AI-Powered Voices** – Choose different natural voices for your agents  
✅ **Call Transcripts & Recording** – Every call logged, searchable, and replayable  
✅ **Smart Scheduling** – Customers can book appointments directly by voice  
✅ **Lead Generation** – Calls automatically converted into leads  
✅ **Admin Dashboard** – Track calls, cost, durations with live charts  
✅ **Full Animations** – Smooth UI built with **Framer Motion & TailwindCSS**  
✅ **Secure Backend** – FastAPI + JWT auth + PostgreSQL  

---

## 🖥️ Tech Stack  

**Frontend:**  
- ⚡ [Next.js](https://nextjs.org/)  
- ⚛️ [React](https://react.dev/)  
- 🎨 [Tailwind CSS](https://tailwindcss.com/)  
- 📊 [Recharts](https://recharts.org/) (animated graphs & stats)  
- ✨ [Framer Motion](https://www.framer.com/motion/) (smooth animations)  

**Backend:**  
- 🐍 [Python FastAPI](https://fastapi.tiangolo.com/)  
- 🗄️ PostgreSQL / Redis  
- 🔑 JWT Authentication  
- ☁️ Twilio / VAPI integration for calls  

---

## 🚀 Getting Started  

### 1️⃣ Clone the Repository  
```bash

## Frontend Setup (Next.js + React)
cd frontend
npm install
npm run dev


Runs on 👉 http://localhost:3000

3️⃣ Backend Setup (FastAPI)
cd backend
pip install -r requirements.txt
uvicorn main:app --reload


Runs on 👉 http://localhost:8000

4️⃣ Environment Variables

Create a .env file in both frontend/ and backend/ with keys for:

API URLs

Database connection string

Twilio / VAPI credentials

JWT secrets

📊 Dashboard Preview

✨ Fully animated and responsive admin panel

📞 Call Flow
flowchart TD
    A[📞 Customer Calls] -->|Routed| B[🤖 AI Agent Answers]
    B --> C{Intent?}
    C -->|Booking| D[📅 Schedule Meeting]
    C -->|Lead| E[📝 Create Lead]
    C -->|Question| F[💬 Provide AI Answer]
    D --> G[✅ Confirmation SMS/Email]
    E --> H[📊 CRM Entry]
    F --> I[📂 Transcript + Log]

🛠️ Development Notes

Frontend:
Built with Next.js + Tailwind + Framer Motion → super smooth animations.

Backend:
FastAPI with async DB queries for speed.

Realtime:
Call events update dashboard live via polling/websockets.

🤝 Contributing

We ❤️ contributions!

Fork the repo

Create a feature branch

Commit changes

Open a PR 🚀

📜 License

MIT License – free to use, modify & distribute.

⭐ Star This Repo!

If you like this project, please give it a star ⭐ on GitHub.
It helps others find this project and motivates us to improve it.

🔥 Final Note

This isn’t just a call app – it’s a full AI-powered voice platform.
Sell, support, and scale your business with AI Voice Agents 🚀.


---

⚡ This README will make your repo look **enterprise-level** and “sbardast” as you said 😅.  

Do you also want me to create a **fancy banner image** (with your project name + tagline) for the top of the README? That makes it look even more premium.



git clone https://github.com/your-username/ai-voice-agent.git
cd ai-voice-agent
