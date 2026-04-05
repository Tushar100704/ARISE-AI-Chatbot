# 🤖 ARISE AI Chatbot

![GitHub stars](https://img.shields.io/github/stars/Tushar100704/ai-sdk-starter-groq?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/Tushar100704/ai-sdk-starter-groq?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/Tushar100704/ai-sdk-starter-groq?style=for-the-badge)
![License](https://img.shields.io/github/license/Tushar100704/ai-sdk-starter-groq?style=for-the-badge)
![Vercel](https://img.shields.io/badge/Deployed-Vercel-black?style=for-the-badge&logo=vercel)

---

ARISE AI Chatbot is a real-time AI assistant built using Next.js, Vercel AI SDK, and Groq API.  
It delivers ultra-fast responses with streaming support and is designed for scalability and future AI integrations.

---

## 🚀 Features

- Ultra-fast AI responses using Groq API  
- Real-time streaming chat interface  
- Context-aware conversations (extendable with memory)  
- Tool integration support (APIs, automation, etc.)  
- Modern UI with Tailwind CSS + shadcn/ui  
- Responsive design (mobile + desktop)  
- Secure backend API handling  

---

## 🧠 Tech Stack

- Frontend: Next.js (App Router)  
- AI Integration: Vercel AI SDK + Groq API  
- UI: Tailwind CSS + shadcn/ui  
- Backend: Next.js API Routes  
- Deployment: Vercel  

---

## ⚙️ How It Works

1. User enters a message in the chat UI  
2. Request is sent to the backend API (/api/chat)  
3. Groq model processes the input  
4. Response is streamed back in real-time  
5. UI updates instantly  

---

## 📂 Project Structure

/app  
  /api/chat/route.ts   → AI backend logic  
  /page.tsx            → Chat UI  
/components            → UI components  
/lib                   → AI configuration  

---

## 🔐 Environment Variables

Create a .env.local file in the root directory:

GROQ_API_KEY=your_groq_api_key_here

---

## ▶️ Run Locally

git clone https://github.com/Tushar100704/ai-sdk-starter-groq  
cd ai-sdk-starter-groq  

npm install  
npm run dev  

Open: http://localhost:3000  

---

## 🌐 Deployment

Deploy using Vercel:

vercel  

Set environment variable in dashboard:

GROQ_API_KEY  

---

## 🧩 Future Improvements

- Add memory (chat history with database)  
- Voice input/output (Speech AI)  
- Tool calling (weather, finance APIs, etc.)  
- Authentication (Clerk / Auth.js)  
- Analytics & logging  
- Multi-agent system  

---

## 🧾 Use Cases

- Personal AI Assistant  
- Customer Support Chatbot  
- Fintech AI (Finmate integration)  
- EdTech Tutor  
- Productivity Assistant  

---

## 👨‍💻 Author

Tushar Ingle  
ENTC Engineer | AI Developer | Founder @ Global Shreni  

---

## ⭐ Project Highlight

Built a real-time AI chatbot using Groq + Next.js with streaming responses and scalable architecture.

---

## 📌 License

This project is open-source under the MIT License.
