# DynaTech
# AI Chatbot Integration Project

## Overview
This project is an AI-powered chatbot integration developed using Botpress Cloud. The chatbot was designed to demonstrate conversational AI, automated user interaction, and modern chatbot deployment for portfolio and educational showcase purposes.

The chatbot is integrated into a professional portfolio website and provides users with an interactive conversational experience through a modern web-based chat interface.

---

## Live Demo
### Chatbot Application
https://cdn.botpress.cloud/webchat/v3.6/shareable.html?configUrl=https://files.bpcontent.cloud/2026/04/23/09/20260423095508-0MHJMVOQ.json
<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/bf07c81a-21a0-4e48-ae09-a073f7a15e84" />

---

## Features
- AI-powered conversational chatbot
- Real-time user interaction
- Responsive chatbot interface
- Modern webchat integration
- User-friendly experience
- Portfolio-ready deployment
- Cloud-hosted chatbot system

---

## Technologies Used
- Botpress Cloud
- Generative AI
- Conversational AI
- Webchat Integration
- HTML
- CSS
- JavaScript

---

## Project Objectives
The main objectives of this project were:
- To demonstrate AI chatbot integration
- To create an interactive user experience
- To explore conversational AI technologies
- To showcase practical AI implementation skills
- To improve portfolio interactivity and engagement

---

## System Functionality
The chatbot allows users to:
- Interact with an AI assistant
- Ask questions
- Receive automated responses
- Experience conversational AI in real time

The system uses Botpress Webchat integration for deployment and interaction handling.

---

## Architecture Overview
Frontend Interface → Botpress Cloud → AI Processing → User Response

The chatbot operates using a cloud-hosted conversational AI infrastructure powered by Botpress.

---

## UI/UX Design
The chatbot interface was designed with:
- Clean modern styling
- Responsive layout
- Easy accessibility
- Smooth interaction flow
- Professional appearance

---

## Deployment
The chatbot was deployed using Botpress Cloud Webchat deployment tools.

Botpress allows chatbot embedding through webchat integration and cloud deployment services.

---

## Skills Demonstrated
- AI Integration
- Conversational AI
- Prompt Engineering
- Web Integration
- UI/UX Design
- Problem Solving
- Technical Deployment
- Responsive Design

---

## Learning Outcomes
Through this project, I gained experience in:
- AI chatbot development
- Botpress platform usage
- Cloud chatbot deployment
- User interaction design
- AI-powered automation concepts
- Frontend integration techniques

---

## Future Improvements
Future versions of the project may include:
- Advanced AI memory features
- Multi-language support
- Voice interaction
- Analytics dashboard
- Enhanced personalization
- Integration with external APIs

---

## Author
### Lerato Alice Zitha

Aspiring AI, IT & Administrative Professional passionate about Artificial Intelligence, educational technology, and digital innovation.

---

## References
- Botpress Documentation: https://botpress.com/docs/webchat/get-started/introduction
- Botpress Webchat Integration: https://botpress.com/docs/webchat/get-started/embedding-webchat
GitHub Repository Structure

Use this structure for your GitHub repository:

AI-Chatbot-Integration/
│
├── README.md
├── index.html
├── styles.css
├── script.js
├── assets/
│   ├── screenshots/
│   └── images/
└── docs/
    └── project-documentation.pdf
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AI Chatbot Integration</title>

  <link rel="stylesheet" href="styles.css" />

  <script src="https://cdn.botpress.cloud/webchat/v3.6/inject.js"></script>
</head>

<body>

  <div class="container">
    <h1>AI Chatbot Integration Project</h1>

    <p>
      This project demonstrates conversational AI integration using Botpress Cloud.
    </p>

    <button id="open-chat">Open Chatbot</button>
  </div>

  <script>
    window.botpress.init({
      "botId": "your-bot-id",
      "configuration": {
        "website": {},
        "email": {},
        "phone": {},
        "termsOfService": {},
        "privacyPolicy": {},
        "variant": "soft",
        "themeMode": "light",
        "fontFamily": "Inter"
      },
      "clientId": "your-client-id"
    });

    document.getElementById("open-chat").addEventListener("click", () => {
      window.botpress.open();
    });
  </script>

</body>
</html>
styles.css
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f5f7fb;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  color: #1e293b;
}

.container {
  text-align: center;
  background: white;
  padding: 40px;
  border-radius: 16px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.08);
}

button {
  padding: 12px 24px;
  border: none;
  background: #2563eb;
  color: white;
  border-radius: 8px;
  cursor: pointer;
  transition: 0.3s ease;
}

button:hover {
  background: #1d4ed8;
}
script.js
console.log("AI Chatbot Integration Loaded");
