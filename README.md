# DebateIQ-Real---Time-Fallacy-Logic-Engine
DebateIQ is a real-time reasoning analytics system designed to identify flawed logic and fallacious arguments in spoken or multimedia content. Whether used in debate rooms, legal environments, or live broadcasts, DebateIQ empowers users with instant insights into the quality of reasoning in conversations.

Built using advanced speech processing and NLP pipelines, it transcribes spoken content and evaluates its logical consistency on the fly using large language models.

💡 What It Does
🗣️ Real-Time Speech Capture
Listens to microphone input and transcribes it into text using Google Cloud’s Speech-to-Text API.

🧩 Fallacy Analysis Engine
Uses the Gemini API to process the text and identify logical fallacies like ad hominem, false cause, or strawman arguments.

🔄 Cross-Platform Input
Supports not just live voice but also audio/video from YouTube, podcasts, and online meetings.

🌐 Web Interface
A lightweight Flask-based UI displays analysis in real-time—ideal for multi-user scenarios like debates, journalism, or academic discussions.

🛠️ Tech Stack & Requirements
Python 3.12+

Flask for backend and frontend

Google Speech Recognition (STT)

Gemini AI API for text reasoning

Utilities: youtube-dlp, ffmpeg, pyaudio for multimedia ingestion

⚙️ Installation Guide


🧪 How to Use
Start Speaking – The system records and transcribes your voice to a text file.

Analyze – The text is sent to Gemini API, where logical fallacies are detected.

View Output – The web interface shows the reasoning issues and feedback in real-time.

🚀 Planned Features & Enhancements
Integration with custom NLP models for domain-specific fallacy detection

Improved streaming support from platforms like Zoom, Teams, or Twitter Spaces

Enhanced response time and fallacy classification depth

Visual analytics dashboard with argument scoring and speaker tagging

🎯 Use Cases
Academic debate evaluations

Legal cross-examination analysis

Journalism and fact-checking

Public speaking coaching

Podcast or video comment moderation
