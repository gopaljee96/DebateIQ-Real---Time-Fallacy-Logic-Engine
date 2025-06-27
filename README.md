# 🚀 DebateIQ – Real-Time Fallacy & Logic Engine

**DebateIQ** is a real-time reasoning analytics system designed to identify flawed logic and fallacious arguments in spoken or multimedia content. Whether used in debate rooms, legal environments, or live broadcasts, DebateIQ empowers users with instant insights into the quality of reasoning in conversations.

Built using advanced speech processing and NLP pipelines, it transcribes spoken content and evaluates its logical consistency on the fly using large language models.

---

## 💡 What It Does

- 🎙️ **Real-Time Speech Capture**  
  Listens to microphone input and transcribes it into text using Google Cloud’s Speech-to-Text API.

- 🧠 **Fallacy Analysis Engine**  
  Uses the Gemini API to process the text and identify logical fallacies like ad hominem, false cause, or strawman arguments.

- 📡 **Cross-Platform Input Support**  
  Works with live speech, YouTube videos, online meetings, and podcast audio.

- 🌐 **Interactive Web Dashboard**  
  Flask-based UI displays detected fallacies and insights in real-time for debate moderators, educators, or analysts.

---

## 🛠️ Tech Stack & Requirements

- Python 3.12+
- Flask (for backend and web interface)
- Google Speech-to-Text API
- Gemini API (logical fallacy detection)
- `youtube-dlp`, `ffmpeg`, `pyaudio` (for multimedia handling)

---

## ⚙️ Installation Guide

### 📥 Step 1: Clone the Repository

```bash
git clone [https://github.com/gopaljee96](https://github.com/gopaljee96/DebateIQ-Real---Time-Fallacy-Logic-Engine.git)
cd DebateIQ

---

## ⚙️ Setup Instructions

Follow the steps below to install and run the application locally:

---


🔑 Step 3: Add Your Gemini API Key
The Gemini API is required for real-time logic and fallacy detection. To use it:

Create a .env file in the root of the project directory.

Add your Gemini API key using the format below.
# .env file
GEMINI_API_KEY=your_gemini_api_key_here

---
🚀 Step 4: Run the Application
Once the dependencies and API key are configured, launch the Flask server:
# Run the Flask server
python server.py

After the server starts, open your browser and navigate to:
http://localhost:5000/










