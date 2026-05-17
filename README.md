# NeuralNexus
 Neural Nexus — AI Powered EdTech Platform
Neural Nexus is a modern AI-powered educational web application designed to simplify complex academic content into easy, Gen-Z style explanations. Students can upload notes or PDFs and instantly “Glow Up” their study material into understandable, engaging explanations.


🎯 Objective

Simplify difficult academic content

Make learning engaging using modern language

Provide an interactive AI-powered study assistant

Improve student understanding and retention


✨ Core Features

📄 Document / Notes upload UI

✨ Glow Up button to simplify content

💬 Chat-style interface for AI explanations

🕘 Chat history page

🔐 Authentication UI (to be connected with Supabase)

📱 Fully responsive dark-themed futuristic UI


🛠️ Tech Stack
🎨 Frontend (This Repository)

HTML

CSS (Dark theme: Purple, Blue, Black, Grey)

Responsive design with Flexbox/Grid

⚙️ Backend (Handled separately)

Node.js

Express.js

OpenRouter API (AI processing)

🗄️ Database & Auth (Handled separately)

Supabase (user data + chat history)

🚀 Deployment

Vercel


🏗️ System Architecture
Frontend (HTML/CSS/JS UI)
        ↓
Backend API (Node.js + Express)
        ↓
OpenRouter API (AI processing)
        ↓
Supabase (Database & Authentication)
        ↓
Vercel (Deployment)


🔄 Workflow

User logs in

Uploads notes or types text

Clicks Glow Up ✨

Backend sends content to AI

AI returns simplified explanation

Response shown in chat UI

Chats saved to database

User can view past chats in History


👥 Team Roles

Role
Name
Responsibility
Frontend Developer
Harshini
UI/UX, HTML/CSS, responsive design
Backend Developer
Rene
API, AI integration, server logic
Database & Auth Developer
Naithik
Supabase, authentication, chat storage


📁 Pages

index.html — Landing / Login page

chat.html — Main AI chat interface

history.html — Chat history UI

style.css — Global styling


🔐 Security Measures (Planned)

API keys stored in environment variables

No sensitive data on frontend

Supabase authentication

.env and .gitignore for secrets


🚀 Future Enhancements

🎙️ Voice explanations

🧠 Flashcard generation

❓ Quiz generation from notes

🎨 Multiple explanation styles

🔍 Auto highlight key concepts


⚠️ Important Note
This repository contains only the frontend UI.

Backend, AI integration, and database functionality will be connected separately by other team members.


🌐 Deployment
The project is deployed using Vercel.


📌 Conclusion
Neural Nexus aims to transform the way students interact with study material by combining AI 
