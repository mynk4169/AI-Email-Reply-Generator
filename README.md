GEMINI_URL=https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=;GEMINI_KEY=AIzaSyCmIiY6ZuRRWeq-seTZyTwGIAKlib0dU3U 
Here is a **professional, clean, and interview-ready `README.md`** for your project.
You can **directly copy–paste** this into your GitHub repository ✅

---

# 🚀 AI Email Reply Generator – Chrome Extension

An **AI-powered Email Reply Generator** that integrates directly into **Gmail** using a **Chrome Extension**.
It leverages **Google Gemini AI** to generate **context-aware, professional email replies**, helping users save time and boost productivity.

---

## 📌 Project Motivation

Writing email replies—especially repetitive or professional responses—can be time-consuming.
The motive of this project is to **automate email replies using AI** and **integrate it seamlessly into Gmail**, so users can generate smart responses **without leaving their inbox**.

---

## ✨ Features

* 🧠 **AI-Powered Replies** using Google Gemini AI
* 📧 **Chrome Extension** that adds an **“AI Reply” button inside Gmail**
* ⚡ **Instant reply generation** from email context
* 🌐 **Web Interface** to generate replies using custom prompts
* 🔐 **Secure backend** (API keys hidden from frontend)
* 🎨 Clean and responsive UI using **Material UI**

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Material UI
* JavaScript

### Backend

* Spring Boot
* REST APIs

### AI

* Google Gemini API

### Browser Extension

* Chrome Extension (Manifest V3)
* Content Scripts & Background Scripts

---

## 🏗️ Project Architecture

```
Chrome Extension / React UI
          |
          |  (HTTP Request)
          ↓
Spring Boot Backend
          |
          |  (Prompt Request)
          ↓
Google Gemini AI
          |
          |  (AI Response)
          ↓
Reply injected into Gmail / UI
```

---

## ⚙️ How It Works

1. User clicks **“AI Reply”** inside Gmail or enters a prompt on the website
2. Email content / prompt is sent to **Spring Boot backend**
3. Backend forwards the request to **Gemini AI**
4. Gemini generates a context-aware reply
5. Reply is sent back and **inserted into Gmail’s reply box**

---

## 🧩 Chrome Extension Workflow

* Uses **MutationObserver** to detect Gmail reply box
* Injects **AI Reply button** dynamically
* Captures email context
* Sends request to backend
* Inserts generated reply into Gmail editor

---

## 🔐 Security Measures

* Gemini API key stored securely in backend (`application.properties`)
* Frontend & extension never expose API keys
* Backend acts as a secure middleware

---

## 🚀 Setup Instructions

### 1️⃣ Backend (Spring Boot)

```bash
git clone https://github.com/mynk4169/AI-Email-Reply-Generator.git
cd backend
```

* Add Gemini API key in `application.properties`
* Run the Spring Boot application

---

### 2️⃣ Frontend (React)

```bash
cd frontend
npm install
npm start
```

---

### 3️⃣ Chrome Extension

1. Open Chrome → `chrome://extensions/`
2. Enable **Developer Mode**
3. Click **Load unpacked**
4. Select the `extension` folder
5. Open Gmail and start replying 🎉

---

## 📈 Future Enhancements

* User authentication (JWT / OAuth)
* Tone selection (Formal, Casual, Friendly)
* Reply history & personalization
* Support for Outlook / Yahoo Mail
* Rate limiting & caching

---

## 👨‍💻 What I Learned

* Full-stack application development
* AI API integration
* Chrome extension development
* Secure API handling
* DOM manipulation in real-world applications

---

## 🧑‍🎓 Author

**Mayank Thakre**
B.Tech CSE (AIML)
Full Stack Developer | AI Enthusiast

🔗 GitHub: [https://github.com/mynk4169](https://github.com/mynk4169)

---


