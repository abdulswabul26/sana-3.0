# 📘 Sana 2.0 — Mental Health Companion App

Sana 2.0 is a simple, supportive mental-health companion designed to help students and young adults track their emotional well-being.  
The platform provides a calm environment where users can chat, journal, explore wellness resources, and personalize their experience through an intuitive dashboard.

---

## 🌟 Features

### 🗣️ AI-Style Chat Support
A warm, friendly chat interface that encourages users to express their thoughts and feelings. The chat system provides supportive responses and emotional comfort.

### 📓 Private Journal
A secure, personal space where users can document daily experiences, emotions, and reflections, helping them build self-awareness over time.

### 📊 Mood Tracking
Simple tools to log daily moods and track emotional patterns. Designed for clarity and long-term mental-health progress monitoring.

### 📚 Wellness Resources
A curated library of self-help articles, coping strategies, and mental-health guides to support users in their personal growth journey.

### 🎓 Student Dashboard
A clean and responsive dashboard tailored for students, giving quick access to chat, journal, resources, settings, and personal insights.

### ⚙️ Settings & Personalization
Users can customize their experience, manage preferences, and improve usability.

---

## 🧩 Tech Stack

| Layer        | Technology                    |
|--------------|--------------------------------|
| **Frontend** | HTML, CSS, JavaScript          |
| **Backend**  | PHP                            |
| **Structure**| Modular, organized architecture |
| **Assets**   | CSS, JS, and images under `/public/assets` |

---

<h2>Project File Structure</h2>

<pre>
sana-2.0/
├── .gitignore
├── README.md
├── LICENSE

├── public/
│   ├── index.html
│   ├── chat.html
│   ├── features.html
│   ├── journal.html
│   ├── resources.html
│   ├── settings.html
│   ├── stdntdashb.html
│   └── assets/
│       ├── css/
│       ├── js/
│       └── img/

├── src/
│   ├── php/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── utils/
│   │   └── index.php
│   │
│   └── js/
│       ├── chat/
│       ├── journal/
│       └── common/

├── config/
│   ├── config.php
│   └── routes.php

├── tests/
│   ├── php/
│   └── js/

└── docs/
    ├── architecture.md
    ├── api.md
    └── contributing.md
</pre>

### 1. Clone the Repository
```bash
git clone https://github.com/Ruba-hub/sana-2.0.git
cd sana-2.0

2. Start a Local PHP Server
php -S localhost:8000 -t public

Then open:
👉 http://localhost:8000
3. (Optional) Use XAMPP / Apache / Nginx
Point the server root to the /public folder.

🤝 Contributing
We welcome all contributions that improve functionality, design, or user experience!
Steps:


Fork the repository


Create a new branch


Commit your changes


Push to your fork


Open a Pull Request


See /docs/contributing.md for more details.

🛡️ Security & Privacy
Sana 2.0 is designed with emotional safety in mind.
All journal entries and chat interactions remain private on the user’s environment.
No mental-health data is shared externally.
⚠️ If converting this app to a cloud platform, ensure proper encryption and secure backend integration.

📄 License
This project is open-source under the MIT License.
You are free to use, modify, and distribute it responsibly.

💬 About Sana 2.0
Sana 2.0 aims to bring comfort, clarity, and emotional support to users seeking a friendly space to express themselves.
It is built with simplicity, accessibility, and empathy as core values.

If you want, I can also generate:  
✅ Screenshots section  
✅ Shields.io badges  
✅ A project logo  
Just say "add screenshots" or "add badges"!
